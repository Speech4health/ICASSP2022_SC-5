---
layout: workshop      # DON'T CHANGE THIS.
# More detailed instructions (including how to fill these variables for an
# online workshop) are available at
# https://carpentries.github.io/workshop-template/customization/index.html
venue: "IEEE ICASSP 2022"        # brief name of the institution that hosts the workshop without address (e.g., "Euphoric State University")
address: ""      # full street address of workshop (e.g., "Room A, 123 Forth Street, Blimingen, Euphoria"), videoconferencing URL, or 'online'
country: "in"      # lowercase two-letter ISO country code such as "fr" (see https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes) for the institution that hosts the workshop
language: "in"     # lowercase two-letter ISO language code such as "fr" (see https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for the
latitude: "45"        # decimal latitude of workshop venue (use https://www.latlong.net/)
longitude: "-1"       # decimal longitude of the workshop venue (use https://www.latlong.net)
humandate: ""    # human-readable dates for the workshop (e.g., "Feb 17-18, 2020")
humantime: ""    # human-readable times for the workshop (e.g., "9:00 am - 4:30 pm")
startdate: 2022-05-24     # machine-readable start date for the workshop in YYYY-MM-DD format like 2015-01-01
enddate:  2022-05-26       # machine-readable end date for the workshop in YYYY-MM-DD format like 2015-01-02
# instructor:  # boxed, comma-separated list of instructors' names as strings, like ["Kay McNulty", "Betty Jennings", "Betty Snyder"]
helper:      # boxed, comma-separated list of helpers' names, like ["Marlyn Wescoff", "Fran Bilas", "Ruth Lichterman"]
email: [""]    # boxed, comma-separated list of contact email addresses for the host, lead instructor, or whoever else is handling questions, like ["marlyn.wescoff@example.org", "fran.bilas@example.org", "ruth.lichterman@example.org"]
collaborative_notes:  # optional: URL for the workshop collaborative notes, e.g. an Etherpad or Google Docs document (e.g., https://pad.carpentries.org/2015-01-01-euphoria)
eventbrite:           # optional: alphanumeric key for Eventbrite registration, e.g., "1234567890AB" (if Eventbrite is being used)
---

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

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')" id="defaultOpen"><strong>Course Overview</strong></button>
  <button class="tablinks" onclick="openCity(event, 'Tab2')" id="defaultOpen"><strong>Learning Outcomes</strong></button> 
</div>

<div id="London" class="tabcontent">
  <p>The promise of speech technology for health applications is profound and is becoming more
  mature recently. Advancements in core speech technologies and their integration – ranging
  from automatic speech recognition (ASR), text-to-speech (TTS)/voice conversion (VC), speech
  enhancement (SE), and paralinguistic speech processing (PSP) – offer novel tools for both
  scientific discovery and creating innovative solutions for clinical screening, diagnostics,
  intervention supports and beyond. Credited to the potential for widespread impact, research
  sites across all continents are actively engaged in this important research area. This short
  course aims to provide an overview of these existing and potential opportunities of speech-
  based solutions in healthcare together with foundational background of these four major speech
  technologies (ASR, TTS/VC, SE, PSP) and an array of healthcare applications where such
  latest technological development plays a key role, together with a hands-on session on
  automatic speech recognition (ASR) system for dysarthric speech.
  </p>
</div>

<div id="Tab2" class="tabcontent">
  <p>Attendees of this course will get to know the roles that speech technologies such as speech
  enhancement (SE), ASR, paralinguistic speech processing (PSP), text-to-speech synthesis
  (TTS) as well as voice conversion (VC) play in a variety of healthcare applications. This course
  will also do a deep dive into each of the technologies to address how some of the challenges in
  healthcare applications are addressed including data scarcity, interoperability, and cultural &
  language barriers. State-of-the art solutions in healthcare applications using ASR, TTS/VC, SE,
  and PSP will also be covered. Finally, through the lecture materials as well as the hands-on
  session, the attendees would learn relevant toolboxes and get to know about the open-source
  datasets to learn using the concepts tutored even after this short course.
  </p>
</div>
<br>


<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    } 
  });
}
</script>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>