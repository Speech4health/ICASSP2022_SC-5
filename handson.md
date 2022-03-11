<br>
<br>

<style>
* {
  box-sizing: border-box;
}

/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>


<!-- 
<div class="widewrapper pagetitle">
  <div style="background-color:#617863;padding:5px;">
    <h1 style="color:white;">Keynotes</h1>
  </div>
</div>
<br> -->


<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 12px;
  width: 100%;
  height: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 20px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 18px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
  background-color: #f1f1f1;
  font-size: 16.5px;
}
</style>

<style>
body {font-family: Arial;}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}

/* Style the close button */
.topright {
  float: right;
  cursor: pointer;
  font-size: 28px;
}

.topright:hover {color: red;}
</style>

<h2> Hands-On Session </h2>

The hands-on session will include a detailed walk through of training ASR for dysarthria speech recognition. The goal is to provide attendees clear steps in using ASR toolkits for speech recognition in health, taking dysarthria as a case study.

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')" id="defaultOpen"><strong>Demonstrations</strong></button>
  <button class="tablinks" onclick="openCity(event, 'Tab2')" id="defaultOpen"><strong>Datesets</strong></button> 
</div>

<div id="London" class="tabcontent">
  <button class="collapsible"><b>Training an ASR system on only dysarthric speech data</b></button>
  <div class="content">
  </div>

  <br>
  <button class="collapsible"><b>Adapting a pre-trained ASR system for dysarthric speech data</b></button>
  <div class="content">
  </div>

  <br>
  <button class="collapsible"><b>Training an ASR system on only dysarthric speech data</b></button>
  <div class="content">
  </div>
</div>

<div id="Tab2" class="tabcontent">
  <ul>
    <li style="font-size:16.5px;"> 
    <p><a href="http://www.cs.toronto.edu/~complingweb/data/TORGO/torgo.html"><strong>TORGO</strong></a></p> - word and sentence utterances from control speakers and speakers with Cerebral Palsy (CP) or Amyotrophic lateral sclerosis (ALS)
    </li>
    <p><a href="http://www.isle.illinois.edu/sst/data/UASpeech/"><strong>UASpeech</strong></a></p> - isolated words from control speakers and speakers with Cerebral Palsy (CP)
    </li>
  </ul>
</div>

<!--
<ul>
  <li style="font-size:16.5px;"> Training an ASR system on only dysarthric speech data </li>
  <li style="font-size:16.5px;"> Adapting a pre-trained ASR system for dysarthric speech data </li> 
  <li style="font-size:16.5px;"> Techniques to improve dysarthric speech recognition performance </li> 
</ul>
-->

