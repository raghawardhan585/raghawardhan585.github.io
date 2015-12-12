---
layout: post
site.title:  "Control of Machining Instability -Research Project-"
---
*<i>This is still an ongoing project. Please look back later for updates.</i>
<br>
<br>
<font size="5"><b>Guided By</b></font>
<p><a href="http://arunkt.wix.com/homepage">Prof. Arun K. Tangirala</a>, Department of Chemical Engineering, IIT Madras</p>
<p><a href="https://mech.iitm.ac.in/Faculty/nrb/home.php">Prof. N. Ramesh Babu</a>, Department of Mechanical Engineering, IIT Madras</p>
<br>
<font size="5"><b>Type of project</b></font>
<p>This is my final year Matsers Degree Project which I started in June,2015 and is expected to be completed by May,2016.</p>
<br>
<font size="5"><b>Span of Topics</b></font>
<p>Non Linear Systems Theory, Bifurcation, Empirical Mode Decomposition,
Wavelet Transform, Feedforward Contol and Identification</p>
<br>
<font size="5"><b>Abstract</b></font>
<p>The objective of the project is to implement a simultaneous time-frequency controller in a Cylindrical Grinding Machine to minimize the Machining Instability and to improve the precision of the Grinding Machine.</p>
<br>
<font size="3"><b>High Speed Low Immersion Milling Model</b></font>
<p>To simplify the objective, we start off with a milling process as it has a definite number of cutting edges with the defined cutting angle. This has a deterministic setting to it. When moving towards the Grinding process, the interaction between the tool and the workpiece becomes complex as the number of cutting edges interacting in a cycle is random and the angle of cut is also random. Hence it poses the challenge of stabilizing the process in the stochastic framework.

The high speed low immersion milling model is simulated in SIMULINK and the displacement data of the tool is acquired. The first objective is to determine that the system goes to instability and then the next objective is to implement the Wavelet Based Filtered-x Least Mean Square (WBFXLMS) Controller to this process to stabilize the process. </p>
<section role="banner">
<center><img src="/img/milling.png" width="1400" height="750" /></center>  
</section>
<font size="3"><b>Instability Analysis </b></font>
<p>The technique of coupled Empirical Mode Decomposition and Instantaneous Frequency has been applied to the displacement data of the tool acquired from the above high speed low immersion milling model for various cutting conditions. It can be clearly seen that the process tends towards instability in frequency domain. </p>
<section role="banner">
  <center><img src="/img/millcut.png" width="750" height="550" /></center>
</section>
<font size="3"><b>WBFXLMS Controller</b></font>
<p>This is the schematic of the controller. It is in the process of implementation. </p>
<section role="banner" align="center">
<center><img src="/img/wbfxlms.png" width="630" height="315" /></center>
</section>

<br>
<div align="right"><a href="/project.html">GO BACK</a></div>
<br>
*<i>This is still an ongoing project. Please look back later for updates.</i>
