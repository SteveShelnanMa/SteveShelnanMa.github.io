---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---

{% include base_path %}

## Working Paper

* __Earnings Dynamics, Transitions, and Stepping-stone Employers__. _(Job Market Paper)_. [[Draft coming soon]](https://SteveShelnanMa.github.io/workingpaper/.pdf).
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p> Earnings cuts upon transitions (ECUTs) are a well-documented phenomenon, prompting the need for both empirical validation and theoretical explanations. This article revisits this feature in U.S. labor market with the data from the Longitudinal Employer-Household Dynamics (LEHD) and the National Survey of College Graduates (NSCG). I confirm that ECUTs are frequent, even after adjusting for potential measurement error related to location changes and the timing of transitions. Furthermore, by linking the LEHD to the NSCG, I identify the workers' reported reasons for transitions, and quantify the share of ECUTs associated with each motivation. While non-pecuniary motivations are important, the pecuniary reasons are the most commonly chosen. Notably, many workers who report pecuniary reasons as their sole motivation for transitioning also experience ECUTs. Building on these findings, I explore the relationship between pecuniary motivation, future earnings trajectories, and the likelihood of subsequent transitions.  The results indicate that (1) workers who transition for pecuniary reasons experience higher earnings growth in future periods, and (2) these workers are more likely to undergo subsequent transitions.   I argue that certain employers serve as ``stepping-stones" by improving workers' opportunities to transition to more desirable firms. Pursuing such stepping-stone employers thus is an important pecuniary motivation for job transitions and partially explains the incidence of ECUTs.  This interpretation is supported by firm-level heterogeneity in transition rates observed in the LEHD data. To formalize this mechanism, I develop a sequential auction model where firms are characterized by heterogenous offer arrival rates in quantity as well as quality. Both the empirical analysis and theoretical framework underscore the critical role of stepping-stone employers in shaping ECUTs and broader labor market dynamics.           </p>
  </div>

* __A Simple Search Model with Employer Network__. [Draft on request] [[Slides]](https://SteveShelnanMa.github.io/workingpaper/simplemodel.pdf)\
  _Conibear Memorial Prize for the Best Third Year Paper, University of Rochester,_\
  _Presented at the Search and Matching Workshop in the Asia-Pacific 2024_
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p style="text-align: justify;">This article studies the role of employer network structures in shaping labor market outcomes through a simple search model. In this model, employers are depicted as nodes within a network, linked by edges that signify higher arrival rates of job offers. We proved the existence and uniqueness of what we term the ‘node value’ — the expected lifetime value derived from leveraging an employer’s network connections for job search. We establish that the node value is essentially an option asset in that its value escalates with the first order stochastic dominance of the wage distribution and its mean-preserving spreads in risk. Moreover, node value exhibits similarity to network centrality measures as it depends on employer’s position within the network. Specifically, it is positively related to the number of connections an employer maintains and the node values of other employers, especially the connected ones. Consequently, employers situated in more central positions within the network are deemed more desirable, offering better working prospects to workers. The node value thus serves as a crucial mechanism by which the employer network structure endogenously determines employment, labor mobility, and wage distributions. Furthermore, the model offers explanatory power for phenomena such as worker mobility towards lower-wage jobs. Our analysis highlights the critical role of network topology in driving employment decisions and molding labor market outcomes.</p>
  </div>


* __Human Capital, Career Choice, and the Hours Profile Over the Life-Cycle__, with [Paulo Lins](https://pauloclins.com) 

## Selected Works in Progress
* __Anatomy of Motivations for Transitions__
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p>This paper focuses on the motivations of transitions in U.S. labor market. </p>
  </div>




<!--
# *  __Wages and Hours Over the Life-Cycle__, _with [Paulo Lins](https://pauloclins.com)_
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
