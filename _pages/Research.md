---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---

{% include base_path %}

## Working Paper

* __Earnings Dynamics, Transitions, and Stepping-stone Employers__. _(Job Market Paper)_. [[Draft comming soon]](https://SteveShelnanMa.github.io/workingpaper/.pdf).\
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p>Full abstract coming soon...</p>
  </div>

* __A Simple Search Model with Employer Network__. [[Draft on request]](https://SteveShelnanMa.github.io/workingpaper/.pdf)\
  _Conibear Memorial Prize for the Best Third Year Paper, University of Rochester,_\
  _Accepted for presentation at the Search and Matching Workshop in the Asia-Pacific 2024_
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p style="text-align: justify;">
This article studies the role of employer network structures in shaping labor market outcomes through a simple search model. In this model, employers are depicted as nodes within a network, linked by edges that signify higher arrival rates of job offers. We proved the existence and uniqueness of what we term the ‘node value’ — the expected lifetime value derived from leveraging an employer’s network connections for job search. We establish that the node value is essentially an option asset in that its value escalates with the first order stochastic dominance of the wage distribution and its mean-preserving spreads in risk. Moreover, node value exhibits similarity to network centrality measures as it depends on employer’s position within the network. Specifically, it is positively related to the number of connections an employer maintains and the node values of other employers, especially the connected ones. Consequently, employers situated in more central positions within the network are deemed more desirable, offering better working prospects to workers. The node value thus serves as a crucial mechanism by which the employer network structure endogenously determines employment, labor mobility, and wage distributions. Furthermore, the model offers explanatory power for phenomena such as worker mobility towards lower-wage jobs. Our analysis highlights the critical role of network topology in driving employment decisions and molding labor market outcomes.
</p>
  </div>
  


## Selected Works in Progress (Updating soon)
* __Anatomy of Drivers of Transitions__. 
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p>This paper focuses on the drivers of transitions in U.S. labor market. </p>
  </div>
  
<!--
# *  __Wages and Hours Over the Life-Cycle__, _with [Paulo Lins](https://pauloclins.com)_

* __Misallocation and SOE Reform in Labor Market__
-->

  
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

/*abstract-content {
  display: none;
  margin-top: 2px; 
  /* This decreases the space between the toggle and the content */
/*}*/
div.abstract-content {
  margin-top: 2px;
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
