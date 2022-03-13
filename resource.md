<br>
<br>
<br>
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

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Tab1')" id="defaultOpen"><strong>Lecture References</strong></button>
  <button class="tablinks" onclick="openCity(event, 'Tab2')" id="defaultOpen"><strong>Lecture Slides</strong></button> 
  <button class="tablinks" onclick="openCity(event, 'Tab3')" id="defaultOpen"><strong>Code Repositories</strong></button>
  <button class="tablinks" onclick="openCity(event, 'Tab4')" id="defaultOpen"><strong>Recent Related Publications</strong></button>
</div>

<div id="Tab1" class="tabcontent">

<button class="collapsible"><b>Lecture 1: PSP for Health</b></button>
<div class="content">
<br>
<ul>
  <li style="font-size:16.5px;"> Haider, Fasih, Sofia De La Fuente, and Saturnino Luz. "An assessment of paralinguistic acoustic features for detection of Alzheimer's dementia in spontaneous speech." IEEE Journal of Selected Topics in Signal Processing 14.2 (2019): 272-281. </li>
  <li style="font-size:16.5px;"> Li, Ming, et al. "An automated assessment framework for atypical prosody and stereotyped idiosyncratic phrases related to autism spectrum disorder." Computer Speech & Language 56 (2019): 80-94. </li>
  <li style="font-size:16.5px;"> Cummins, Nicholas, Alice Baird, and Bjoern W. Schuller. "Speech analysis for health: Current state-of-the-art and the increasing impact of deep learning." Methods 151 (2018): 41-54. </li>
  <li style="font-size:16.5px;"> Hong, Hui-Ting, et al. "Investigating the Variability of Voice Quality and Pain Levels as a Function of Multiple Clinical Parameters." Interspeech. 2020. </li>
  <li style="font-size:16.5px;"> Arevian, Armen C., et al. "Clinical state tracking in serious mental illness through computational analysis of speech." PLoS one 15.1 (2020): e0225695. </li>
  <li style="font-size:16.5px;"> Schuller, Björn, and Anton Batliner. Computational paralinguistics: emotion, affect and personality in speech and language processing. John Wiley & Sons, 2013. </li>
  <li style="font-size:16.5px;"> Schmitt, Maximilian, and Björn W. Schuller. "Machine-based decoding of paralinguistic vocal features." The Oxford handbook of voice perception. 2019. </li>
  <li style="font-size:16.5px;"> Schuller, B. et al. "Computational Paralinguistic Challenge" <a href="http://www.compare.openaudio.eu/">http://www.compare.openaudio.eu/</a> </li>
  <li style="font-size:16.5px;"> Teixeira, Francisco, Alberto Abad, and Isabel Trancoso. "Privacy-preserving paralinguistic tasks." ICASSP 2019-2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2019. </li>
</ul>
</div>

<button class="collapsible"><b>Lecture 2: SE for Health</b></button>
<div class="content">
<br>
<ul>
  <li style="font-size:16.5px;"> Wang, DeLiang, and Jitong Chen. "Supervised speech separation based on deep learning: An overview." IEEE/ACM Transactions on Audio, Speech, and Language Processing 26.10(2018): 1702-1726. </li>
  <li style="font-size:16.5px;"> Loizou, Philipos C. Speech enhancement: theory and practice. CRC press, 2007. </li>
  <li style="font-size:16.5px;"> Vincent, Emmanuel, Tuomas Virtanen, and Sharon Gannot, eds. Audio source separation and speech enhancement. John Wiley & Sons, 2018. </li>
  <li style="font-size:16.5px;"> Fu, Szu-Wei, et al. "End-to-end waveform utterance enhancement for direct evaluation metrics optimization by fully convolutional neural networks." IEEE/ACM Transactions on Audio, Speech, and Language Processing 26.9 (2018): 1570-1584. </li>
  <li style="font-size:16.5px;"> Fu, Szu-Wei, et al. "Metricgan: Generative adversarial networks based black-box metric scores optimization for speech enhancement." International Conference on Machine Learning. PMLR, 2019. </li>
  <li style="font-size:16.5px;"> Lesica, Nicholas A., et al. "Harnessing the power of artificial intelligence to transform hearing healthcare and research." Nature Machine Intelligence 3.10 (2021): 840-849. </li>
  <li style="font-size:16.5px;"> Goehring, Tobias, et al. "Speech enhancement based on neural networks improves speech intelligibility in noise for cochlear implant users." Hearing research 344 (2017): 183-194. </li>
  <li style="font-size:16.5px;"> Lai, Ying-Hui, et al. "A deep denoising autoencoder approach to improving the intelligibility of vocoded speech in cochlear implant simulation." IEEE Transactions on Biomedical Engineering 64.7 (2016): 1568-1578. </li>
  <li style="font-size:16.5px;"> Lai, Ying-Hui, et al. "A deep denoising autoencoder approach to improving the intelligibility of vocoded speech in cochlear implant simulation." IEEE Transactions on Biomedical Engineering 64.7 (2016): 1568-1578. </li>
  <li style="font-size:16.5px;"> Tseng, Rung-Yu, et al. "A Study of Joint Effect on Denoising Techniques and Visual Cues to Improve Speech Intelligibility in Cochlear Implant Simulation." arXiv preprint arXiv:1909.11919 (2019). </li>
</ul>
</div>

<button class="collapsible"><b>Lecture 3: TTS/VC for Health</b></button>
<div class="content">
<br>
<ul>
  <li style="font-size:16.5px;"> Tan, Xu, et al. "A survey on neural speech synthesis." arXiv preprint arXiv:2106.15561 (2021). </li>
  <li style="font-size:16.5px;"> Sisman, Berrak, et al. "An overview of voice conversion and its challenges: From statistical modeling to deep learning." IEEE/ACM Transactions on Audio, Speech, and Language Processing (2020). </li>
  <li style="font-size:16.5px;"> Mohammadi, Seyed Hamidreza, and Alexander Kain. "An overview of voice conversion systems." Speech Communication 88 (2017): 65-82. </li>
  <li style="font-size:16.5px;"> Yen, Ming-Chi, et al. "Mandarin Electrolaryngeal Speech Voice Conversion with Sequence-to-Sequence Modeling." Submitted to Interspeech (2021). </li>
  <li style="font-size:16.5px;"> Kobayashi, Kazuhiro, and Tomoki Toda. "Electrolaryngeal speech enhancement with statistical voice conversion based on CLDNN." 2018 26th European Signal Processing Conference (EUSIPCO). IEEE, 2018. </li>
  <li style="font-size:16.5px;"> Kobayashi, Kazuhiro, and Tomoki Toda. "Implementation of low-latency electrolaryngeal speech enhancement based on multi-task CLDNN." 2020 28th European Signal Processing Conference (EUSIPCO). IEEE, 2021. </li>
  <li style="font-size:16.5px;"> Kameoka, Hirokazu, et al. "ConvS2S-VC: Fully convolutional sequence-to-sequence voice conversion." IEEE/ACM Transactions on Audio, Speech, and Language Processing 28(2020): 1849-1863. </li>
</ul>
</div>

<button class="collapsible"><b>Lecture 4: ASR for Health</b></button>
<div class="content">
<br>
<ul>
  <li style="font-size:16.5px;"> Metcalf, David S., et al. Voice Technology in Healthcare: Leveraging Voice to Enhance Patient and Provider Experiences. CRC Press, Taylor & Francis Group, 2020. </li>
  <li style="font-size:16.5px;"> Latif, Siddique, et al. "Speech technology for healthcare: Opportunities, challenges, and state of the art." IEEE Reviews in Biomedical Engineering 14 (2020): 342-356. </li>
  <li style="font-size:16.5px;"> Wang, Dong, Xiaodong Wang, and Shaohe Lv. "An overview of end-to-end automatic speech recognition." Symmetry 11.8 (2019): 1018. </li>
  <li style="font-size:16.5px;"> Chiu, Chung-Cheng, et al. "Speech recognition for medical conversations." Interspeech. 2017. </li>
  <li style="font-size:16.5px;"> Blackley, Suzanne V., et al. "Speech recognition for clinical documentation from 1990 to 2018: a systematic review." Journal of the american medical informatics association 26.4 (2019): 324-338. </li>
  <li style="font-size:16.5px;"> Takashima, Ryoichi, Tetsuya Takiguchi, and Yasuo Ariki. "Two-step acoustic model adaptation for dysarthric speech recognition." ICASSP 2020-2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2020. </li>
  <li style="font-size:16.5px;"> Geng, Mengzhe, et al. "Investigation of Data Augmentation Techniques for Disordered Speech Recognition." Interspeech. 2020. </li>
  <li style="font-size:16.5px;"> Shor, Joel, et al. "Personalizing ASR for dysarthric and accented speech with limited data." arXiv preprint arXiv:1907.13511 (2019). </li>
  <li style="font-size:16.5px;"> Espana-Bonet, Cristina, and José AR Fonollosa. "Automatic speech recognition with deep neural networks for impaired speech." International Conference on Advances in Speech and Language Technologies for Iberian Languages. Springer, Cham, 2016. </li>
</ul>
</div>
<br>
  
</div>

<div id="Tab2" class="tabcontent">
<br>
<p><span style="color: red; font-size:18px;"><strong>Coming soon!</strong></span></p>
<br>
</div>

<div id="Tab3" class="tabcontent">
<br>
<p><span style="color: red; font-size:18px;"><strong>Coming soon!</strong></span></p>
<br>
</div>

<div id="Tab4" class="tabcontent">

<button class="collapsible"><b>Chi-Chun Lee</b></button>
<div class="content">
<br>
<ul>
  <li style="font-size:16.5px;"> Yun-Shao Lin, Susan Shur-Fen Gau and Chi-Chun Lee, "A Multimodal Interlocutor-Modulated Attentional BLSTM for Classifying Autism Subgroups During Clinical Interviews," in IEEE Journal of Selected Topics in Signal Processing, vol. 14, no. 2, pp. 299-311, Feb. 2020, doi: 10.1109/JSTSP.2020.2970578. </li>
  <li style="font-size:16.5px;"> Chin-Po Chen, Susan Shur-Fen Gau, and Chi-Chun Lee. "Toward Differential Diagnosis of Autism Spectrum Disorder using Multimodal Behavior Descriptors and Executive Functions." in Journal of Computer Speech & Language 56 (2019): 17-35. </li>
  <li style="font-size:16.5px;"> Hui-Ting Hong, Jeng-Lin Li, Yi-Ming Weng, Chip-Jin Ng and Chi-Chun Lee, "Investigating the Variability of Voice Quality and Pain Levels as a Function of Multiple Clinical Parameters" in Proceedings of the International Speech Communication Association (Interspeech), pp. 3058-3062, 2019. </li>
  <li style="font-size:16.5px;"> Daniel Bone, Chi-Chun Lee, Theodora Chaspari, James Gibson, Shrikanth Narayanan, "Signal Processing and Machine Learning for Mental Health Research and Clinical Applications", in IEEE Signal Processing Magazine 34(5), 196 – 195, 2017. </li>
  <li style="font-size:16.5px;"> Daniel Bone, Chi-Chun Lee, Matthew Black, Marian Williams, Sungbok Lee, Pat Levitt, and Shrikanth S. Narayanan, “The Psychologist as an Interlocutor in ASD Assessment: Insights from a Study of Spontaneous Prosody”, in: Journal of Speech, Language, and Hearing Research, 57(1):1162-1177, August 2014, doi: 10.1044/2014_JSLHR-S-13-0062 </li>
</ul>
</div>
<br>

<button class="collapsible"><b>Prasanta Kumar Ghosh</b></button>
<div class="content">
<br>
<ul>
  <li style="font-size:16.5px;"> Tanuka Bhattacharjee, Jhansi Mallela, Yamini Belur, Nalini Atchayaram, Ravi Yadav, Pradeep Reddy, Dipanjan Gope, and P. K. Ghosh, “Source and Vocal Tract Cues for Speech-based Classification of Patients with Parkinson’s Diseaseand Healthy Subjects”, in Proc. Interspeech, pp. 2961-2965, 2021. </li>
  <li style="font-size:16.5px;"> Tanuka Bhattacharjee, Jhansi Mallela, Yamini Belur, Nalini Atchayaram, Ravi Yadav, Pradeep Reddy, Dipanjan Gope, and P. K. Ghosh, “Effect of Noise and Model Complexity on Detection of Amyotrophic Lateral Sclerosis and Parkinson’s Disease Using Pitch and MFCC”, in IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 7313-7317, 2021. </li>
  <li style="font-size:16.5px;"> Jhansi Mallela, Aravind Illa, Yamini Belur, Nalini Atchayaram, Ravi yadav, Pradeep Reddy, Dipanjan Gope, P. K. Ghosh, “Raw speech waveform based classification of patients with ALS, Parkinson’s Disease and healthy controls using CNN-BLSTM”, in Proc. Interspeech, pp. 4586-4590, 2020. </li>
  <li style="font-size:16.5px;"> Jhansi Mallela, Aravind Illa, Suhas B N, Sathivik Udupa, Yamini Belur, Nalini Atchayaram, Ravi Yadav, Pradeep Reddy, Dipanjan Gope, P. K. Ghosh, “Voice Based Classification of Patients with Amyothrophic Lateral Sclerosis, Parkinson’s Disease and Healthy Controls with CNN-LSTEM using Transfer Learning”, in IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 6784-6788, 2020. </li>
  <li style="font-size:16.5px;"> Suhas BN, Deep Patel, Nithin Rao, Yamini Belur, Pradeep Reddy, Nalini Atchayaram, Ravi Yadav, Dipanjan Gope and P. K. Ghosh, “Comparison of Speech Tasks and Recording Devices for Voice Based Automatic Classification of Healthy Subjects and Patients with Amyotrophic Lateral Sclerosis”, in Proc. Interspeech, pp. 4564-4568, 2019. </li>
</ul>
</div>
<br>

<button class="collapsible"><b>Yu Tsao</b></button>
<div class="content">
<br>
<ul>
  <li style="font-size:16.5px;"> S.-W. Fu, T.-W. Wang, Y. Tsao, X. Lu, and H. Kawai “End-to-End Waveform Utterance Enhancement for Direct Evaluation Metrics Optimization by Fully Convolutional Neural Networks,” IEEE/ACM Transactions on Audio, Speech and Language Processing, vol. 26(9), pp. 1570-1584, April 2018. </li>
  <li style="font-size:16.5px;"> S.-W. Fu, C.-F. Liao, Y. Tsao, and S.-D. Lin, “MetricGAN: Generative Adversarial Networks based Black-box Metric Scores Optimization for Speech Enhancement,” in Proc. ICML 2019, Long Oral Presentation with ICML Travel Grant. </li>
  <li style="font-size:16.5px;"> Y.-H. Lai, F. Chen, S.-S. Wang, X. Lu, Y. Tsao, and C.-H. Lee,“A Deep Denoising Autoencoder Approach to Improving the Intelligibility of Vocoded Speech in Cochlear Implant Simulation,” IEEE Transactions on Biomedical Engineering, vol. 64(7), pp. 1568-1578, July, 2017. </li>
  <li style="font-size:16.5px;"> J.-C. Hou, S.-S. Wang, Y.-H. Lai, Y. Tsao, H.-W. Chang, and H.-M. Wang, “Audio-Visual Speech Enhancement Using Multimodal Deep Convolutional Neural Networks,” IEEE Transactions on Emerging Topics in Computational Intelligence, 2018., vol. 2(2), pp. 117-128, April. 2018. </li>
  <li style="font-size:16.5px;"> C.-L. Liu, S.-W. Fu, Y.-J. Li, J.-W. Huang, H.-M. Wang, and Y. Tsao, "Multichannel Speech Enhancement by Raw Waveform-mapping using Fully Convolutional Networks," IEEE Transactions on Audio, Speech and Language Processing, volume 28, pages 1888-1900, February 2020. </li>
</ul>
</div>
<br>

<button class="collapsible"><b>Yi-Chiao Wu</b></button>
<div class="content">
<br>
<ul>
  <li style="font-size:16.5px;"> Y.-C. Wu, T. Hayashi, P. L. Tobing, K. Kobayashi, and T. Toda, “Quasi-Periodic WaveNet: an autoregressive raw waveform generative model with pitch-dependent dilated convolution neural network,” in IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 29, pp. 1134-1148, 2021. </li>
  <li style="font-size:16.5px;"> Y.-C. Wu, T. Hayashi, T. Okamoto, H. Kawai, and T. Toda, “Quasi-Periodic Parallel WaveGAN: a non-autoregressive raw waveform generative model with pitch-dependent dilated convolution neural network,” in IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 29, pp. 792-806, 2021. </li>
  <li style="font-size:16.5px;"> Y.-C. Wu, C.-H. Hu, H.-S. Lee, Y.-H. Peng, W.-C. Huang, Y. Tsao, H.-M. Wang, and T. Toda, “Relational data selection for data augmentation of speaker-dependent multi-band MelGAN vocoder,” in Proc. Interspeech, pp. 3630-3634, Aug.-Sep. 2021. </li>
  <li style="font-size:16.5px;"> Y.-C. Wu, P. L. Tobing, K. Kobayashi, T. Hayashi, and T. Toda, “Non-parallel voice conversion system with WaveNet vocoder and collapsed speech suppression,” in IEEE Access, vol. 8, pp. 62094-62106, Apr. 2020. </li>
  <li style="font-size:16.5px;"> Y.-C. Wu, P. L. Tobing, K. Yasuhara, N. Matsunaga, Y. Ohtani, and T. Toda, “A cyclical post-filtering approach to mismatch refinement of neural vocoder for text-to-speech systems,” in proc. Interspeech, Full virtual, Oct. 2020. </li>
</ul>
</div>
<br>

<button class="collapsible"><b>Hsin-Min Wang</b></button>
<div class="content">
<br>
<ul>
  <li style="font-size:16.5px;"> Ming-Chi Yen, Wen-Chin Huang, Kazuhiro Kobayashi, Yu-Huai Peng, Shu-Wei Tsai, Yu Tsao, Tomoki Toda, Jyh-Shing Jang, and Hsin-Min Wang, "Mandarin Electrolaryngeal Speech Voice Conversion with Sequence-to-Sequence Modeling," IEEE Workshop on Automatic Speech Recognition and Understanding (ASRU 2021), December 2021. </li>
  <li style="font-size:16.5px;"> Hung-Shin Lee, Yu Tsao, Shyh-Kang Jeng, and Hsin-Min Wang, "Subspace-based Representation and Learning for Phonotactic Spoken Language Recognition," IEEE/ACM Transactions on Audio, Speech, and Language Processing, 28, pp. 3065-3079, November 2020. </li>
  <li style="font-size:16.5px;"> Wen-Chin Huang, Hao Luo, Hsin-Te Hwang, Chen-Chou Lo, Yu-Huai Peng, Yu Tsao, and Hsin-Min Wang, "Unsupervised Representation Disentanglement using Cross Domain Features and Adversarial Learning in Variational Autoencoder based Voice Conversion," IEEE Transactions on Emerging Topics in Computational Intelligence, 4(4), pp. 468-479, August 2020. </li>
  <li style="font-size:16.5px;"> Chin-Cheng Hsu, Hsin-Te Hwang, Yi-Chiao Wu, Yu Tsao, and Hsin-Min Wang, "Voice Conversion from Unaligned Corpora Using Variational Autoencoding Wasserstein Generative Adversarial Networks," Interspeech2017, August 2017. </li>
  <li style="font-size:16.5px;"> Chin-Cheng Hsu, Hsin-Te Hwang, Yi-Chiao Wu, Yu Tsao and Hsin-Min Wang, "Voice Conversion from Non-parallel Corpora Using Variational Auto-encoder," APSIPA Annual Summit and Conference (APSIPA ASC 2016), December 2016. </li>
</ul>
</div>
<br>

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