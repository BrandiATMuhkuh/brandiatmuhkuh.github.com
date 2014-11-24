---
layout: page
title: "My Little and Big Projects"
comments: true
sharing: true
footer: true
---
<section class="card">
This page is some kind of portfolio in which you see all interesting projects in my private and professional life. It should give you a bit of a feeling what type of person I am and it should also give you a feeling about my experience with diffent technologies. 

All projects are sorted by date except the last part (**Little Projects**). Those projects are short weekend project. Just for fun.

</section>

<section class="card">
# Robot Peer Pressure and Conformity Experiments
{% img shadowImg /images/projects/myNaoFriends.JPG %}
During my PhD at the [HITLabNZ](http://www.hitlabnz.org/index.php?option=com_jresearch&view=member&task=show&id=356&Itemid=253) (University of Canterbury, New Zealand) I will ask two main questions. **First, what is the most persuasive technique for robots to change human speech. Second, how can this change influence the peoples opinion.** To find and compare this techniques I use social science experiments as intellectual model. In my first experiment I recreate the famous [Asch](http://en.wikipedia.org/wiki/Asch_conformity_experiments) and [Sherif](http://en.wikipedia.org/wiki/Muzafer_Sherif) conformity experiments and extend them with regular and irregular words. The goal is to see if a group of social robots can create a conformity effect like humans. (*While writing this text, I was not done with collecting all data. The results will be added to this text as soon as I'm done with data collection.*) I believe it is important to understand how persuasive social robots can be and what this could mean for our social life. This would be especially from interest if most robots were developed by a hand full of companies and those companies could remotely change the robots behaviour. Mass media could/can not be used to change the opinion of humans since it misses the social interaction between media and consumer. Social robots on the other hand, could add exactly this missing link. 


{% img shadowImg /images/projects/DSC_4179.JPG 600 %}
<br />

** Technologies Used**

* [Aldebaran NAO](http://www.aldebaran-robotics.com/en/) social robot
* [NAO api](https://community.aldebaran-robotics.com/doc/1-14/index.html) for remote controlling 
* [Deployd](http://deployd.com/) as simple node server for user tracking

</section>


<section class="card">
# Rehabilitation Game
<iframe width="100%" height="315" src="//www.youtube.com/embed/rrZrV4t98H0?rel=0" frameborder="0" allowfullscreen class="shadowImg"></iframe>
For my master thesis at the [Vienna Institute of Technology (HCI Group)](http://igw.tuwien.ac.at/hci/) I created a "Positive Impact Game as a Contribution to Movement Rehabilitation". When a person looses its arm it is not only a physical challenge but also a psychological challenge. Most of the time engineers try to help participants by create tools which focus only on the physical (engineering) challenges but leave out the person as human being with feelings. My approach was to set the psychological situation of the participant in the middle and build a rehabilitation game around the person. My project builds up on the "Virtual Reality Training for Upper Limb Prosthesis Patients" project developed by Vienna Institute of Technology (Interactive Media Systems Group) and Otto-Bock. Their project was a typical engineering approach which focused "only" on movement rehabilitation to limit the time until a person can start with rehabilitation.

Altogether rehabilitation in the case of a lost arm combines five main problems

1. Repeating Tasks are Boring
2. Prosthesis Production time
3. 6 Month for wound healing
4. psychological problems 
5. psychological feedback

Task 1,2 and 3 where already solved by the previous team. My work was focused on point 4 and 5. 

{% img shadowImg /images/projects/finalMapSituation.png 600 %}

To include the psychological problems in a game I tried to reflect the situation of the patient in the game. Since my game was built as a prototype it included 4 fixed situations: **death, help, create life, enjoy** (See figure above). The idea is that the patient is angry at the beginning. She/He just lost an arm. To get rid of the anger the patient can destroy trees and other surrounding objects (Attention: This approach is not suitable for everyone. For many people aggression makes the situation even worse). In the next step the participant can help burning trees by putting water on them. The idea is, that she/he feels "useful" again. This should to regain self-confidence. In the third step the participant can pour flowers and trees and they start to come a live. This should give her/him back the the confidence of creating something new on her/him own. The last step is about enjoyment. Event though a person lost an arm, should not mean she/he can not enjoy live anymore. 



Link to thesis: https://www.ims.tuwien.ac.at/publications/tuw-219779


** Technologies Used**

* [Unity3D](http://unity3d.com/) was used as game engine
* [Open Tracker](http://studierstube.icg.tugraz.at/opentracker/) was used as tracking hardware

</section>


<section class="card">
# SportMate - The Group Activity Wrist Band
{% img shadowImg /images/projects/prore2.png 300 %}
{% img shadowImg /images/projects/prore3.png 300 %}
<iframe width="100%" height="315" src="//www.youtube.com/embed/SjAfv6yWv_E?rel=0" frameborder="0" allowfullscreen class="shadowImg"></iframe>
<iframe width="100%" height="315" src="//www.youtube.com/embed/9VUYxXamAbg?rel=0" frameborder="0" allowfullscreen class="shadowImg"></iframe>
SportMate was a one year project in the last year of my master study. The purpose of this project was to develop a prototype starting with research, expert interviews, cultural probes, educative probes, provocative probe, creating different scenarios, creating personal and finishing with prototype. At the end of this paper we presented our work to industrial leaders. 

The idea of SportMate was to motivate people to more sport and to make them aware of how much sport they already did. To do so we created a wrist band which shows how much sport one person did in one week and how much sport his/her group, which this person joint, did in the same week. The goal is that all people in one group make enough sport to reach the group goal. Group goals are combinations of individual goals. Only if all people reach their own individual goal the group goal is fulfilled. By indicating on the band that one person in the group makes sport, all other people should feel guilty not making sport. It can be seen as type of peer pressure for a good cause.  

**My Job:** UX-Designer, Tester <br />
**Team Members:** 5 <br />
**My Age:** 24-25 <br />

** Technologies Used**

* Android for calculation and visualisation
* Arduino Lilipad for the wrist band
* Bluetooth for communication
* PostgreSQL as backend

</section>

<section class="card">
# HTML5 Epaper
{% img shadowImg /images/projects/screencapture-epaper-heute-at.png %}

{% img shadowImg /images/projects/screencapture-epaper-heute-at2.png %}

For many years Flash was the dominating technology for ebook and epaper readers. But since Flash was not working on iOS devices and it got deprecated in Android 4.x it was time for a HTML5 version. The HTML5 version runs now on all modern platforms and is capable of finger and mouse gestures. The biggest free newspaper in Austria is using our implementation. Check it out: http://epaper.heute.at . 

**Project Link:** <http://epaper.heute.at/><br />
**Company:** [openresearch](http://openresearch.com) <br />
**My Job:** HTML5 Developer <br />
**Team Members:** 8 <br />
**My Age:** 24 <br />

**Technologies Used**

* [Emberjs](http://emberjs.com/) as MVC framework
* Ember-Data for data persistence
* [Nodejs](http://nodejs.org/) 
* [Apache Cordova](http://cordova.apache.org/)

</section>


<section class="card">
# Heute App
{% img shadowImg /images/projects/heute.webp 300 %}
"Heute" is Austrias biggest news papers. My job was to integrate the epaper system and maintain the app. 

**Google Play Link:** <https://play.google.com/store/apps/details?id=at.heute.android/><br />
**Company:** [openresearch](http://openresearch.com) <br />
**My Job:** Android Developer, Technical Support<br />
**Team Members:** 7 <br />
**My Age:** 24 <br />

**Technologies Used**

* Android 
* JSON as communication 

</section>

<section class="card">
# ÖAMTC Android-App
{% img shadowImg /images/projects/oeamtc.webp 300 %}
{% img shadowImg /images/projects/oeamtc2.webp 300 %}
ÖAMTC is Austria's biggest car community. The Android application includes a gas comparison system, community stations and other useful features for drivers. 

**Google Play Link:** <https://play.google.com/store/apps/details?id=at.oeamtc.android><br />
**Company:** [openresearch](http://openresearch.com) <br />
**My Job:** UI, Software and Cluster Algorithm Developer<br />
**Team Members:** 7 <br />
**My Age:** 24 <br />

**Technologies Used**

* Android 
* Google Maps
* JSON as communication 

</section>

<section class="card">
# Fetal Movements
<iframe src="https://docs.google.com/presentation/d/1DQKcvNDja9XUM54EY9cwV6gZtf2BuVBeHUQZM6ikVV4/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="800px" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"  class="shadowImg"></iframe>
At the end of my master I had to make for a class called "Beyond the Desktop and Building Interface and Interaction Technologies" a mobile hardware prototype. Coincidentally a friend of mine who was attending this course with me got pregnant. But she had a problem. Her partner was in Norway and she was in Vienna. So we decided to create a tool to transfer the movements of the baby in her belly to the partner in Norway. This was the birth of the fetal movement prototype.

Here is a link to the paper: [Can you feel this - Sharing fetal movements over a distance](https://docs.google.com/file/d/0BydzO1mEr3Hld3pXNWluXzR5UlU)

**Team Members:** 4 <br />
**Affiliation:** Master in Media Informatics, Vienna Institute of Technology<br />

** Technologies Used**

* Android as twitter bridge
* Twitter as communication tool
* Arduino Lilipad with force sensitive resistors to measure the babies movements
* Bluetooth for communication with the belt

</section>

<section class="card">
# Tag A Price
{% img shadowImg /images/projects/screencapture-beta-tagaprice-org2.png %}
{% img shadowImg /images/projects/screencapture-beta-tagaprice-org3.png %}
**In one sentence:** TagAPrice is a Consumer-Generated Location-Aware Price Comparison Service

This project has been created as my bachelor practicum. The idea of TagAPrice is to make the grocery market fully transparent. We buy groceries almost every day but we have no simple solution to find out where we get the cheapest product. TagAPrice tries to help to solve the problem. 

The project is divided into three main parts. First a store database. Second a product database. And third, a price database to combine the other two datasets. Right now, TagAPrice is in sleep mode. That means we have no time to develop or add more data. We tried to find investors but three years ago it was very hard to find someone who wants to support such a project. Right now, I'm working on only one part of the platform. I want to create a mobile app that uses a receipt as input and extracts all products and prices from it. As soon as this is done we can restart to integrate the data into the full project. 

**My Job:** Project Manager, UX-Designer <br />
**Team Members:** 7 <br />
**My Age:** 23-24 <br />

**Technologies Used**

* [GWT (Google Web Toolkit)](http://www.gwtproject.org/) used as front and backend technology
* GWT-RPC as communication protocol
* [CouchDB](http://couchdb.apache.org/) as database
* [Elasticsearch](http://www.elasticsearch.org/) as communication layer

</section>

<section class="card">
# WERistIN (v2)
{% img shadowImg /images/projects/screencapture-weristin-com.png %}
{% img shadowImg /images/projects/screencapture-weristin-com2.png %}
WERistIN is a local advertising service. It is divided into a web version and a stand alone version. The stand alone version is integrated into tourist-terminals which are sold in many cities is Austria. This Version (V2) is based on GoogleMap and we switched from a list concept (WERistIN V1) to a touchscreen map concept.  

**My Job:** CEO, Lead Developer, Project Manager, Sale <br />
**Team Members:** 3 <br />
**My Age:** 22-23 <br />

**Technologies Used**

* GWT (Google Web Toolkit), JAVA for frontend
* JSON as communication protocol
* PHP in the backend
* MySQL for data storage

</section>

<section class="card">
# GeoSearch
{% img shadowImg /images/projects/screencapture-geosearch-fakeroot-at.png %}
GeoSearch is a Map-Crawler. Compared to Web-Crawler like google, GeoSearch crawls only Maps. The intention is to have a search engine for location based information. 

**My Job:** Project Manager <br />
**Team Members:** 5 <br />
**My Age:** 22  <br />

**Technologies Used**

* GWT (Google Web Toolkit), JAVA for frontend
* GWT-RPC as communication layer
* Java Servlets as backend
* PostgreSQL for data storage

</section>

<section class="card">
# WERistIN (V1)
WERistIN is a local advertising service. It is divided into a web version and a stand alone version. The stand alone version is integrated into tourist-terminals which are sold in many cities is Austria. 

WERistIN was the start of my first company I founded with my brother and this wife. The system itself builds on the "High scalable CMS" I created for a customer but we used a different business model. Our business model was built on reciprocity and pro accounts. Community like a football club could get access to our system for free but they had to make advertisement for us. And companies had to pay via pro account. 

**My Job:** Lead Developer, Project Manager, Sale <br />
**Team Members:** 3 <br />
**My Age:** 18-20 <br />

**Technologies Used**

* PHP as frontend and backend
* MySQL as data storage

</section>

<section class="card">
# Created own CMS
{% img shadowImg /images/projects/screencapture-www-ortner-siegl-at-index-php.png%}
To have some intellectual challenges while being in the army (It is compulsory in Austria) I created a content management system to run future project on it. I included several plugins and was used by many countries I sold it to. 

At the end of the production it was used by: http://www.ortner-siegl.at, http://flyreini.at, http://www.stoecher.at, http://www.gasthauszurhoftaverne.at

**My Job:** Project Manager, Sales <br />
**Team Members:** 2 <br />
**My Age:** 18-22 <br />

**Technologies Used**

* PHP as frontend and backend
* MySQL as data storage

**Plugin list**

* Webstore
* Feedback System
* Gallery
* Newsletter Support

</section>

<section class="card">
# In-House ERP System for AKD-Wohnen
In-House ERP System for AKD-Wohnen based on qualitative methods for the design. Between Army and University I had six month time to work in a interior design company to optimize their process. My work was to analyse the company, using a HCI approach and develop a ERP system for them. 

**My Job:** Project Manager, Developer <br />
**Team Members:** 8 <br />
**My Age:** 20 <br />

**Technologies Used**

* PHP as frontend and backend
* MySQL as data storage

</section>

<section class="card">
# Samsung Smart TV Video Service App
<iframe width="100%" height="315" src="//www.youtube.com/embed/odNC_Y9FL_8?rel=0" frameborder="0" allowfullscreen class="shadowImg"></iframe>
This was a project where I collaborated with Samsung Austria. The project is a responsive web design framework for video platforms to make videos available on 10-Foot-UI, Smartphones, Tablets and Desktops. To be able to integrate the software into closed Smart-TVs the framework includes wrapper for Smart-TVs like Samsung-Smart-TV. 

Documentation(German): [Here on google drive](https://drive.google.com/file/d/0BydzO1mEr3HlN2dlWl9iNW4xeW8/edit?usp=sharing)

**My Job:** Project Manager, UX Designer, Software Developer <br />
**Team Members:** 3 <br />
**My Age:** 25 <br />

**Technologies Used**

* Websockets
* Samsung SmartTV API
* PostgreSQL or CouchDB
* [Youtube API](https://developers.google.com/youtube/)

</section>

<section class="card">
# High scalable CMS
The software was created to manage hundreds of different websites on high scalable server system. On the peak of the service more than 300 pages ran on the same system.  

**My Job:** Project Manager <br />
**Team Members:** 4 <br />
**My Age:** 17 <br />

**Technologies Used**

* PHP as frontend and backend
* MySQL as data storage

</section>

<section class="card">
# Little Projects

## Twitter pos/neg stock analyser
I want to find out if the positive and negative news about a company and a companies products on twitter reflect the stock market. If yes, is twitter faster or slower than the real stock movements. 

The source can be found on my [github account](https://github.com/BrandiATMuhkuh/twitter-stock-predicter). But the project is in a very early stage. 

**Technologies Used**

* [NodeJs](nodejs.org) as easy programming environment. Awesome for prototyping
* [Twitter node package](https://npmjs.org/package/twitter) to for twitter streaming
* [Twitter Streaming API](https://dev.twitter.com/docs/streaming-apis) for realtime streaming. 

## All Foursquare location on one Google Map
{% img shadowImg /images/projects/foresquareSuperMap.png %}
In October 2013 someone posted on [Hackernews](https://news.ycombinator.com/item?id=6513074) a link to a ~1Gb [Fouresquare](https://foursquare.com/) dataset. Since I enjoy a lot working with geo-data, I though why not posting all foursquare locations on a google map, using the google maps cluster library. 

At the end I added 336792 unique points on a google map. It takes about 1 minute to read the data from the database (~500Mb) using websockets but about 10 minutes to visualise them. As soon as the cluster library reaches around 1000 objects it becomes clearly slower. 

**Technologies Used**

* Websockets for data transfair
* [Deployd](http://www.deployd.com/) as simple nodejs server
* Google Maps Api
* [Google Maps Ultility Library](https://code.google.com/p/google-maps-utility-library-v3/) for clustering

## Talk with a chatbot
{% img shadowImg /images/projects/robot.jpg 300 %}
This is a prove of concept where I use only client side HTML5 tools so you can use your voice to chat with a chatbot. It should run with every modern browser, but not on mobile browsers (Mobile browser have a security feature for recording a voice). You can try it [here](https://googledrive.com/host/0BydzO1mEr3HlSEpOdFJNQVpzZms/index.html)

**Technologies Used**

* [personalityforge](http://www.personalityforge.com/) API used as chatbot brain 
* [jsonp.jit.su](jsonp.jit.su) used as JSONP proxy
* [Google Translate Hack](thttp://translate.google.com/translate_tts?tl=en&q=This is awesome) used as text to speech tool
* [HTML5 Voice Recognition](http://updates.html5rocks.com/2013/01/Voice-Driven-Web-Apps-Introduction-to-the-Web-Speech-API) used as Speech to Text
* [Google App Script](https://developers.google.com/apps-script/) used as backend service
* Google Drive used as server

</section>