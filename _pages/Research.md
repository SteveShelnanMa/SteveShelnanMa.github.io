---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---

{% include base_path %}

## Working Paper

* __Earnings Dynamics, Transitions, and Stepping-stone Employers__. _(Job Market Paper)_. [[Draft]](https://SteveShelnanMa.github.io/workingpaper/JMP_Jan27.pdf)\
  _Under Census Bureau Project #2799_ \
[[Short Abstract]] I study the prevalence and drivers of earnings cuts upon transitions (ECUTs).  Using linked administrative-survey data from U.S. census, I identify motivations for transitions and quantify ECUTs across them. I find many movers solely moitivated by pecuniary reason still experience ECUTs. Moreover, workers who transition for pecuniary reasons have higher future earnings growth and higher probability of subsequent transitions. I propose that certain employers act as “stepping-stones,” providing pathways to better job opportunities.  I develop a random search model where employers differ in the quantity and quality of offer arrival rates, highlighting the role of stepping-stone employers in ECUTs and labor dynamics.

<!--
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Short Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
     <p style="text-align: justify;"> I study the prevalence and drivers of earnings cuts upon transitions (ECUTs).  Using linked administrative-survey data from U.S. census, I identify motivations for transitions and quantify ECUTs across them. I find many movers solely moitivated by pecuniary reason still experience ECUTs. Moreover, workers who transition for pecuniary reasons have higher future earnings growth and higher probability of subsequent transitions. I propose that certain employers act as “stepping-stones,” providing pathways to better job opportunities.  I develop a random search model where employers differ in the quantity and quality of offer arrival rates, highlighting the role of stepping-stone employers in ECUTs and labor dynamics.            </p>
  </div>
-->

* __A Simple Search Model with Employer Network__. [[Draft]](https://SteveShelnanMa.github.io/workingpaper/LMENS.pdf)[[Slides]](https://SteveShelnanMa.github.io/workingpaper/simplemodel.pdf)\
  _Conibear Memorial Prize for the Best Third Year Paper, University of Rochester,_\
[Short Abstract] I examine how employer network structures influence labor market outcomes with a simple search model. Employers are represented as network nodes, with edges reflecting higher job offer arrival rates. We establish the existence and uniqueness of a ‘node value,’ the expected lifetime value of using an employer's network for job search. This node value share similar properties with option asset and network centrality. Through node values, employer network structures impact employment, labor mobility, and wage distributions.

<!--
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Short Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
    <p style="text-align: justify;"> I examine how employer network structures influence labor market outcomes with a simple search model. Employers are represented as network nodes, with edges reflecting higher job offer arrival rates. We establish the existence and uniqueness of a ‘node value,’ the expected lifetime value of using an employer's network for job search. This node value share similar properties with option asset and network centrality. Through node values, employer network structures impact employment, labor mobility, and wage distributions.</p>
  </div>
-->

* __Human Capital, Job Ladders, and Life-Cycle Labor Supply__, with [Paulo Lins](https://pauloclins.com) [Draft available on request]\
[Abstract] We document new facts about the behavior of total annual hours over the life cycle using NLSY79 data and show that current life-cycle models fail to explain these patterns. In the data, both the intensive and extensive margins of labor supply are equally important, each contributing 50% to the life-cycle growth in total annual hours. We propose a life-cycle model that nests different theories used to explain the hours’ profile and calibrate it to reproduce our empirical evidence. Both human capital accumulation and a job ladder are needed to account for the data patterns, while versions with only one ingredient fail to explain labor supply over the life cycle. Through counterfactual exercises, we find that human capital accumulation is the primary driver of wage growth in the early stages of a worker’s career, while job search significantly contributes to hours growth.

<!--
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
     <p style="text-align: justify;"> We document new facts about the behavior of total annual hours over the life cycle using NLSY79 data and show that current life-cycle models fail to explain these patterns. In the data, both the intensive and extensive margins of labor supply are equally important, each contributing 50% to the life-cycle growth in total annual hours. We propose a life-cycle model that nests different theories used to explain the hours’ profile and calibrate it to reproduce our empirical evidence. Both human capital accumulation and a job ladder are needed to account for the data patterns, while versions with only one ingredient fail to explain labor supply over the life cycle. Through counterfactual exercises, we find that human capital accumulation is the primary driver of wage growth in the early stages of a worker’s career, while job search significantly contributes to hours growth.  </p>
  </div>
-->

  
## Selected Works in Progress
* __Anatomy of Motivations for Transitions__ \
_Under Census Bureau Project #2799_ \
[Abstract] This project leverages the administrative and survey datasets from the U.S. Census Bureau to investigate the motivations behind job transitions and their connections to earnings dynamics and worker characteristics. I begin by benchmarking the NSCG against other public survey datasets, emphasizing its superior ability to capture transition motivations. In contrast to my job market paper, which centers on pecuniary motives, this analysis delves into non-pecuniary motivations and examines how these relate to various worker attributes. Finally, I analyze how reported motivations for transitions vary across the worker’s life cycle.

<!--
  <div class="toggle-abstract" onclick="toggleAbstract(event)">
    <div class="triangle-right"></div><span class="abstract-text">Abstract</span>
  </div>
  <div class="abstract-content" style="display:none;">
     <p style="text-align: justify;">This project leverages the administrative and survey datasets from the U.S. Census Bureau to investigate the motivations behind job transitions and their connections to earnings dynamics and worker characteristics. I begin by benchmarking the NSCG against other public survey datasets, emphasizing its superior ability to capture transition motivations. In contrast to my job market paper, which centers on pecuniary motives, this analysis delves into non-pecuniary motivations and examines how these relate to various worker attributes. Finally, I analyze how reported motivations for transitions vary across the worker’s life cycle. </p>
  </div>
-->

* __On the Dynamics of Hours and Wage Distributions__



  
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
