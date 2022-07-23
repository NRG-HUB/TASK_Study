<body style="background-color:e4e4e4;"></body>

<p align="center"> <img width="200" src="https://raw.githubusercontent.com/NRG-HUB/SMARTPHONE_Study/main/nrg-logo.jpg" alt="logo"> </p> 

This page contains information about the TASK study being conducted by the NRG lab, University of Reading. <br>

### This is a study being conducted by the [NRG-Lab](https://www.nrg-lab.co.uk/) by the following researchers:<br>
Prof. Ciara McCabe (<a href="mailto:c.mccabe@reading.ac.uk">c.mccabe@reading.ac.uk</a>) 

Angad Sahni, PhD Student (<a href="mailto:a.sahni@pgr.reading.ac.uk">a.sahni@pgr.reading.ac.uk</a>) 
<br>
<br>

### You can view the [instructions](README.md#instructions) with images from the task.<br> This will give you an idea of what it entails.

<br>

# Take Part!
<br>
You will need a <b>laptop or PC</b> to participate.
<br>
<br>
<p align="center"> <img width="1000" src="Task_poster.jpg" alt="poster"> </p> 

<br>

# Instructions

### Your Aim
We want you to <b>MAXIMIZE reward</b> and <b>MINIMIZE effort</b> over the whole task.<br><br>
One side is <b>better than the other</b> and we want you to figure out which one it is!

<br>
<h3 align="center"><b>Choose a shape</b><br> <img width="600" src="task_choice.png" alt="choice"> </h3>
<br>
<br>

<h3 align="center"><b>The outcome is an image (reward) and<br>the effort it requires</b><br> <img width="500" src="task_outcome.png" alt="outcome"> </h3>
<br>
<br>

<h3 align="center"><b>Exert effort by pressing C and M in alternation (CMCMCM...)<br>and fill up the bar</b><br> <img width="500" src="task_effort.png" alt="effort"> </h3>
<br>
<br>

<h3 align="center"><b>Achieve reward!<br>It's obvious which one is more rewarding...</b><br><br><img width="800" src="task_reward.png" alt="reward"> </h3>
<br>
<br>

<h3 align="center" style="color:red"><b>REPEAT!</b></h3>
<br>
<br>


<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 20px;
}

#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: red;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: white;
  color: red;
}
</style>

<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>

<script>
//Get the button
var mybutton = document.getElementById("myBtn");

// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>
