---
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also browse my <u><a href="https://scholar.google.es/citations?user=aYO_0vgAAAAJ">Google Scholar profile</a>.</u>


{% include base_path %}


<style>
    /*********************************
     The list of publication items
     *********************************/
/* The list of items */
.biblist { }
/* The item */
.biblist li { }
/* You can define custom styles for plstyle field here. */


/*************************************
 The box that contain BibTeX code
 *************************************/
div.noshow { display: none; }
div.bibtex {
	margin-right: 0%;
	margin-top: 1.2em;
	margin-bottom: 1em;
	border: 1px solid silver;
	padding: 0em 1em;
	background: #ffffee;
}
div.bibtex pre { font-size: 75%; overflow: auto;  width: 100%; padding: 0em 0em;}</style>
<script type="text/javascript">
    // Toggle Display of BibTeX
    function toggleBibtex(articleid) {
        var bib = document.getElementById('bib_'+articleid);
        if (bib) {
            if(bib.className.indexOf('bibtex') != -1) {
                bib.className.indexOf('noshow') == -1?bib.className = 'bibtex noshow':bib.className = 'bibtex';
            }
        } else {
            return;
        }
    }
    </script>

<!--
<ul class="biblist">
<li ><p>
<a href="https://ch.linkedin.com/in/sergicaelles" target="_blank">S. Caelles</a>, <a href="http://www.vision.ee.ethz.ch/~kmaninis" target="_blank">K.K. Maninis</a>, J. Pont-Tuset, <a href="https://lealtaixe.github.io" target="_blank">L. Leal-Taixé</a>, 
<a href="http://vision.in.tum.de/members/cremers" target="_blank">D. Cremers</a>, and <a href="http://www.vision.ee.ethz.ch/members/get_member.cgi?id=1" target="_blank">L. Van Gool</a>
<br><b>Video Object Segmentation Without Temporal Information</b><br>
<i>IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</i>, 2018.
<br />
<a href="javascript:toggleBibtex('Maninis2018b')">[BibTeX]</a>
<a href="https://arxiv.org/pdf/1709.06031" target="_blank">[PDF]</a> <a href="http://www.vision.ee.ethz.ch/~cvlsegmentation/osvos-s/"  target="_blank">[Project Page]</a>
</p>
<div id="bib_Maninis2018b" class="bibtex noshow">
<pre>
@Article{Maninis2018b,
  author = {K.K. Maninis and S. Caelles and Y. Chen and J. Pont-Tuset and L. Leal-Taix\'e and D. Cremers and L. Van Gool},
  title = {Video Object Segmentation Without Temporal Information},
  journal = {IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)},
  year = {2018}
}
</pre>
</div>
</li>

</ul>
-->

<h3 style="margin-bottom:0px;padding-top:10px;">Top-Tier Journal Publications</h3>
{% for post in site.publications reversed %}
    {% if post.type==1 %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}

<h3 style="margin-bottom:0px;padding-top:10px;">Conferences</h3>

{% for post in site.publications reversed %}
    {% if post.type==2 %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}
