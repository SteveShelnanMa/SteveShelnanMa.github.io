---
layout: archive
title: ""
permalink: /Research/
author_profile: true
---

{% include base_path %}

## Working Paper

* [Labor Mobility, Earnings, and Network Structure](https://SteveShelnanMa.github.io/workingpaper/AKM.pdf), with someone. PDF  
  <button class="abstract-button" onclick="toggleAbstract(event)">Abstract</button>
  <div class="abstract-content" style="display:none;">
    <p>
      Here is the first abstract of the paper.
    </p>
  </div>

* __LEHD-NSCG__. _Job Market Paper_ [Draft]  
  Something else  
  <button class="abstract-button" onclick="toggleAbstract(event)">Abstract</button>
  <div class="abstract-content" style="display:none;">
    <p>
      Here is the abstract of the paper. This paper studies this and that using the data bla. I document that this and that and set a model to do this.
    </p>
  </div>

## Works in progress

<script>
document.addEventListener('DOMContentLoaded', (event) => {
  window.toggleAbstract = function(event) {
    event.preventDefault();
    var content = event.target.nextElementSibling;
    if (content.style.display === "none" || content.style.display === "") {
      content.style.display = "block";
    } else {
      content.style.display = "none";
    }
  }
});
</script>
