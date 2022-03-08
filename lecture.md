
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


<div class="container">
  <br>
  <br>
<button class="collapsible"><img style="height: 120px; width:auto;padding:5px;"  src="./assets/img/persons/Anurag_Dwarakanath.PNG"><b>Lecture 1: ASR for Health</b> <p>Prasanta Kumar Ghosh</p></button>
<div class="content">
  
<p><strong>Brief Bio:</strong> Prasanta Kumar Ghosh received his Ph.D. in Electrical Engineering from University of Southern California (USC), Los Angeles, USA in 2011. Prior to that he obtained his M.Sc.(Engineering) in Electrical Communication Engineering from Indian Institute of Science (IISc), Bangalore and B.E.(ETCE) in Electronics from Jadavpur University, Kolkata in 2006 and 2003 respectively. He has been a Research Intern at Microsoft Research India, Bangalore in the areas of audio-visual speaker verification from March to July in 2006. During 2011-2012 he was with IBM India Research Lab (IRL) as a researcher. Currently, he is an associate professor in the department of Electrical Engineering (EE) at IISc. Prasanta Kumar Ghosh was awarded the INSPIRE faculty fellowship from Department of Science and
Technology (DST), Govt. of India in 2012. He received the best M.Sc. (Engg.) thesis award for the
year 2006-07 in the Electrical Sciences division at IISc. He was awarded Center of Excellence in
Teaching's award for excellence in teaching in the category of EE for the year 2010-11 in USC. He has
also received Prof. Priti Shankar Teaching Award for Assistant Professor in 2017 from Indian Institute of
Science (IISc), Bangalore. His research interests include human centered signal processing, engineering model and technology development with applications to education and health care. 
</p>
</div>
 <br>




<button class="collapsible"><img style="height: 120px; width:auto;padding:5px;"  src="./assets/img/persons/Sri_Garimella.jpg">Sri Garimella, Amazon</button>
<div class="content">
  <p><strong>Title:</strong> Overview of Speech Recognition Technology in Conversational Agents</p>
  <p><strong>Abstract:</strong> From the early days of modern Automatic Speech Recognition (ASR) research in the 1990s, one of the driving visions of the field has been a computer-based assistant that could accomplish tasks for the user, simply by being spoken to. Today, we are close to achieving that vision, with a whole array of speech-enabled AI agents eager to help users. Amazon’s Alexa pioneered the AI assistant concept for smart speaker devices enabled by far-field ASR. It currently supports billions of customer interactions per week, on over 100 million devices across multiple languages. This talk will give an overview of the interplay between underlying speech technologies, including wakeword detection, endpointing, speaker identification, and speech recognition that enable Alexa. We highlight successes and challenges in developing large-scale ASR, and dive into the unique data aspects of large-scale deployments like Alexa, where a continuous stream of unlabeled data enables successful applications of semi-supervised learning. Finally, we highlight problems that remain to be solved before the promise of a fully natural, conversational assistant is fully realized.</p>

<p><strong>Brief Bio:</strong> Sri Garimella is a senior manager of Applied Science, Alexa ASR in India. His team developed the ASR technology for launching Alexa in Indian English and Hindi languages. Sri obtained PhD from the Department of Electrical and Computer Engineering, Center for Language and Speech Processing at the Johns Hopkins University, Baltimore, USA in 2012. And Master of Engineering in Signal Processing from the Indian Institute of Science, Bangalore, India in 2006.</p>
Weblink:<a href="https://sites.google.com/site/sivaramiisc/">https://sites.google.com/site/sivaramiisc/</a>

</div>
<br>

<button class="collapsible"><img style="height: 120px; width:auto;padding:5px;"  src="./assets/img/persons/Samuel_Thomas.jpg">Samuel Thomas, IBM T.J. Watson Research Center, New York</button>
<div class="content">
  <p><strong>Title:</strong> What next after ASR in Indian Languages? We speak in order to be understood!</p>
  <p><strong>Abstract:</strong> The MUCS 2021 challenge has focused on building multilingual and code-switching ASR systems for Indian languages in low resource settings. Within this challenge, teams have successfully tackled important problems and have demonstrated significant improvements on various languages. Where do these gains lead us next? If we speak in order to be understood, we advocate that the next frontier in this space is spoken language understanding (SLU). In this talk we will review recent work in end-to-end spoken language understanding, where the speech input is directly processed into intent without going through an intermediate text transcript. The lessons learnt in building ASR systems in low resource settings are extremely useful for this task too, as very often there is very limited SLU training data. We will share insights on training E2E SLU systems and the challenges ahead and how they can be applied for Indic languages.</p>

<p><strong>Brief Bio:</strong> Samuel Thomas received his B.Tech degree in Computer Engineering from the Cochin University of Science and Technology, India (2000) and M.S degree in Computer Science and Engineering from the Indian Institute of Technology Madras, India (2006) before earning his Doctor of Philosophy degree from the Johns Hopkins University, Baltimore in 2012. Since graduation, he has been at the IBM T.J. Watson Research Center, New York with the Speech Technologies Group. In the past, he has worked on several speech research projects and workshops with the Center for Language and Speech Processing (CLSP) at JHU, the Idiap Research Institute, Switzerland and the TeNeT group, IIT Madras. His research interests include speech processing and machine learning for speech recognition, spoken language understanding, speech synthesis and speaker recognition.</p>
Weblink:<a href="https://researcher.watson.ibm.com/researcher/view.php?person=us-sthomas">https://researcher.watson.ibm.com/researcher/view.php?person=us-sthomas</a>
</div>
<br>





<button class="collapsible"><img style="height: 120px; width:auto;padding:5px;"  src="./assets/img/persons/vikas_joshi.jfif">Vikas Joshi, Senior Applied Researcher, Microsoft Research India.</button>
<div class="content">
  <p><strong>Title: </strong>Recent advances in transfer learning and multilingual methods for streaming end-to-end ASR systems</p>
  <p><strong>Abstract: </strong>Transfer learning (TL) and multilingual models often improve the performance of low resource langauges, by leveraging data from high resource langauges. Multilingual models also simplify the training and deployment strategy, as a single model is used for multiple languages. This talk will provide an overview of recent advances in TL and multilingual methods for streaming end-to-end (E2E) ASR systems.  Though there is considerable progress, most of the multilingual methods assume the availability of the input language. Hence, it is still challenging to provide a truly multilingual experience, where users can interact with voice assistants in any language, interchangeably, without explicitly setting the language of the conversation. While highlighting the improvements made, we will also discuss the practical challenges and potential research directions in building a truly multilingual experience.</p>
  <p><strong>Brief Bio: </strong>Vikas Joshi is a senior researcher at Microsoft Speech team in India, working on various speech technologies including multilingual end-to-end ASR systems. Prior to Microsoft, he spent 3 years at Amazon Alexa, building large scale ASR systems and 4.5 years at IBM India Research labs. Vikas obtained his PhD degree from IIT Madras in 2016 and completed BTech from BVB college of Engineering, Hubli. He has over 15 publications and 10 granted patents.</p>
  Weblink:<a href="https://in.linkedin.com/in/vikas-joshi-aa3b939">https://in.linkedin.com/in/vikas-joshi-aa3b939</a>
</div>
<br>

</div>


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
