---
layout: post
title:  "Modern Control Theory *Course Project*"
date:   2014-12-01 02:51:19 +0530
---


<br>
<div align="right"><a href="/project.html">GO BACK</a></div>
<br>
<font size="5"><b>Guided By</b></font>
<p><a href="http://arunkt.wix.com/homepage">Prof. Raghunathan Rengasamy</a>, Department of Chemical Engineering, IIT Madras</p>

<br>
<font size="5"><b>Span of Topics</b></font>
<p>State Space Systems Theory, System Identification, Kalman Filter, Model Predictive Control and Optimization</p>
<br>

<font size="5"><b>PROJECT 1- State Estimation of an Inverted Pendulum</b></font>
<section role="banner">
<center><img src="/img/invertedpendulum.png" />
<h4>Inverted Pendulum Process</h4></center>
</section>
<br>
<font size="3"><b>Abstract</b></font>
<p>The objective of the project is to implement some of the variants of Kalman Filter like Extended Kalman Filter. Ensemble Kalman Filter and Particle Filter to the simulated Inverted Pendulum Process in MATLAB to estimate the four states of the system with measurements of position and orientation of the pendulum.</p>
<p>
<b>Process Input</b>
<br>- Force Applied 
<br><b>Process States</b>
<br>- Position of the pendulum 
<br>- Linear Velocity of the cart 
<br>- Orientation(Angle) of the pendulum with respect to vertical
<br>- Angular Velocity of the pendulum 
<br><b>Process Outputs</b>
<br>- Position of the pendulum 
<br>- Orientation(Angle) of the pendulum with respect to vertical
</p>

<br>
<section role="banner" align="center">
<iframe src="/kalmanfilter.pdf" 
style="width:600px; height:500px;" frameborder="2"></iframe>
</section>


<br>
<font size="5"><b>PROJECT 2- Model Predictive Control of a Fluidized Catalyst Crackling Process</b></font>
<section role="banner">
<center><img src="/img/FCC.jpg" />
<h4>Fluid Catalytic Crackling Process</h4></center>
</section>
<br>
<font size="3"><b>Abstract</b></font>
<p align ="justify">The objective of the project is to implement the Model Predictive Contol Scheme to a Fluidized Catalytic Converter Process.</p>
<p>
<b>Process Inputs</b>
<br>- mass flow rate of air to the generator 
<br>- mass flow rate of regenerated catalyst 
<br><b>Process Outputs</b>
<br>- Oxygen mole fraction in regenerator dense bed 
<br>- Weight-fraction of coke deposited on catalyst
<br>- Temperature of Catalyst in Regenerator dense bed</p>
<p align="justify">The process is simulated with various inputs like IRS, Sinusoidal and RBS upto a certain time. The input-output data that has been accumulated is used to identify the state space model of the system. Now we select two of the three outputs we want to control and then for various values of the predciction horizon and the control horizon, we implement the MPC and find the optimal input such that the ouputs follow the desired response closely.</p>
<br>
<section role="banner" align="center">
<iframe src="/MPC.pdf" 
style="width:600px; height:500px;" frameborder="2"></iframe>
</section>
<div align="right"><a href="/project.html">GO BACK</a></div>
<br>




