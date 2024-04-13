---
layout: archive
title: ""
permalink: /Research/
author_profile: true
---

{% include base_path %}

## Working Paper

* __Something, Something, and Some Something__. _Job Market Paper_ [[Draft]](https://SteveShelnanMa.github.io/workingpaper/AKM.pdf).   
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p>Here is the first abstract of the paper.</p>
  </div>

* __A Simple Search Model with Employer Network__, [Draft]  
  Something else  
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p>Here is the abstract of the paper 2. This paper studies this and that using the data bla. I document that this and that and set a model to do this.</p>
  </div>
  
* __Distortion in Something and Some Reform__, with someone [Draft]  
  Something else  
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p>Here is the abstract of the paper 3. This paper studies this and that using the data bla. I document that this and that and set a model to do this.</p>
  </div>

## Selected Works in Progress
* __LFN in U.S.__. 
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
  margin-top: 2px; 
  /* This decreases the space between the toggle and the content */
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
