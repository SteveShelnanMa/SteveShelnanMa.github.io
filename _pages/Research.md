---
layout: archive
title: ""
permalink: /Research/
author_profile: true
---

{% include base_path %}

## Working Paper

* [Labor Mobility, Earnings, and Network Structure](https://SteveShelnanMa.github.io/workingpaper/AKM.pdf), with someone. PDF  
  <div class="triangle-right" onclick="toggleAbstract(event)"></div>
  <div class="abstract-content" style="display:none;">
    <p>Here is the first abstract of the paper.</p>
  </div>

* __LEHD-NSCG__. _Job Market Paper_ [Draft]  
  Something else  
  <div class="triangle-right" onclick="toggleAbstract(event)"></div>
  <div class="abstract-content" style="display:none;">
    <p>Here is the abstract of the paper. This paper studies this and that using the data bla. I document that this and that and set a model to do this.</p>
  </div>

## Works in progress

<style>
.triangle-right, .triangle-down {
  cursor: pointer;
  display: inline-block;
  margin-right: 5px;
  vertical-align: middle;
}

.triangle-right {
  width: 0; 
  height: 0; 
  border-top: 5px solid transparent;
  border-bottom: 5px solid transparent; 
  border-left: 10px solid black; /* Adjust color */
}

.triangle-down {
  width: 0; 
  height: 0; 
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;  
  border-top: 10px solid black; /* Adjust color */
}

.abstract-content {
  display: none;
  margin-top: 5px;
  /* Add any additional styling here */
}
</style>

<script>
document.addEventListener('DOMContentLoaded', (event) => {
  window.toggleAbstract = function(event) {
    event.preventDefault();
    var triangle = event.target;
    var content = triangle.nextElementSibling;
    if (content.style.display === "none" || content.style.display === "") {
      content.style.display = "block";
      triangle.className = "triangle-down";
    } else {
      content.style.display = "none";
      triangle.className = "triangle-right";
    }
  }
});
</script>
