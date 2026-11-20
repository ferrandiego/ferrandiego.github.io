# ferrandiego.github.io

Web personal de Ferran Diego.

Estática, servida por [GitHub Pages](https://pages.github.com/), construida con [Jekyll](https://jekyllrb.com/) sobre el template [AcademicPages](https://github.com/academicpages/academicpages.github.io) (tema Minimal Mistakes) con una capa de estilos moderna en [`assets/css/custom.css`](assets/css/custom.css).

## Estructura de lo que importa

| Archivo | Qué es |
|---|---|
| `_pages/about.md` | Portada: bio, intereses y **News** |
| `_pages/publications.md` | Lista de publicaciones (con BibTeX desplegable) |
| `_pages/cv.md` | Página "Misc": CV, educación y service |
| `_config.yml` | Nombre, descripción, redes y otros ajustes globales |
| `assets/css/custom.css` | Estilos propios (fuente Inter, tarjetas de papers, timeline de news, tabla CV) |

Todo lo demás (`_layouts`, `_includes`, `_sass`) es parte del tema y no se toca normalmente.

## Cómo actualizar la web

1. `git pull`
2. Editar el archivo correspondiente:
   - **Noticia nueva** → añadir una `<li>` al principio de la lista `news-timeline` en `_pages/about.md`.
   - **Paper nuevo** → copiar una entrada `pub-item` en `_pages/publications.md` (la sección y el orden que corresponda). El `id` del `<div class="bibtex">` tiene que ser `bib_<claves>` y encajar con `toggleBibtex('<claves>')`. Añade también `data-year="AAAA"` al `<li class="pub-item">`: el filtro de la cabecera (búsqueda, año y tipo) lo necesita.
   - **Puesto / CV** → editar la tabla `cv-table` en `_pages/cv.md`.
   - **Descripción / redes** → sección `author:` en `_config.yml`.
3. Revisar localmente (ver abajo) y `git push`. GitHub Pages reconstruye la web en ~1 minuto.

## Verla localmente

```bash
gem install jekyll jekyll-feed jekyll-redirect-from jekyll-gist
bundle exec jekyll serve    # o: jekyll serve
```

Y abrir <http://localhost:4000>.

## Notas

- El PDF del CV enlaça a Dropbox (ver enlace en `_pages/cv.md` si se renueva).
- La página de publicaciones es la única fuente: el antiguo `publications.html` (duplicado) fue eliminado.
- Los enlaces de proyectos antiguos de HCI apuntan a `hciweb.iwr.uni-heidelberg.de` (el dominio viejo `hci.iwr` devuelve errores en las páginas de staff).
