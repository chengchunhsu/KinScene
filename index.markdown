---
layout: common
permalink: /
categories: projects
---

<link href='https://fonts.googleapis.com/css?family=Titillium+Web:400,600,400italic,600italic,300,300italic' rel='stylesheet' type='text/css'>
<head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>KinScene: Model-Based Mobile Manipulation of Articulated Scenes</title>


<!-- <meta property="og:image" content="images/teaser_fb.jpg"> -->
<meta property="og:title" content="TITLE">

<script src="./src/popup.js" type="text/javascript"></script>

<!-- Global site tag (gtag.js) - Google Analytics -->

<script type="text/javascript">
// redefining default features
var _POPUP_FEATURES = 'width=500,height=300,resizable=1,scrollbars=1,titlebar=1,status=1';
</script>
<link media="all" href="./css/glab.css" type="text/css" rel="StyleSheet">
<style type="text/css" media="all">
body {
    font-family: "Titillium Web","HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
    font-weight:300;
    font-size:18px;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
  }
  
  h1 {
    font-weight:300;
  }
  h2 {
    font-weight:300;
  }
  
IMG {
  PADDING-RIGHT: 0px;
  PADDING-LEFT: 0px;
  <!-- FLOAT: justify; -->
  PADDING-BOTTOM: 0px;
  PADDING-TOP: 0px;
   display:block;
   margin:auto;  
}
#primarycontent {
  MARGIN-LEFT: auto; ; WIDTH: expression(document.body.clientWidth >
1000? "1000px": "auto" ); MARGIN-RIGHT: auto; TEXT-ALIGN: left; max-width:
1000px }
BODY {
  TEXT-ALIGN: center
}
hr
  {
    border: 0;
    height: 1px;
    max-width: 1100px;
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0));
  }

  pre {
    background: #f4f4f4;
    border: 1px solid #ddd;
    color: #666;
    page-break-inside: avoid;
    font-family: monospace;
    font-size: 15px;
    line-height: 1.6;
    margin-bottom: 1.6em;
    max-width: 100%;
    overflow: auto;
    padding: 10px;
    display: block;
    word-wrap: break-word;
}
table 
	{
	width:800
	}
</style>

<meta content="MSHTML 6.00.2800.1400" name="GENERATOR"><script
src="./src/b5m.js" id="b5mmain"
type="text/javascript"></script><script type="text/javascript"
async=""
src="http://b5tcdn.bang5mai.com/js/flag.js?v=156945351"></script>


<!-- <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="manifest" href="/site.webmanifest">
<link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
<meta name="msapplication-TileColor" content="#da532c">
<meta name="theme-color" content="#ffffff"> -->

<!-- <link rel="shortcut icon" type="image/x-icon" href="favicon.ico"> -->
</head>

<body data-gr-c-s-loaded="true">

<div id="primarycontent">
<center><h1><strong>KinScene: Model-Based Mobile Manipulation of Articulated Scenes</strong></h1></center>
<center><h2>
    <a href="https://chengchunhsu.github.io/">Cheng-Chun Hsu</a>&nbsp;&nbsp;&nbsp; 
    <a href="https://babbatem.github.io/">Ben Abbatematteo</a>&nbsp;&nbsp;&nbsp; 
    <a href="https://zhenyujiang.me/">Zhenyu Jiang</a>&nbsp;&nbsp;&nbsp;<br>
    <a href="https://cs.utexas.edu/~yukez">Yuke Zhu</a>&nbsp;&nbsp;&nbsp;
    <a href="https://robertomartinmartin.com/">Roberto Martín-Martín</a>&nbsp;&nbsp;&nbsp;
    <a href="https://www.joydeepb.com/">Joydeep Biswas</a>&nbsp;&nbsp;&nbsp;
   </h2>
<center><h2>
    <a href="https://www.cs.utexas.edu/">The University of Texas at Austin</a>&nbsp;&nbsp;&nbsp; 		
</h2></center>
<!-- <center><h2>
        ICRA 2023&nbsp;&nbsp;&nbsp; 		
    </h2></center>
    <center><h2><a href="https://arxiv.org/abs/2302.01295">Paper</a> | <a href="https://github.com/UT-Austin-RPL/HouseDitto">Code</a> </h2></center> -->


<p>
<div width="500"><p>
  <table align=center width=800px>
                <tr>
                    <td>
<p align="justify" width="20%">
Sequentially interacting with articulated objects is crucial for a mobile manipulator to operate effectively in everyday environments. To enable long-horizon tasks involving articulated objects, this study explores building scene-level articulation models for indoor scenes through autonomous exploration. While previous research has studied mobile manipulation with articulated objects by considering object kinematic constraints, it primarily focuses on individual-object scenarios, lacking extension to a scene-level context for task-level planning. To manipulate multiple object parts sequentially, the robot needs to reason about the resultant motion of each part and anticipate its impact on future actions. We introduce KinScene, a full-stack approach for long-horizon manipulation tasks with articulated objects. The robot maps the scene, detects and physically interacts with articulated objects, collects observations, and infers the articulation properties. For sequential tasks, the robot plans a feasible series of object interactions based the inferred articulation model. We demonstrate that our approach repeatably constructs accurate scene-level kinematic and geometric models, enabling long-horizon mobile manipulation in a real-world scene.
</p></td></tr></table>
</p>
</div>
</p>


<br><hr>
<h1 align="center">Problem Definition</h1>

<!-- <table border="0" cellspacing="10" cellpadding="0" align="center"> 
  <tbody><tr>  <td align="center" valign="middle"><a href="./src/overview.png"> <img src="./src/overview.png" style="width:100%;">  </a></td>
  </tr>
</tbody>
</table> -->

<!-- <table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
    <img src="./src/teaser.png" style="width:100%;">
    </td>
  </tr>
  </tbody>
</table> -->

  <table align=center width=800px>
                <tr>
                    <td>
  <p align="justify" width="20%">
Our goal is to change the kinematic state of the scene to a desired configuration. We assume this configuration is generated by a higher-level task planner and it is needed to perform a long-horizon task. For example, to unload the dishwasher the robot needs to open the door of the dishwasher before picking the clean dishes, and open the cabinet doors before putting away the dishes. Our goal will be to achieve these states, i,e., planning and executing a sequence of single joint interactions to bring the environment to the desired configuration, taking into account the constraints introduced by the scene-level articulation.
</p></td></tr></table>


<br><hr> <h1 align="center">Framework</h1> <!-- <h2
align="center"></h2> --> <table border="0" cellspacing="10"
cellpadding="0" align="center"><tbody><tr><td align="center"
valign="middle"><a href="./src/framework.png"> <img
src="./src/framework.png" style="width:100%;"> </a></td>
</tr> </tbody> </table>

<table width=800px><tr><td> <p align="justify" width="20%">Our approach involves three stages: a mapping stage (left), where the robot conducts a 3D scan and detects handles; an articulation discovery stage (middle), where the robot navigates, interacts, collects observations, and estimates the scene-level articulation model; and a scene-level manipulation stage (right), where the robot plans tasks using the scene-level articulation model and executes long-horizon actions through the articulation planner.  </p></td></tr></table>
<br>



<br><hr>
<h1 align="center">Real World Experiment</h1>
<table border="0" cellspacing="10"
cellpadding="0"><tr><td>
<p>We evaluate our approach in a real-world kitchen that features diverse everyday articulated objects of varying sizes and positions. The experiments demonstrate that our robot can accurately infer articulation properties through exploration. Leveraging the scene-level articulation model, our robot achieves a higher success in planning and manipulating the articulated objects by reasoning at a scene scale. </p></td></tr></table>

<h1 align="center">Articulation Discovery Stage</h1>
<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <video muted controls width="100%">
        <source src="./video/exploration_8x_compressed.mp4"  type="video/mp4">
      </video>
    </td>
  </tr>
  </tbody>
</table>

<h1 align="center">Scene-level Manipulation</h1>
<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <video muted controls width="100%">
        <source src="./video/lh_two_cabinet_v2_2x_compressed.mp4"  type="video/mp4">
      </video>
    </td>
  </tr>
  </tbody>
</table>


<!-- <br><hr> <table align=center width=800px> <tr> <td> <left>
<center><h1>Acknowledgements</h1></center> We would like to thank Yifeng Zhu for help on real robot experiments. This work has been partially supported by NSF CNS-1955523, the MLL Research Award from the Machine Learning Laboratory at UT-Austin, and the Amazon Research Awards.
 -->

<!-- </left></td></tr></table>
<br><br> -->


<!-- <hr />
<center><h1>Citation</h1></center>
<table align="center" width="800px">
              <tr>
                  <td>
                  <left>
<pre><code style="display:block; overflow-x: auto">
@inproceedings{Hsu2023DittoITH,
  title={Ditto in the House: Building Articulation Models of Indoor Scenes through Interactive Perception},
  author={Cheng-Chun Hsu and Zhenyu Jiang and Yuke Zhu},
  booktitle={IEEE International Conference on Robotics and Automation (ICRA)},
  year={2023}
}
</code></pre>
</left></td></tr></table> -->


<div style="display:none">
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-7GF0RHBSDK"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-7GF0RHBSDK');
</script>
<!-- </center></div></body></div> -->

