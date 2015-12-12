---
layout: post
title:  "Weight Loss Control System -Research Project-"
---


<br>
<br>
<font size="5"><b>Guided By</b></font>
<p><a href="http://engineering.unl.edu/mme/benjamin-terry/">Prof. Benjamin Terry</a>, Department of Mechanical Engineering, University of Nebraska, Lincoln, USA</p>
<br>

<font size="5"><b>Type of project</b></font>
<p>During the summer of my 3rd year, Prof. Benjamin Terry had offered me an internship in his lab for a period of two months to work on his ongoing project.</p>
<br>

<br>
<font size="5"><b>Span of Topics</b></font>
<p>State Space Systems Theory, System Identification and Control </p>
<br>

<br>
<font size="5"><b>Abstract</b></font>
<p>The objective of the project is to dvelop a Control System for aiding in weight reduction based on a sensor which measures the mass flow rate in the small intestine. The sub-ojective is to develop a model a model between the food intake and the weight change of the body to design the necessary controller.  
<br>


<font size="3"><b>Proposed Control Framework</b></font>
<section role="banner" align="center">
<center><img src="/img/wls.png" width="630" height="315" /></center>
In this framework, the first controller takes care to attain the overall objectives by taking in the initial condition of the person and various inputs like the desired weight and the desired time to attain that weight and calculates the maximum calorie consumption to achieve that goal. The second controller has a measurement of the mass flow rate in the small intestine from which the calorie intake is estimated and it suggests to the user, the amount of food he can consume for the meal. To start off, the primary objective is to identify the system dynamics. 
</section>

<font size="3"><b>Model Identification</b></font>
<section role="banner" align="center">
<center><img src="/img/wls.png" width="630" height="315" /></center>
To model the dynamics of the system, the data of food intake and weight of the body has been collected for a period of one month and system identification techniques have been implemented to identify the linear time invariant models. But they are highly insufficient to capture the dynamics of the process.

<iframe src="/wls.pdf" 
style="width:600px; height:500px;" frameborder="2"></iframe>
</section>

<br>
<div align="right"><a href="/project.html">GO BACK</a></div>
<br>




