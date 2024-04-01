---
layout: archive
title: ""
permalink: /Research/
author_profile: true
---

{% include base_path %}

## Working Paper

* __Labor Mobility, Earnings, and Network Structure__, with someone, [[PDF]](https://SteveShelnanMa.github.io/workingpaper/AKM.pdf).   
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p>Here is the first abstract of the paper.</p>
  </div>

* __LEHD-NSCG__. _Job Market Paper_ [Draft]  
  Something else  
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p>Here is the abstract of the paper. This paper studies this and that using the data bla. I document that this and that and set a model to do this.</p>
  </div>

## Works in progress
* __The Trend of Steppingstone Firms in US.__. _Job Market Paper_ [Draft]  
  Something else  
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p>Here is the abstract of this paper.</p>
  </div>

  
<style>
.toggle-abstract {
  cursor: pointer;
  display: flex;
  align-items: center;
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

.abstract-text {
  color: grey;
  margin-left: 5px;
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
    var toggleContainer = event.target.closest('.toggle-abstract');
    var content = toggleContainer.nextElementSibling;
    var triangle = toggleContainer.querySelector('.triangle-right, .triangle-down');
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
