---
layout: page
title: Research and Projects
excerpt: "Research and Project details."
---


#### Face Recognition using Deep Neural Nets
<img src="/images/fp.png" width="171" height="57" align="right">
<font size="2">
I am developing a Deep Belief Network based viewpoint and illumination invariant Face Recognition architecture (along with GUI) for F&P Robotics AG. They are located in Zurich and are a wonderful team to work with. 
I got to visit them in 2014 for a month and also represented them at InnoRobo-2014, Lyon and ICRA-2014, HongKong. I developed a great interest in Deep Neural Nets since I have been working on this project.
</font>

<hr>

#### Markov Random Field based small object discovery over images
<img src="/images/small_object.png" width="246" height="82" align="right">
 <font size="2">
 This project involved discovery and extraction of small objects(height 3-8cm) lying scatterd on indoor floors to label the navigable area. An estimate of the ground plane homography and the cumulative residual(homography error) of the superpixels in an image was evaluated. This in turn is formulated into a Markov Random Field to label the image pixels as objects and floor. This work
 was published at the ICRA '14, Hong Kong. <em><a href="/docs/Suryansh_etal_ICRA_14.pdf">View ICRA-14 Paper</a></em>. <em><a href="https://www.youtube.com/watch?v=WPZQbYSef78">View ICRA-14 Video</a></em> 
 </font>

<hr>

#### Guess from far, Recognize when near: Searching indoor floors for small objects
<img src="/images/icra_img.png" width="275" height="100" align="right">

<p> <font size="2">When the environment is a large room and the objects are scattered at far away locations, it would be expensive to visit each object and check if it is the required one. Also the small size of the objects makes the viewpoint an important aspect for accurate classification through its 3-D point cloud. In such cases, by making a probabilistic guess about existence of a search object from far away we can substantially reduce the search space for the robot. In addition a polar data structure, Viewpoint Object Potential(VOP) is introduced that characterizes the discriminative viewpoints to recognize an object using 3-D data. In case an object seems to be similar to multiple objects, their VOPs can be linearly combined to form a Composite VOP to finnd a unique viewpoint to clearly distinguish the object. This information was integrated into a probabilistic Decision Analysis Graph to decide a set of strategicwaypoints for the robot to follow to efficiently recover objects through earning a maximal reward. This work was published at the ICPR-14, Sweden and ICVGIP-14, India. </font> </p>

<p> <font size="2"><em><a href="/docs/Sudhanshu_etal_ICPR_14.pdf">View ICPR-14 Paper</a></em>. <em><a href="/docs/Siva_etal_ICVGIP_14.pdf">View ICVGIP-14 Paper
</a></em>. <em><a href="https://www.youtube.com/watch?v=4ZpH4LM7EO0">View ICVGIP-14 Video</a></em> </font></p>


<hr>

#### Fetal Heart Sound Monitor(FHSM) data classification using Spiking Neural Nets(SNNs)
<img src="/images/siemens.png" width="180" height="60" align="right">
<font size="2">
	This project was done as a part of an internship at Siemens Research India. I analysed FHSM data for preliminary noise modelling and removal for extraction of a signal with high SNR. Further, I analysed it for various discriminative frequency characteristics among classes. The FHSM data was classified using SNNs by transforming it to a higher dimensional temporal space using Receptive Field Encoding. Additionally I built a human spoken digit classifier using SNNs.
</font>

<hr>

#### Scalable long range AUV position estimation and RF communication platform
<img src="/images/nus.jpg" width="171" height="57" align="right">
<font size="2">
Integrated an RF communication framework into AUV software platform to broadcast AUV
position to deployment boats and ground stations. Estimated the position of AUVs in case of communication failure using Kalman Filter and already existing data like current flow, speed etc. Visualized all of this on Maps API on tablet devices.
</font>

<hr>


<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-59912294-1', 'auto');
  ga('send', 'pageview');

</script>
