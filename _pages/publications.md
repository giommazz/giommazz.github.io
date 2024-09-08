---
layout: archive
title: Publications
permalink: /publications/
author_profile: true
---



## International Journals

- **Cycle-based Formulations in Distance Geometry**  
  **L. Liberti, G. Iommazzo, C. Lavor, N. Maculan (2023)**  
  *Open Journal of Mathematical Optimization*, Volume 4, article no. 1, 16 p.  
  [PDF](https://doi.org/10.5802/ojmo.18) | [ArXiv](https://arxiv.org/abs/2006.11523) | 
  <button onclick="toggleBibtex('bibtex-lil23')" style="background:none; border:none; color:blue; cursor:pointer;">[BibTeX]</button> | 
  <button id="copy-btn-lil23" onclick="copyBibtex('bibtex-lil23', 'copy-btn-lil23')" style="background:none; border:none; color:blue; cursor:pointer;">&#128203; copy</button>
  
  <div id="bibtex-lil23" style="display:none; padding: 10px; border: 1px solid #ddd; margin-top: 10px; font-family: monospace; max-height: 100px; overflow: auto;">
    <pre>
@article{OJMO_2023__4__A1_0,
     author = {Leo Liberti and Gabriele Iommazzo and Carlile Lavor and Nelson Maculan},
     title = {Cycle-based formulations in {Distance} {Geometry}},
     journal = {Open Journal of Mathematical Optimization},
     eid = {1},
     pages = {1--16},
     publisher = {Universit\'e de Montpellier},
     volume = {4},
     year = {2023},
     doi = {10.5802/ojmo.18},
     language = {en},
     url = {https://ojmo.centre-mersenne.org/articles/10.5802/ojmo.18/}
    }
    </pre>
  </div>

<script>
function toggleBibtex(id) {
  var x = document.getElementById(id);
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}

function copyBibtex(bibtexId, buttonId) {
  var bibtexText = document.getElementById(bibtexId).getElementsByTagName('pre')[0].innerText;
  navigator.clipboard.writeText(bibtexText).then(function() {
    // Change the button text to "copied!"
    var copyButton = document.getElementById(buttonId);
    copyButton.innerHTML = 'copied!';
  }).catch(function() {
    alert('Failed to copy BibTeX');
  });
}
</script>
