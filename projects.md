---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
classes: wide
---
 
The overarching theme of my research is designing and evaluating accessible interactions with emerging technologies such as wearables and AI-infused applications. The majority of my work has focus on technologies that benefit people with visual impairments such as exploring interactions with wearables for directional feedback or exploring interactions with speech and image recognition systems, which are error prone as any automation systems. To better contextualize my findings and contribute to inclusive interactions that can benefit a larger population, sighted participants are often included in my studies.

## Teachable Interface for Personalizing an Object Recognizer

<!-- ![intro_image](/images/MachineTeachingPerception.png){:width="80%"}<br> -->
<!-- <img src='/images/MachineTeachingPerception.png' width=100%><br> -->
<p align="center">
  <img src="/images/MachineTeachingPerception.png" width="80%" alt="sample images of objects collected from crowdworkers.">
</p>

The projects in this research aim to improve the user interface of machine teaching for non-experts. 
Through a user study, I examined end-users’ perception of machine teaching through a quantitative and qualitative analysis 
so that we can understand how non-experts train a machine learning model using a teachable interface. 
As a machine teaching application, I built a teachable object recognizer using an Inception-v3 model and transfer learning in this study. 
In addition, as an effort to facilitate machine teaching for end-users, 
I led a project to create a user interface that generates descriptors of a training set so that a blind user can understand the training set 
based on the them when they fine-tune an object recognizer with their own photos as a training set. 
The descriptors are generated using computer vision techniques such as hand detection, image quality assessment, and SIFT feature extraction/matching.

### Publications
[Blind Users Accessing Their Training Images in Teachable Object Recognizers](/papers/ASSETS2022-Descriptors.pdf)<br>
**Jonggi Hong**, Jaina Gandhi, Ernest Essuah Mensah, Farnaz Zeraati, Ebrima Jarjue, Kyungjun Lee, Hernisa Kacorri. ASSETS 2022.

[Crowdsourcing the Perception of Machine Teaching](/papers/CHI2020-CrowdTeaMa.pdf)<br>
**Jonggi Hong**, Kyungjun Lee, June Xu, Hernisa Kacorri. CHI 2020.

[Revisiting Blind Photography in the Context of Teachable Object Recognizers](/papers/ASSETS2019-Revisiting.pdf)<br>
Kyungjun Lee, **Jonggi Hong**, Ebrima Jarjue, Simone Pimento, Hernisa Kacorri. ASSETS 2019.

[Exploring Machine Teaching for Object Recognition with the Crowd](/papers/CrowdTeaMa_CHI2019_LateBreakingWork.pdf)<br>
**Jonggi Hong**, Kyungjun Lee, June Xu, Hernisa Kacorri. CHI EA 2019.

[Accessible Human-Error Interactions in AI Applications for the Blind](/papers/Ubicomp2018_DC_Jonggi.pdf)<br>
**Jonggi Hong**. UbiComp DC 2018.


<hr style="height:2px;border-width:0;color:gray;background-color:gray">


## Identifying Speech Recognition Errors with Audio-only Interactions

<!-- ![intro_image](/images/dictation_CHI2017.png){:width="80%"}<br> -->
<!-- ![intro_image](/images/dictation_CHI2017.png){:class="img-responsive"}<br> -->
<p align="center">
  <img src="/images/dictation_CHI2017.png" width="80%" alt="a setup for the speech dictation task">
</p>

I explored the challenges of identifying automatic speech recognition errors for people with visual impairments. 
Due to the similarity between the text-to-speech of the original input and the misrecognized texts, 
blind users may miss the errors when they review the speech recognition results with text-to-speech. 
Therefore, I explored the experience of reviewing and identifying errors through qualitative analysis 
(a semi-structured interview and thematic coding) and evaluated the users’ ability of identifying errors with text-to-speech through quantitative analysis. 
In addition, as a part of accessibility research, I designed and created a prototype of haptic wristbands that can indicate direction with the vibrations around a wrist. 
Through a user study with statistical analysis, we established a design of a haptic wristband that allows a blind user 
to trace a path or find a target on a surface based on the directional guidance.

### Publications
[Reviewing Speech Input with Audio: Differences between Blind and Sighted Users](/papers/TACCESS2020-speech.pdf)<br>
**Jonggi Hong**, Christine Vaing, Hernisa Kacorri, Leah Findlater. TACCESS 2020.

[Identifying Speech Input Errors Through Audio-Only Interaction](/papers/CHI2018-DictationErrorsAudioOnly.pdf)<br>
**Jonggi Hong**, Leah Findlater. CHI 2018.

[Correcting Errors in Speech Input During Non-visual Use](/papers/CHI2017Workshop_dictation.pdf)<br>
**Jonggi Hong**, Leah Findlater. CHI Workshop 2017.



<hr style="height:2px;border-width:0;color:gray;background-color:gray">


## Detecting of Misalignments Between Promotion Links and Landing Pages

<p align="center">
  <img src="/images/link_analysis.png" width="80%" alt="screenshots of an email and a landing page">
</p>
At Adobe Research, I developed a machine learning model that classifies the semantic relationship between a link and a landing page. 
Beyond detecting the “Page not found” error from the server, it analyzes the relationship to detect the landing pages with semantic problems such as outdated information, 
irrelevant information, and having unexpected additional steps. In this project, I collected and cleaned the data for machine learning. 
The classifiers are built and evaluated using SVM, Random Forest, and neural network. 
This project is a part of research to build a system that helps online marketers managing their emails with links to external web pages. 
This system is expected to help them to identify the misaligned links and resolve the problems in the links or landing pages quickly.

### Publication
[Identifying and Presenting Misalignments between Digital Messages and External Digital Content](https://www.freepatentsonline.com/y2020/0372399.html)<br>
Tak Yeon Lee, Jonggi Hong, Eunyee Koh. US Patent App. 16/419,676


<hr style="height:2px;border-width:0;color:gray;background-color:gray">


## Interacting with Wearable Devices

<p align="center">
  <img src="/images/Haptic_GI2016.png" width="80%" alt="components of a haptic wristband: motors, an elastic band, and 3D printed cases for motors on the elastic band.">
</p>
The wearable and mobile devices can enable novel interactions for people with disabilities. They can also enhance the interfaces of augmented reality applications and smart watches.

### Publications
[Evaluating Wrist-Based Haptic Feedback for Non-Visual Target Finding and Path Tracing on a 2D Surface](/papers/ASSETS2017-haptic.pdf)<br>
**Jonggi Hong**, Alisha Pradhan, Jon E. Froehlich, Leah Findlater. ASSETS 2017.

[The Cost of Turning Heads: A Comparison of a Head-Worn Display to a Smartphone for Supporting Persons With Aphasia in Conversation](/papers/ASSETS2016-AphasiaHMD.pdf)<br>
Kristin Williams, Karyn Moffatt, **Jonggi Hong**, Yasmeen Faroqi-Shah, Leah Findlater. ASSETS 2016

[Evaluating Angular Accuracy of Wrist-based Haptic Directional Guidance for Hand Movement](/papers/GI2016-haptic.pdf)<br>
**Jonggi Hong**, Lee Stearns, Tony Cheng, Jon E. Froehlich, David Ross, Leah Findlater. GI 2016.

[Comparison of Three QWERTY Keyboards for a Smartwatch](/papers/IWC_SplitBoard.pdf)<br>
**Jonggi Hong**, Seongkook Heo, Poika Isokoski, and Geehyuk Lee. IWC 2016.

[TouchRoller: A Touch-sensitive Cylindrical Input Device for GUI Manipulation of Interactive TVs](/papers/IWC-TouchRoller.pdf)<br>
**Jonggi Hong**, Hwan Kim, Woohun Lee, Geehyuk Lee. IWC 2015.

[SplitBoard: A Simple Split Soft Keyboard for Wristwatch-sized Touch Screens](/papers/CHI2015-SplitBoard.pdf)<br>
**Jonggi Hong**, Seongkook Heo, Poika Isokoski, Geehyuk Lee. CHI 2015.

[Smart Wristband: Touch-and-motion–tracking Wearable Input Device for Smart Glasses](/papers/HCII2014-smartwristband.pdf)<br>
Jooyeun Ham, **Jonggi Hong**, Youngkyoon Jang, Seung Hwan Ko, Woontack Woo. HCII 2014.

[TouchShield: A Virtual Control for Stable Grip of a Smartphone Using the Thumb](/papers/CHI2013-TouchShield.pdf)<br>
**Jonggi Hong**, Geehyuk Lee. CHI EA 2013.