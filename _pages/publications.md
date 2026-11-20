---
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

You can also browse my <a href="https://scholar.google.es/citations?user=aYO_0vgAAAAJ">Google Scholar profile</a>.

<div class="pub-filters" id="pubFilters">
  <input type="search" id="pubSearch" class="pub-search" placeholder="Search title, author or venue…" aria-label="Search publications">
  <select id="pubYear" class="pub-select" aria-label="Filter by year">
    <option value="all">All years</option>
    <option value="2020-2025">2020 – 2025</option>
    <option value="2010-2019">2010 – 2019</option>
    <option value="2006-2009">2006 – 2009</option>
  </select>
  <div class="pub-chips" role="group" aria-label="Filter by type">
    <button type="button" class="pub-chip is-active" data-type="all">All</button>
    <button type="button" class="pub-chip" data-type="journals">Journals</button>
    <button type="button" class="pub-chip" data-type="conferences">Conferences</button>
    <button type="button" class="pub-chip" data-type="preprints">Preprints</button>
    <button type="button" class="pub-chip" data-type="books">Books</button>
  </div>
  <span class="pub-count" id="pubCount" aria-live="polite"></span>
</div>
<p class="pub-nomatch" id="pubNoMatch" hidden>No publications match your search.</p>


<style>
    /*************************************
     The box that contains BibTeX code
     *************************************/
div.noshow { display: none; }
</style>
<script type="text/javascript">
    // Toggle display of BibTeX
    function toggleBibtex(articleid) {
        var bib = document.getElementById('bib_' + articleid);
        if (bib) {
            if (bib.className.indexOf('bibtex') != -1) {
                bib.className.indexOf('noshow') == -1 ? bib.className = 'bibtex noshow' : bib.className = 'bibtex';
            }
        } else {
            return;
        }
    }
</script>

<h3 class="pub-section" data-type="journals">Journals</h3>

<ul class="biblist">

<!-- Item: theodoropoulos2023a -->
<li class="pub-item" data-year="2023">
  <p class="pub-authors">T. Theodoropoulos, L. Rosa, C. Benzaid, P. Gray, E. Marin, A. Makris, L. Cordeiro, <b>F. Diego</b>, P. Sorokin, M. Di Girolamo, P. Barone, T. Taleb and K. Tserpes.</p>
  <p class="pub-title"><b>Security in Cloud-Native Services: A Survey</b><br>
  <i>Journal of Cybersecurity and Privacy</i>, 3(4), 758–793, 2023.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('theodoropoulos2023a')">[BibTeX]</a>
    <a href="https://doi.org/10.3390/jcp3040034" target="_blank" rel="noopener">[PDF]</a>
  </p>
  <div id="bib_theodoropoulos2023a" class="bibtex noshow">
  <pre>@article{theodoropoulos2023a,
  author  = {Theodoropoulos, Theodoros and Rosa, Luis and Benzaid, Chafika and Gray, Peter and Marin, Eduard and Makris, Antonios and Cordeiro, Luis and Diego, Ferran and Sorokin, Pavel and Di Girolamo, Marco and Barone, Paolo and Taleb, Tarik and Tserpes, Konstantinos},
  title   = {Security in Cloud-Native Services: A Survey},
  journal = {Journal of Cybersecurity and Privacy},
  volume  = {3},
  number  = {4},
  pages   = {758--793},
  year    = {2023},
  doi     = {10.3390/jcp3040034}
}
  </pre>
  </div>
</li>

<!-- Item: milbich2020a -->
<li class="pub-item" data-year="2020">
  <p class="pub-authors">T. Milbich, O. Ghori, <b>F. Diego</b> and B. Ommer.</p>
  <p class="pub-title"><b>Unsupervised Representation Learning by Discovering Reliable Image Relations</b><br>
  <i>Pattern Recognition</i>, 102, 107107, 2020.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('milbich2020a')">[BibTeX]</a>
    <a href="https://doi.org/10.1016/j.patcog.2019.107107" target="_blank" rel="noopener">[PDF]</a>
  </p>
  <div id="bib_milbich2020a" class="bibtex noshow">
  <pre>@article{milbich2020a,
  author  = {Milbich, T. and Ghori, Omer and Diego, Ferran and Ommer, Bernhard},
  title   = {Unsupervised Representation Learning by Discovering Reliable Image Relations},
  journal = {Pattern Recognition},
  volume  = {102},
  pages   = {107107},
  year    = {2020},
  doi     = {10.1016/j.patcog.2019.107107}
}
  </pre>
  </div>
</li>

<!-- Item: diego2013tmm -->
<li class="pub-item" data-year="2013">
  <p class="pub-authors"><b>F. Diego</b>, J. Serrat and A. M. López.</p>
  <p class="pub-title"><b>Joint Spatio-Temporal Alignment of Sequences</b><br>
  <i>IEEE Trans. on Multimedia (TMM)</i>, 15(6), 1377–1387, 2013.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2013tmm')">[BibTeX]</a>
    <a href="https://hci.iwr.uni-heidelberg.de/sites/default/files/publications/files/348209579/diego_12_joint.pdf" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://hciweb.iwr.uni-heidelberg.de/Staff/fdiego/JointVA" target="_blank" rel="noopener">[Project Page]</a>
  </p>
  <div id="bib_diego2013tmm" class="bibtex noshow">
  <pre>@article{diego2013tmm,
  author  = {Diego, Ferran and Serrat, Joan and L\'opez, Antonio M.},
  title   = {Joint Spatio-Temporal Alignment of Sequences},
  journal = {IEEE Transactions on Multimedia},
  volume  = {15},
  number  = {6},
  pages   = {1377--1387},
  year    = {2013}
}
  </pre>
  </div>
</li>

<!-- Item: alvarez2012a -->
<li class="pub-item" data-year="2012">
  <p class="pub-authors">J. M. Álvarez, T. Gevers, <b>F. Diego</b> and A. M. López.</p>
  <p class="pub-title"><b>Road Geometry Classification by Adaptive Shape Models</b><br>
  <i>IEEE Trans. on Intelligent Transportation Systems (T-ITS)</i>, 14(1), 459–468, 2012.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('alvarez2012a')">[BibTeX]</a>
    <a href="https://doi.org/10.1109/TITS.2012.2221088" target="_blank" rel="noopener">[PDF]</a>
  </p>
  <div id="bib_alvarez2012a" class="bibtex noshow">
  <pre>@article{alvarez2012a,
  author  = {Alvare\'iz, Jose M. and Gevers, Theo and Diego, Ferran and L\'opez, Antonio M.},
  title   = {Road Geometry Classification by Adaptive Shape Models},
  journal = {IEEE Transactions on Intelligent Transportation Systems},
  volume  = {14},
  number  = {1},
  pages   = {459--468},
  year    = {2012},
  doi     = {10.1109/TITS.2012.2221088}
}
  </pre>
  </div>
</li>

<!-- Item: diego2011a -->
<li class="pub-item" data-year="2011">
  <p class="pub-authors"><b>F. Diego</b>, D. Ponsa, J. Serrat and A. M. López.</p>
  <p class="pub-title"><b>Video Alignment for Change Detection</b><br>
  <i>IEEE Trans. on Image Processing (TIP)</i>, 20(7), 1858–1869, 2011.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2011a')">[BibTeX]</a>
    <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5648349" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://hciweb.iwr.uni-heidelberg.de/Staff/fdiego/VideoAlignemnt" target="_blank" rel="noopener">[Project Page]</a>
  </p>
  <div id="bib_diego2011a" class="bibtex noshow">
  <pre>@article{diego2011a,
  author  = {Diego, Ferran and Ponsa, Daniel and Serrat, Joan and L\'opez, Antonio M.},
  title   = {Video Alignment for Change Detection},
  journal = {IEEE Transactions on Image Processing},
  volume  = {20},
  number  = {7},
  pages   = {1858--1869},
  year    = {2011}
}
  </pre>
  </div>
</li>

<!-- Item: serrat2008a -->
<li class="pub-item" data-year="2008">
  <p class="pub-authors">J. Serrat, <b>F. Diego</b>, F. Lumbreras, J. M. Álvarez, A. M. López and C. Elvira.</p>
  <p class="pub-title"><b>Dynamic Comparison of Headlights</b><br>
  <i>Proc. Inst. Mech. Eng. Part D: J. Automobile Engineering</i>, 222(5), 643–656, 2008.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('serrat2008a')">[BibTeX]</a>
    <a href="https://doi.org/10.1243/09544070jauto655" target="_blank" rel="noopener">[DOI]</a>
  </p>
  <div id="bib_serrat2008a" class="bibtex noshow">
  <pre>@article{serrat2008a,
  author  = {Serrat, Joan and Diego, Ferran and Lumbreras, Felipe and Alvare\'iz, Jose M. and L\'opez, Antonio M. and Elvira, Concepci\'on},
  title   = {Dynamic Comparison of Headlights},
  journal = {Proceedings of the Institution of Mechanical Engineers, Part D: Journal of Automobile Engineering},
  volume  = {222},
  number  = {5},
  pages   = {643--656},
  year    = {2008},
  doi     = {10.1243/09544070jauto655}
}
  </pre>
  </div>
</li>

</ul>

<h3 class="pub-section" data-type="conferences">Conferences and Workshops</h3>


<ul class="biblist">

<!-- Item: alvarez2025a -->
<li class="pub-item" data-year="2025">
  <p class="pub-authors">F. Álvarez, <b>F. Diego</b>, M. Rozanska, R. Sanfeliu, Y. Verginadis and G. Horn.</p>
  <p class="pub-title"><b>RemWoW: Resource Efficient Management of Workloads of Repeated Workflows</b><br>
  <i>MECC '25: Proceedings of the 2nd International Workshop on MetaOS for the Cloud-Edge-IoT Continuum</i> (co-located with EuroSys 2025), pp. 66–72, 2025.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('alvarez2025a')">[BibTeX]</a>
    <a href="https://doi.org/10.1145/3721889.3721931" target="_blank" rel="noopener">[PDF]</a>
  </p>
  <div id="bib_alvarez2025a" class="bibtex noshow">
  <pre>@inproceedings{alvarez2025a,
  author    = {Alvare\'iz, Francisco and Diego, Ferran and Rozanska, Marta and Sanfeliu, Robert and Verginadis, Yiannis and Horn, Geir},
  title     = {RemWoW: Resource Efficient Management of Workloads of Repeated Workflows},
  booktitle = {Proceedings of the 2nd International Workshop on MetaOS for the Cloud-Edge-IoT Continuum (MECC '25), co-located with EuroSys 2025},
  pages     = {66--72},
  year      = {2025},
  doi       = {10.1145/3721889.3721931}
}
  </pre>
  </div>
</li>

<!-- Item: tura2021a -->
<li class="pub-item" data-year="2021">
  <p class="pub-authors">B. Tura, S. Escuder, <b>F. Diego</b>, C. Segura and J. Luque.</p>
  <p class="pub-title"><b>Efficient Keyword Spotting by Capturing Long-Range Interactions with Temporal Lambda Networks</b><br>
  <i>IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)</i>, pp. 146–153, 2021.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('tura2021a')">[BibTeX]</a>
    <a href="https://doi.org/10.1109/ASRU51503.2021.9687932" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://arxiv.org/abs/2104.08086" target="_blank" rel="noopener">[arXiv]</a>
  </p>
  <div id="bib_tura2021a" class="bibtex noshow">
  <pre>@inproceedings{tura2021a,
  author    = {Tura, Biel and Escuder, Santiago and Diego, Ferran and Segura, Carlos and Luque, Jordi},
  title     = {Efficient Keyword Spotting by Capturing Long-Range Interactions with Temporal Lambda Networks},
  booktitle = {2021 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)},
  pages     = {146--153},
  year      = {2021},
  doi       = {10.1109/ASRU51503.2021.9687932}
}
  </pre>
  </div>
</li>

<!-- Item: valenzuela2021a -->
<li class="pub-item" data-year="2021">
  <p class="pub-authors">A. Valenzuela, C. Segura, <b>F. Diego</b> and V. Gómez.</p>
  <p class="pub-title"><b>Expression Transfer Using Flow-Based Generative Models</b><br>
  <i>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops</i> (Workshop on Media Forensics), pp. 1023–1031, 2021.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('valenzuela2021a')">[BibTeX]</a>
    <a href="https://openaccess.thecvf.com/content/CVPR2021W/WMF/papers/Valenzuela_Expression_Transfer_Using_Flow-Based_Generative_Models_CVPRW_2021_paper.pdf" target="_blank" rel="noopener">[PDF]</a>
  </p>
  <div id="bib_valenzuela2021a" class="bibtex noshow">
  <pre>@inproceedings{valenzuela2021a,
  author    = {Valenzuela, Andrea and Segura, Carlos and Diego, Ferran and G\'omez, Vicen\c{c}},
  title     = {Expression Transfer Using Flow-Based Generative Models},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
  pages     = {1023--1031},
  year      = {2021},
  doi       = {10.1109/CVPRW53098.2021.00113}
}
  </pre>
  </div>
</li>

<!-- Item: korontanis2021a -->
<li class="pub-item" data-year="2021">
  <p class="pub-authors">I. Korontanis, K. Tserpes, M. Pateraki, L. Blasi, J. Violos, <b>F. Diego</b>, E. Marin, N. Kourtellis, M. Coppola, E. Carlini, Z. Ledwoń, P. Tarkowski, T. Loven, Y. González Rozas, M. Kentros, M. Dodis and P. Dazzi.</p>
  <p class="pub-title"><b>Inter-Operability and Orchestration in Heterogeneous Cloud/Edge Resources: The ACCORDION Vision</b><br>
  <i>FRAME '21: Proceedings of the 1st Workshop on Flexible Resource and Application Management on the Edge</i> (co-located with HPDC 2021), pp. 9–14, 2021.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('korontanis2021a')">[BibTeX]</a>
    <a href="https://doi.org/10.1145/3452369.3463816" target="_blank" rel="noopener">[PDF]</a>
  </p>
  <div id="bib_korontanis2021a" class="bibtex noshow">
  <pre>@inproceedings{korontanis2021a,
  author    = {Korontanis, Ioannis and Tserpes, Konstantinos and Pateraki, Maria and Blasi, Lorenzo and Violos, John and Diego, Ferran and Marin, Eduard and Kourtellis, Nicolas and Coppola, Massimo and Carlini, Emanuele and Ledwo\'n, Zbyszek and Tarkowski, Przemyslaw and Loven, Thomas and Gonz\'alez Rozas, Yago and Kentros, Mike and Dodis, Michael and Dazzi, Patrizio},
  title     = {Inter-Operability and Orchestration in Heterogeneous Cloud/Edge Resources: The ACCORDION Vision},
  booktitle = {Proceedings of the 1st Workshop on Flexible Resource and Application Management on the Edge (FRAME '21), co-located with HPDC 2021},
  pages     = {9--14},
  year      = {2021},
  doi       = {10.1145/3452369.3463816}
}
  </pre>
  </div>
</li>

<!-- Item: oriol2020a -->
<li class="pub-item" data-year="2020">
  <p class="pub-authors">B. Oriol, J. Luque, <b>F. Diego</b> and X. Giro-i-Nieto.</p>
  <p class="pub-title"><b>Transcription-Enriched Joint Embeddings for Spoken Descriptions of Images and Videos</b><br>
  <i>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops</i> (Workshop on Egocentric Perception, Interaction and Computing), 2020.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('oriol2020a')">[BibTeX]</a>
    <a href="https://arxiv.org/abs/2006.00785" target="_blank" rel="noopener">[arXiv]</a>
  </p>
  <div id="bib_oriol2020a" class="bibtex noshow">
  <pre>@inproceedings{oriol2020a,
  author    = {Oriol, Benet and Luque, Jordi and Diego, Ferran and Giro-i-Nieto, Xavier},
  title     = {Transcription-Enriched Joint Embeddings for Spoken Descriptions of Images and Videos},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
  year      = {2020}
}
  </pre>
  </div>
</li>

<!-- Item: mackowiak2018a -->
<li class="pub-item" data-year="2018">
  <p class="pub-authors">R. Mackowiak, P. Lenz, O. Ghori, <b>F. Diego</b>, O. Lange and C. Rother.</p>
  <p class="pub-title"><b>Cereals-Cost-Effective Region-Based Active Learning for Semantic Segmentation</b><br>
  <i>British Machine Vision Conference (BMVC)</i>, 2018.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('mackowiak2018a')">[BibTeX]</a>
    <a href="https://arxiv.org/abs/1810.09726" target="_blank" rel="noopener">[arXiv]</a>
  </p>
  <div id="bib_mackowiak2018a" class="bibtex noshow">
  <pre>@inproceedings{mackowiak2018a,
  author    = {Mackowiak, Robin and Lenz, Peter and Ghori, Omer and Diego, Ferran and Lange, Otfried and Rother, Christian},
  title     = {Cereals-Cost-Effective Region-Based Active Learning for Semantic Segmentation},
  booktitle = {British Machine Vision Conference (BMVC)},
  year      = {2018}
}
  </pre>
  </div>
</li>

<!-- Item: ghori2018a -->
<li class="pub-item" data-year="2018">
  <p class="pub-authors">O. Ghori, R. Mackowiak, M. Bautista, N. Beuter, L. Drumond, <b>F. Diego</b> and B. Ommer.</p>
  <p class="pub-title"><b>Learning to Forecast Pedestrian Intention from Pose Dynamics</b><br>
  <i>IEEE Intelligent Vehicles Symposium (IV)</i>, 2018.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('ghori2018a')">[BibTeX]</a>
  </p>
  <div id="bib_ghori2018a" class="bibtex noshow">
  <pre>@inproceedings{ghori2018a,
  author    = {Ghori, Omer and Mackowiak, Robin and Bautista, M. and Beuter, N. and Drumond, L. and Diego, Ferran and Ommer, Bernhard},
  title     = {Learning to Forecast Pedestrian Intention from Pose Dynamics},
  booktitle = {IEEE Intelligent Vehicles Symposium (IV)},
  year      = {2018}
}
  </pre>
  </div>
</li>

<!-- Item: peter2017a -->
<li class="pub-item" data-year="2017">
  <p class="pub-authors">S. Peter, <b>F. Diego</b>, F. A. Hamprecht and B. Nadler.</p>
  <p class="pub-title"><b>Cost Efficient Gradient Boosting</b><br>
  <i>Advances in Neural Information Processing Systems (NeurIPS)</i>, 2017.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('peter2017a')">[BibTeX]</a>
    <a href="https://papers.nips.cc/paper/6753-cost-efficient-gradient-boosting" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://github.com/svenpeter42/LightGBM-CEGB" target="_blank" rel="noopener">[Code]</a>
  </p>
  <div id="bib_peter2017a" class="bibtex noshow">
  <pre>@inproceedings{peter2017a,
  author    = {Peter, Sven and Diego, Ferran and Hamprecht, Fred A. and Nadler, Benjamin},
  title     = {Cost Efficient Gradient Boosting},
  booktitle = {Advances in Neural Information Processing Systems (NeurIPS)},
  year      = {2017}
}
  </pre>
  </div>
</li>

<!-- Item: peter2017b -->
<li class="pub-item" data-year="2017">
  <p class="pub-authors">S. Peter, E. Kirschbaum, M. Both, L. Campbell, B. Harvey, C. Heins, D. Durstewitz, <b>F. Diego</b> and F. A. Hamprecht.</p>
  <p class="pub-title"><b>Sparse Convolutional Coding for Neuronal Assembly Detection</b><br>
  <i>Advances in Neural Information Processing Systems (NeurIPS)</i>, 2017.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('peter2017b')">[BibTeX]</a>
    <a href="https://papers.nips.cc/paper/6958-sparse-convolutional-coding-for-neuronal-assembly-detection" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://github.com/sccfnad/Sparse-convolutional-coding-for-neuronal-assembly-detection" target="_blank" rel="noopener">[Code]</a>
  </p>
  <div id="bib_peter2017b" class="bibtex noshow">
  <pre>@inproceedings{peter2017b,
  author    = {Peter, Sven and Kirschbaum, E. and Both, Michael and Campbell, L. and Harvey, Ben and Heins, C. and Durstewitz, Daniel and Diego, Ferran and Hamprecht, Fred A.},
  title     = {Sparse Convolutional Coding for Neuronal Assembly Detection},
  booktitle = {Advances in Neural Information Processing Systems (NeurIPS)},
  year      = {2017}
}
  </pre>
  </div>
</li>

<!-- Item: schiegg2016a -->
<li class="pub-item" data-year="2016">
  <p class="pub-authors">M. Schiegg, <b>F. Diego</b> and F. A. Hamprecht.</p>
  <p class="pub-title"><b>Learning Diverse Models: The Coulomb Structured Support Vector Machine</b><br>
  <i>European Conference on Computer Vision (ECCV)</i>, 2016.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('schiegg2016a')">[BibTeX]</a>
    <a href="https://hci.iwr.uni-heidelberg.de/sites/default/files/publications/files/53208582/schiegg_16_learning.pdf" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://github.com/martinsch/coulomb_ssvm" target="_blank" rel="noopener">[Code]</a>
  </p>
  <div id="bib_schiegg2016a" class="bibtex noshow">
  <pre>@inproceedings{schiegg2016a,
  author    = {Schiegg, Martin and Diego, Ferran and Hamprecht, Fred A.},
  title     = {Learning Diverse Models: The Coulomb Structured Support Vector Machine},
  booktitle = {European Conference on Computer Vision (ECCV)},
  year      = {2016}
}
  </pre>
  </div>
</li>

<!-- Item: kandemir2016a -->
<li class="pub-item" data-year="2016">
  <p class="pub-authors">M. Kandemir, M. Haussmann, <b>F. Diego</b>, K. T. Rajamani, J. van der Laak and F. A. Hamprecht.</p>
  <p class="pub-title"><b>Variational Weakly Supervised Gaussian Processes</b><br>
  <i>British Machine Vision Conference (BMVC)</i>, 2016.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('kandemir2016a')">[BibTeX]</a>
    <a href="http://www.bmva.org/bmvc/2016/papers/paper071/paper071.pdf" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://github.com/melihkandemir/vwsgp" target="_blank" rel="noopener">[Code]</a>
  </p>
  <div id="bib_kandemir2016a" class="bibtex noshow">
  <pre>@inproceedings{kandemir2016a,
  author    = {Kandemir, Melih and Haussmann, Manuel and Diego, Ferran and Rajamani, Kumar T. and van der Laak, Jeroen and Hamprecht, Fred A.},
  title     = {Variational Weakly Supervised Gaussian Processes},
  booktitle = {British Machine Vision Conference (BMVC)},
  year      = {2016}
}
  </pre>
  </div>
</li>

<!-- Item: diego2016a -->
<li class="pub-item" data-year="2016">
  <p class="pub-authors"><b>F. Diego</b> and F. A. Hamprecht.</p>
  <p class="pub-title"><b>Structured Regression Gradient Boosting</b><br>
  <i>IEEE Conference on Computer Vision and Pattern Recognition (CVPR)</i>, 2016.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2016a')">[BibTeX]</a>
    <a href="https://hci.iwr.uni-heidelberg.de/sites/default/files/publications/files/1037872734/diego_16_structured.pdf" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://hciweb.iwr.uni-heidelberg.de/Staff/fdiego/SRGB" target="_blank" rel="noopener">[Project]</a>
  </p>
  <div id="bib_diego2016a" class="bibtex noshow">
  <pre>@inproceedings{diego2016a,
  author    = {Diego, Ferran and Hamprecht, Fred A.},
  title     = {Structured Regression Gradient Boosting},
  booktitle = {IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year      = {2016}
}
  </pre>
  </div>
</li>

<!-- Item: diego2014a -->
<li class="pub-item" data-year="2014">
  <p class="pub-authors"><b>F. Diego</b> and F. A. Hamprecht.</p>
  <p class="pub-title"><b>Sparse Space-Time Deconvolution for Calcium Image Analysis</b><br>
  <i>Advances in Neural Information Processing Systems (NeurIPS)</i>, 2014.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2014a')">[BibTeX]</a>
    <a href="http://papers.nips.cc/paper/5342-sparse-space-time-deconvolution-for-calcium-image-analysis.pdf" target="_blank" rel="noopener">[PDF]</a>
  </p>
  <div id="bib_diego2014a" class="bibtex noshow">
  <pre>@inproceedings{diego2014a,
  author    = {Diego, Ferran and Hamprecht, Fred A.},
  title     = {Sparse Space-Time Deconvolution for Calcium Image Analysis},
  booktitle = {Advances in Neural Information Processing Systems (NeurIPS)},
  year      = {2014}
}
  </pre>
  </div>
</li>

<!-- Item: fiaschi2014a -->
<li class="pub-item" data-year="2014">
  <p class="pub-authors">L. Fiaschi, <b>F. Diego</b>, K. Gregor, M. Schiegg, U. Köthe, M. Zlatic and F. A. Hamprecht.</p>
  <p class="pub-title"><b>Learning to Disambiguate Indistinguishable Objects Over Time Using Weakly Supervised Structured Learning</b><br>
  <i>IEEE Conference on Computer Vision and Pattern Recognition (CVPR)</i>, 2014.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('fiaschi2014a')">[BibTeX]</a>
    <a href="https://hci.iwr.uni-heidelberg.de/sites/default/files/publications/files/219478572/fiaschi_14_tracking.pdf" target="_blank" rel="noopener">[PDF]</a>
  </p>
  <div id="bib_fiaschi2014a" class="bibtex noshow">
  <pre>@inproceedings{fiaschi2014a,
  author    = {Fiaschi, Luca and Diego, Ferran and Gregor, K. and Schiegg, Martin and K\"othe, Ullrich and Zlatic, Marta and Hamprecht, Fred A.},
  title     = {Learning to Disambiguate Indistinguishable Objects Over Time Using Weakly Supervised Structured Learning},
  booktitle = {IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year      = {2014}
}
  </pre>
  </div>
</li>

<!-- Item: diego2013sparse -->
<li class="pub-item" data-year="2013">
  <p class="pub-authors"><b>F. Diego</b> and F. A. Hamprecht.</p>
  <p class="pub-title"><b>Learning Multi-Level Sparse Representations</b><br>
  <i>Advances in Neural Information Processing Systems (NeurIPS)</i>, 2013.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2013sparse')">[BibTeX]</a>
    <a href="http://papers.nips.cc/paper/5076-learning-multi-level-sparse-representations.pdf" target="_blank" rel="noopener">[PDF]</a>
  </p>
  <div id="bib_diego2013sparse" class="bibtex noshow">
  <pre>@inproceedings{diego2013sparse,
  author    = {Diego, Ferran and Hamprecht, Fred A.},
  title     = {Learning Multi-Level Sparse Representations},
  booktitle = {Advances in Neural Information Processing Systems (NeurIPS)},
  year      = {2013}
}
  </pre>
  </div>
</li>

<!-- Item: diego2013b -->
<li class="pub-item" data-year="2013">
  <p class="pub-authors"><b>F. Diego</b>, S. Reichinnek, M. Both and F. A. Hamprecht.</p>
  <p class="pub-title"><b>Automated Identification of Neuronal Activity from Calcium Imaging by Sparse Dictionary Learning</b><br>
  <i>IEEE International Symposium on Biomedical Imaging (ISBI)</i>, 2013.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2013b')">[BibTeX]</a>
    <a href="https://hci.iwr.uni-heidelberg.de/sites/default/files/publications/files/1778693862/diego_13_automated.pdf" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://github.com/nanshe-org/nanshe" target="_blank" rel="noopener">[Code]</a>
  </p>
  <div id="bib_diego2013b" class="bibtex noshow">
  <pre>@inproceedings{diego2013b,
  author    = {Diego, Ferran and Reichinnek, Sebastian and Both, Michael and Hamprecht, Fred A.},
  title     = {Automated Identification of Neuronal Activity from Calcium Imaging by Sparse Dictionary Learning},
  booktitle = {IEEE International Symposium on Biomedical Imaging (ISBI)},
  year      = {2013}
}
  </pre>
  </div>
</li>

<!-- Item: evangelidis2013a -->
<li class="pub-item" data-year="2013">
  <p class="pub-authors">G. D. Evangelidis, <b>F. Diego</b> and R. Horaud.</p>
  <p class="pub-title"><b>From Video Matching to Video Grounding</b><br>
  <i>ICCV Workshop on Computer Vision in Vehicle Technology (ICCVW)</i>, 2013.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('evangelidis2013a')">[BibTeX]</a>
    <a href="https://hal.inria.fr/hal-00872517/document" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://team.inria.fr/perception/research/cvvt2013/" target="_blank" rel="noopener">[Project]</a>
  </p>
  <div id="bib_evangelidis2013a" class="bibtex noshow">
  <pre>@inproceedings{evangelidis2013a,
  author    = {Evangelidis, Georgios D. and Diego, Ferran and Horaud, Radu},
  title     = {From Video Matching to Video Grounding},
  booktitle = {ICCV Workshop on Computer Vision in Vehicle Technology (ICCVW)},
  year      = {2013}
}
  </pre>
  </div>
</li>

<!-- Item: diego2012a -->
<li class="pub-item" data-year="2012">
  <p class="pub-authors"><b>F. Diego</b> and F. A. Hamprecht.</p>
  <p class="pub-title"><b>Learning Latent Structure for Identifying Neuronal Activity</b><br>
  <i>NeurIPS Workshop on Machine Learning and Interpretation in NeuroImaging</i>, 2012.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2012a')">[BibTeX]</a>
  </p>
  <div id="bib_diego2012a" class="bibtex noshow">
  <pre>@inproceedings{diego2012a,
  author    = {Diego, Ferran and Hamprecht, Fred A.},
  title     = {Learning Latent Structure for Identifying Neuronal Activity},
  booktitle = {NeurIPS Workshop on Machine Learning and Interpretation in NeuroImaging},
  year      = {2012}
}
  </pre>
  </div>
</li>

<!-- Item: diego2012b -->
<li class="pub-item" data-year="2012">
  <p class="pub-authors"><b>F. Diego</b>, G. D. Evangelidis and J. Serrat.</p>
  <p class="pub-title"><b>Night-Time Outdoor Surveillance by Mobile Cameras</b><br>
  <i>International Conference on Pattern Recognition, Applications and Methods (ICPRAM)</i>, 2012.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2012b')">[BibTeX]</a>
    <a href="https://hal.inria.fr/hal-00936023/document" target="_blank" rel="noopener">[PDF]</a>
  </p>
  <div id="bib_diego2012b" class="bibtex noshow">
  <pre>@inproceedings{diego2012b,
  author    = {Diego, Ferran and Evangelidis, Georgios D. and Serrat, Joan},
  title     = {Night-Time Outdoor Surveillance by Mobile Cameras},
  booktitle = {International Conference on Pattern Recognition, Applications and Methods (ICPRAM)},
  year      = {2012}
}
  </pre>
  </div>
</li>

<!-- Item: evangelidis2011a -->
<li class="pub-item" data-year="2011">
  <p class="pub-authors">G. D. Evangelidis, <b>F. Diego</b>, J. Serrat and A. M. López.</p>
  <p class="pub-title"><b>Slice Matching for Accurate Spatio-Temporal Alignment</b><br>
  <i>ICCV Workshop on Visual Surveillance</i>, 2011.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('evangelidis2011a')">[BibTeX]</a>
    <a href="https://hal.inria.fr/hal-00936021/document" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://hciweb.iwr.uni-heidelberg.de/Staff/fdiego/SliceMatching" target="_blank" rel="noopener">[Project]</a>
  </p>
  <div id="bib_evangelidis2011a" class="bibtex noshow">
  <pre>@inproceedings{evangelidis2011a,
  author    = {Evangelidis, Georgios D. and Diego, Ferran and Serrat, Joan and L\'opez, Antonio M.},
  title     = {Slice Matching for Accurate Spatio-Temporal Alignment},
  booktitle = {ICCV Workshop on Visual Surveillance},
  year      = {2011}
}
  </pre>
  </div>
</li>

<!-- Item: diego2010a -->
<li class="pub-item" data-year="2010">
  <p class="pub-authors"><b>F. Diego</b>, J. M. Álvarez, J. Serrat and A. M. López.</p>
  <p class="pub-title"><b>Vision-Based Road Detection via On-Line Video Registration</b><br>
  <i>IEEE Intelligent Transportation Systems Conference (ITSC)</i>, pp. 1135–1140, 2010.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2010a')">[BibTeX]</a>
    <a href="https://doi.org/10.1109/ITSC.2010.5624998" target="_blank" rel="noopener">[DOI]</a>
    <a href="https://hciweb.iwr.uni-heidelberg.de/Staff/fdiego/RoadSegmentation" target="_blank" rel="noopener">[Project]</a>
  </p>
  <div id="bib_diego2010a" class="bibtex noshow">
  <pre>@inproceedings{diego2010a,
  author    = {Diego, Ferran and Alvare\'iz, Jose M. and Serrat, Joan and L\'opez, Antonio M.},
  title     = {Vision-Based Road Detection via On-Line Video Registration},
  booktitle = {IEEE Intelligent Transportation Systems Conference (ITSC)},
  pages     = {1135--1140},
  year      = {2010},
  doi       = {10.1109/ITSC.2010.5624998}
}
  </pre>
  </div>
</li>

<!-- Item: diego2010b -->
<li class="pub-item" data-year="2010">
  <p class="pub-authors"><b>F. Diego</b>, D. Ponsa, J. Serrat and A. M. López.</p>
  <p class="pub-title"><b>Vehicle Geolocalization Based on Video Synchronization</b><br>
  <i>IEEE Intelligent Transportation Systems Conference (ITSC)</i>, pp. 1511–1516, 2010.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2010b')">[BibTeX]</a>
    <a href="https://doi.org/10.1109/ITSC.2010.5625055" target="_blank" rel="noopener">[DOI]</a>
    <a href="https://hciweb.iwr.uni-heidelberg.de/Staff/fdiego/VehicleGeolocalization" target="_blank" rel="noopener">[Project]</a>
    <a href="https://pdfs.semanticscholar.org/2b6b/8e1ce126c67deebd8992acae859044442ab0.pdf" target="_blank" rel="noopener">[Slides]</a>
  </p>
  <div id="bib_diego2010b" class="bibtex noshow">
  <pre>@inproceedings{diego2010b,
  author    = {Diego, Ferran and Ponsa, Daniel and Serrat, Joan and L\'opez, Antonio M.},
  title     = {Vehicle Geolocalization Based on Video Synchronization},
  booktitle = {IEEE Intelligent Transportation Systems Conference (ITSC)},
  pages     = {1511--1516},
  year      = {2010},
  doi       = {10.1109/ITSC.2010.5625055}
}
  </pre>
  </div>
</li>

<!-- Item: alvarez2009a -->
<li class="pub-item" data-year="2009">
  <p class="pub-authors">J. M. Álvarez, <b>F. Diego</b>, A. M. López, J. Serrat and D. Ponsa.</p>
  <p class="pub-title"><b>Automatic Ground-Truthing Using Video Registration for On-Board Detection Algorithms</b><br>
  <i>IEEE International Conference on Image Processing (ICIP)</i>, pp. 4389–4392, 2009.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('alvarez2009a')">[BibTeX]</a>
    <a href="https://doi.org/10.1109/ICIP.2009.5413620" target="_blank" rel="noopener">[DOI]</a>
  </p>
  <div id="bib_alvarez2009a" class="bibtex noshow">
  <pre>@inproceedings{alvarez2009a,
  author    = {Alvare\'iz, Jose M. and Diego, Ferran and L\'opez, Antonio M. and Serrat, Joan and Ponsa, Daniel},
  title     = {Automatic Ground-Truthing Using Video Registration for On-Board Detection Algorithms},
  booktitle = {IEEE International Conference on Image Processing (ICIP)},
  pages     = {4389--4392},
  year      = {2009},
  doi       = {10.1109/ICIP.2009.5413620}
}
  </pre>
  </div>
</li>

<!-- Item: diego2009a -->
<li class="pub-item" data-year="2009">
  <p class="pub-authors"><b>F. Diego</b>, D. Ponsa, J. Serrat and A. M. López.</p>
  <p class="pub-title"><b>Video Alignment for Automotive Applications</b><br>
  <i>One Day BMVA Symposium: Vision for Automotive Applications</i>, 2009.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2009a')">[BibTeX]</a>
  </p>
  <div id="bib_diego2009a" class="bibtex noshow">
  <pre>@inproceedings{diego2009a,
  author    = {Diego, Ferran and Ponsa, Daniel and Serrat, Joan and L\'opez, Antonio M.},
  title     = {Video Alignment for Automotive Applications},
  booktitle = {One Day BMVA Symposium: Vision for Automotive Applications},
  year      = {2009}
}
  </pre>
  </div>
</li>

<!-- Item: diego2008a -->
<li class="pub-item" data-year="2008">
  <p class="pub-authors"><b>F. Diego</b>, D. Ponsa, J. Serrat and A. M. López.</p>
  <p class="pub-title"><b>Video Alignment for Difference-Spotting</b><br>
  <i>ECCV Workshop on Multi-Camera and Multi-Modal Sensor Fusion Algorithms and Applications (ECCVW: M2SFA2)</i>, 2008.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2008a')">[BibTeX]</a>
  </p>
  <div id="bib_diego2008a" class="bibtex noshow">
  <pre>@inproceedings{diego2008a,
  author    = {Diego, Ferran and Ponsa, Daniel and Serrat, Joan and L\'opez, Antonio M.},
  title     = {Video Alignment for Difference-Spotting},
  booktitle = {ECCV Workshop on Multi-Camera and Multi-Modal Sensor Fusion Algorithms and Applications (ECCVW: M2SFA2)},
  year      = {2008}
}
  </pre>
  </div>
</li>

<!-- Item: serrat2007a -->
<li class="pub-item" data-year="2007">
  <p class="pub-authors">J. Serrat, <b>F. Diego</b>, F. Lumbreras and J. M. Álvarez.</p>
  <p class="pub-title"><b>Synchronization of Video Sequences from Free-Moving Cameras</b><br>
  <i>3rd Iberian Conference on Pattern Recognition and Image Analysis (IbPRIA)</i>, LNCS 4478, pp. 620–627, 2007.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('serrat2007a')">[BibTeX]</a>
    <a href="https://doi.org/10.1007/978-3-540-72849-8_78" target="_blank" rel="noopener">[DOI]</a>
  </p>
  <div id="bib_serrat2007a" class="bibtex noshow">
  <pre>@inproceedings{serrat2007a,
  author    = {Serrat, Joan and Diego, Ferran and Lumbreras, Felipe and Alvare\'iz, Jose M.},
  title     = {Synchronization of Video Sequences from Free-Moving Cameras},
  booktitle = {3rd Iberian Conference on Pattern Recognition and Image Analysis (IbPRIA)},
  series    = {Lecture Notes in Computer Science},
  volume    = {4478},
  pages     = {620--627},
  year      = {2007},
  doi       = {10.1007/978-3-540-72849-8_78}
}
  </pre>
  </div>
</li>

<!-- Item: serrat2007b -->
<li class="pub-item" data-year="2007">
  <p class="pub-authors">J. Serrat, <b>F. Diego</b>, F. Lumbreras and J. M. Álvarez.</p>
  <p class="pub-title"><b>Alignment of Videos Recorded from Moving Vehicles</b><br>
  <i>14th International Conference on Image Analysis and Processing (ICIAP)</i>, pp. 512–517, 2007.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('serrat2007b')">[BibTeX]</a>
    <a href="https://doi.org/10.1109/ICIAP.2007.4362829" target="_blank" rel="noopener">[DOI]</a>
  </p>
  <div id="bib_serrat2007b" class="bibtex noshow">
  <pre>@inproceedings{serrat2007b,
  author    = {Serrat, Joan and Diego, Ferran and Lumbreras, Felipe and Alvare\'iz, Jose M.},
  title     = {Alignment of Videos Recorded from Moving Vehicles},
  booktitle = {14th International Conference on Image Analysis and Processing (ICIAP)},
  pages     = {512--517},
  year      = {2007},
  doi       = {10.1109/ICIAP.2007.4362829}
}
  </pre>
  </div>
</li>

<!-- Item: duxans2006a -->
<li class="pub-item" data-year="2006">
  <p class="pub-authors">H. Duxans, D. Erro, J. Pérez, <b>F. Diego</b>, A. Bonafonte and A. Moreno.</p>
  <p class="pub-title"><b>Voice Conversion of Non-Aligned Data Using Unit Selection</b><br>
  <i>TC-STAR Workshop on Speech-to-Speech Translation</i>, 2006.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('duxans2006a')">[BibTeX]</a>
  </p>
  <div id="bib_duxans2006a" class="bibtex noshow">
  <pre>@inproceedings{duxans2006a,
  author    = {Duxans, H. and Erro, Daniel and P\'erez, J. and Diego, Ferran and Bonafonte, Antonio and Moreno, Asunci\'on},
  title     = {Voice Conversion of Non-Aligned Data Using Unit Selection},
  booktitle = {TC-STAR Workshop on Speech-to-Speech Translation},
  year      = {2006}
}
  </pre>
  </div>
</li>

</ul>

<h3 class="pub-section" data-type="preprints">Preprints and Technical Reports</h3>


<ul class="biblist">

<!-- Item: castellano2023a -->
<li class="pub-item" data-year="2023">
  <p class="pub-authors">G. Castellano, J.-J. Nieto, J. Luque, <b>F. Diego</b>, C. Segura, D. Perino, F. Esposito, F. Risso and A. Raman.</p>
  <p class="pub-title"><b>Scheduling Inference Workloads on Distributed Edge Clusters with Reinforcement Learning</b><br>
  <i>arXiv preprint arXiv:2301.13618</i>, 2023.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('castellano2023a')">[BibTeX]</a>
    <a href="https://arxiv.org/abs/2301.13618" target="_blank" rel="noopener">[arXiv]</a>
  </p>
  <div id="bib_castellano2023a" class="bibtex noshow">
  <pre>@misc{castellano2023a,
  author = {Castellano, Gabriele and Nieto, Juan-Jos\'e and Luque, Jordi and Diego, Ferran and Segura, Carlos and Perino, Diego and Esposito, Flavio and Risso, Fulvio and Raman, Aravindh},
  title  = {Scheduling Inference Workloads on Distributed Edge Clusters with Reinforcement Learning},
  howpublished = {arXiv:2301.13618},
  year   = {2023}
}
  </pre>
  </div>
</li>

<!-- Item: andersson2021a -->
<li class="pub-item" data-year="2021">
  <p class="pub-authors">A. Andersson, <b>F. Diego</b>, F. A. Hamprecht and C. Wählby.</p>
  <p class="pub-title"><b>ISTDECO: In Situ Transcriptomics Decoding by Deconvolution</b><br>
  <i>bioRxiv preprint</i>, 2021.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('andersson2021a')">[BibTeX]</a>
    <a href="https://doi.org/10.1101/2021.03.01.433040" target="_blank" rel="noopener">[PDF]</a>
    <a href="https://github.com/axanderssonuu/istdeco" target="_blank" rel="noopener">[Code]</a>
  </p>
  <div id="bib_andersson2021a" class="bibtex noshow">
  <pre>@misc{andersson2021a,
  author = {Andersson, Axel and Diego, Ferran and Hamprecht, Fred A. and W{\"a}hlby, Carolina},
  title  = {ISTDECO: In Situ Transcriptomics Decoding by Deconvolution},
  howpublished = {bioRxiv:2021.03.01.433040},
  year   = {2021},
  doi    = {10.1101/2021.03.01.433040}
}
  </pre>
  </div>
</li>

<!-- Item: alvarez2014a -->
<li class="pub-item" data-year="2014">
  <p class="pub-authors">J. M. Álvarez, <b>F. Diego</b>, J. Serrat and A. M. López.</p>
  <p class="pub-title"><b>Road Detection via On-Line Label Transfer</b><br>
  <i>arXiv preprint arXiv:1412.3159</i>, 2014.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('alvarez2014a')">[BibTeX]</a>
    <a href="https://arxiv.org/abs/1412.3159" target="_blank" rel="noopener">[arXiv]</a>
  </p>
  <div id="bib_alvarez2014a" class="bibtex noshow">
  <pre>@misc{alvarez2014a,
  author = {Alvare\'iz, Jose M. and Diego, Ferran and Serrat, Joan and L\'opez, Antonio M.},
  title  = {Road Detection via On-Line Label Transfer},
  howpublished = {arXiv:1412.3159},
  year   = {2014}
}
  </pre>
  </div>
</li>

</ul>

<h3 class="pub-section" data-type="books">Books</h3>


<ul class="biblist">

<!-- Item: diego2011book -->
<li class="pub-item" data-year="2011">
  <p class="pub-authors"><b>F. Diego</b>, D. Geronimo and J. Vazquez-Corral (Eds.)</p>
  <p class="pub-title"><b>State of the Art of Research and Development in Computer Vision</b><br>
  <i>Proceedings of the Sixth CVC Workshop. Computer Vision Center</i>, 2011.</p>
  <p class="pub-links">
    <a href="javascript:toggleBibtex('diego2011book')">[BibTeX]</a>
  </p>
  <div id="bib_diego2011book" class="bibtex noshow">
  <pre>@book{diego2011book,
  editor = {Diego, Ferran and Geronimo, D. and Vazquez-Corral, J.},
  title  = {State of the Art of Research and Development in Computer Vision},
  publisher = {Proceedings of the Sixth CVC Workshop. Computer Vision Center},
  year   = {2011}
}
  </pre>
  </div>
</li>

</ul>

<script type="text/javascript">
(function () {
  var search = document.getElementById('pubSearch');
  var yearSel = document.getElementById('pubYear');
  var chips = Array.prototype.slice.call(document.querySelectorAll('.pub-chip'));
  var sections = Array.prototype.slice.call(document.querySelectorAll('h3.pub-section'));
  var items = Array.prototype.slice.call(document.querySelectorAll('li.pub-item'));
  var count = document.getElementById('pubCount');
  var noMatch = document.getElementById('pubNoMatch');
  var total = items.length;
  var activeType = 'all';

  function inRange(y, range) {
    if (range === 'all') return true;
    var parts = range.split('-');
    var lo = parseInt(parts[0], 10);
    var hi = parts[1] ? parseInt(parts[1], 10) : 9999;
    return y >= lo && y <= hi;
  }

  function apply() {
    var q = search.value.trim().toLowerCase();
    var range = yearSel.value;
    var shown = 0;
    items.forEach(function (it) {
      var y = parseInt(it.getAttribute('data-year') || '0', 10);
      var ok = inRange(y, range) && (!q || it.textContent.toLowerCase().indexOf(q) !== -1);
      it.style.display = ok ? '' : 'none';
      if (ok) shown++;
    });
    sections.forEach(function (h3) {
      var t = h3.getAttribute('data-type');
      var typeOk = activeType === 'all' || t === activeType;
      var ul = h3.nextElementSibling;
      while (ul && ul.tagName !== 'UL') ul = ul.nextElementSibling;
      var hasVisible = Array.prototype.some.call(
        ul.querySelectorAll('li.pub-item'),
        function (it) { return it.style.display !== 'none'; }
      );
      var show = typeOk && hasVisible;
      h3.style.display = show ? '' : 'none';
      ul.style.display = show ? '' : 'none';
    });
    noMatch.hidden = shown !== 0;
    count.textContent = shown === total ? '' : shown + ' of ' + total + ' shown';
  }

  search.addEventListener('input', apply);
  yearSel.addEventListener('change', apply);
  chips.forEach(function (c) {
    c.addEventListener('click', function () {
      chips.forEach(function (x) { x.classList.remove('is-active'); });
      c.classList.add('is-active');
      activeType = c.getAttribute('data-type');
      apply();
    });
  });
})();
</script>
