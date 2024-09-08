---
layout: archive
title: Publications
permalink: /publications/
author_profile: true
---



## International Journals

- Cycle-based Formulations in Distance Geometry  
  L. Liberti, G. Iommazzo, C. Lavor, N. Maculan  
  *Open Journal of Mathematical Optimization*, Volume 4, article no. 1, 16 p. (2023)  
  [[DOI]](https://doi.org/10.5802/ojmo.18){:target="_blank"} | [[ArXiv]](https://arxiv.org/abs/2006.11523){:target="_blank"} | 
  <a href="javascript:void(0)" onclick="toggleBibtex('bibtex-lil23', 'copy-btn-lil23')" style="text-decoration: none; color: #228B22;">[BibTeX]</a> 
  <button id="copy-btn-lil23" onclick="copyBibtex('bibtex-lil23', 'copy-btn-lil23')" style="display:none; background:none; border:none; color: #228B22; cursor:pointer;">&#128203; copy</button>
  
  <div id="bibtex-lil23" style="display:none; padding: 10px; border: 1px solid #ddd; margin-top: 10px; font-family: monospace; font-size: 12px; background-color: #d3d3d3; color: black; max-width: 600px; max-height: 150px; overflow: auto;">
    <pre>
@article{LIL+23,
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
function toggleBibtex(bibtexId, buttonId) {
  var bibtexBox = document.getElementById(bibtexId);
  var copyButton = document.getElementById(buttonId);

  if (bibtexBox.style.display === "none") {
    bibtexBox.style.display = "block";
    copyButton.style.display = "inline";  // Show the copy button when BibTeX is visible
  } else {
    bibtexBox.style.display = "none";
    copyButton.style.display = "none";  // Hide the copy button when BibTeX is hidden
  }
}

function copyBibtex(bibtexId, buttonId) {
  var bibtexText = document.getElementById(bibtexId).getElementsByTagName('pre')[0].innerText;
  navigator.clipboard.writeText(bibtexText).then(function() {
    // Change the button text to "copied!" but keep the icon
    var copyButton = document.getElementById(buttonId);
    copyButton.innerHTML = '&#128203; copied!';
  }).catch(function() {
    alert('Failed to copy BibTeX');
  });
}
</script>
