---
layout: page
permalink: /dataset/
title: Datasets
description: 
nav: true
nav_order: 6
---
# PARSEL Dataset 


  PARSEL is a novel multi-modal dataset collected to design a dataset for modeling the successive phases of the decision-making process involved in selecting suitable cooperation and collaboration partners in online conversations. PARSEL was collected in a semi-in-the-wild setting via Prolific and Qualtrics using a self-developed early version of OpenVIMO: a software framework for creating video-based online interaction experiments built on open-source technologies (see below). PARSEL was collected in two parts - intake and interaction sessions - that happened within one week from each other. 

<div class="row justify-content-sm-center">
  <div class="col-sm-20 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/intake.jpg" title="Figure 1. Overview of the experimental design of PARSEL" class="img-fluid rounded z-depth-1" %}
    <p class="mt-2 text-muted"> Figure 1. Visualization of the Dataset Flow (Interaction Session) </p>
  </div>
</div>


### Dataset Flow

Participants first completed questionnaires assessing various traits (e.g., HEXACO personality traits, social anxiety). A week later, they were placed in groups of four to six for an interactive session. Each participant uploaded a photo and was randomly assigned to a condition emphasizing either competence or trustworthiness in partner selection for a cooperative task. After viewing group members’ photos, participants rated their impressions and indicated whom they would choose as a partner (see Figure 1).

Regardless of these choices, all participants took part in a 3-minute one-on-one video conversation with each group member. Before each interaction, they viewed their partner’s photo and reported expectations; afterward, they evaluated their partner, the conversation, and their sense of teamwork, and indicated their willingness to collaborate again. Participants then completed an individual cooperative task with each partner, followed by a surprise 3-minute collaborative “Feud Task” with each partner. For a visualization see the figure above. 


### Type of Data 

The dataset contains multi-modal data: 
<ol>
  <li>Audio-visual recordings of both initial conversational and collaborative task interactions</li>
    <ul>
      <li>Local recordings (Original Video) </li>
      <li>Global recordings (Streamed Video) </li>
    </ul>

<div class="row justify-content-sm-center">
  <div class="col-sm-5 mt-2 mt-md-2">
    {% include figure.liquid path="assets/img/pic1.jpg" title="" class="img-fluid rounded z-depth-1" %}
    <p class="mt-2 text-muted"> Figure 2. Examples of an online conversation </p>
  </div>

  <div class="col-sm-5 mt-2 mt-md-2">
    {% include figure.liquid path="assets/img/pic2.jpg" title="" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

  <li>Photographs of participants </li>
  <li>Self-report Surveys (Intake) </li>
     <ul>
      <li>HEXACO personality </li>
      <li>Social Anxiety</li>
      <li>Psychopathy</li>
      <li>Trust</li>
      <li>Cooperative Behavior (Social Value Orientation)</li>
      <li>Partner Preferences</li>
    </ul>
   <li>First-person perceptions and Partner Selection Decisions (Interaction) </li>
    <ul>
      <li>Person Perceptions ("How trustworthy/skillful is this person?")</li>
      <li>Situation Perceptions ("Our preferred outcomes in this situation are conflicting.")</li>
      <li>Team perceptions (i.e., social cohesion and rapport)</li>
    </ul>
  <li>Measures of cooperative and collaborative behavior and performance</li>
    <ul>
      <li> Money exchanged in a cooperative task </li>
      <li> Correctness of answers on a question from a Family Feud </li>
    </ul> 
  <li>Transcriptions of the audio-video recordings</li>
  <li>Extracted OpenFace (facial) and OpenSmile (acoustic) features</li>
</ol> 

### OpenVIMO 

For the collection of the dataset, the authors also developed a software framework for creating video-based online interaction experiments built on open-source technologies. It can be deployed on a server under a researcher’s control without relying on
additional commercial third-party services. Concretely, it enables (1) the creation of web-based experiments and surveys involving video calls between participants, as well as (2) the remote monitoring of participants’ progress throughout a study, including means for communication and intervention throughout a protocol; (3) collecting and storing survey and interaction data (incl. audio and video) and (4) allow the staging of highly customized experimental protocols and to be dynamically expanded by the research community. 

We are currently in the final stages of developing and making openVIMO open source. However, if you are interested in using the tool you can contact us at [parsel-ewi@tudelft.nl](mailto:parsel-ewi@tudelft.nl). 

### Dataset Access 

The dataset is available and can be provided only after the Licensors receive an [End-User License Agreemant](/assets/pdf/EULA_Paco.pdf) that dictates the conditions under which the dataset can be provided and used. You can send the signed EULA to [parsel-ewi@tudelft.nl](mailto:parsel-ewi@tudelft.nl). Additionally, in the e-mail please indicate which part of the data you want to use and need. You can use the list of the type of data to refer to the part of the dataset you need.  

### More Information on the Dataset

For more information check the preprint of the [Dataset paper](https://tiffanymatejh.github.io/assets/pdf/taffc.pdf) or check the Published version at [TAFFC](https://ieeexplore.ieee.org/abstract/document/11130635).

### Papers using the dataset 

List of papers that have already used PARSEL dataset: 

[Matej Hrkalovic, T., Dudzik, B., Hung, H., & Balliet, D. (2025). Partner perceptions during brief online interactions shape partner selection and cooperation. PloS one, 20(4), e0318137.](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0318137)

Vasiliki, K., Buczny, J., Matej Hrkalovic, T., Dudzik, B., Balliet, D., & De Vries, R., (under review). Partners Among Strangers: A Social Relations Perspective on Personality and Collaborative Partner Preferences in First Encounters



