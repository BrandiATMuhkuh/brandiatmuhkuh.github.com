---
layout: page
title: "My Little and Big Projects"
comments: true
sharing: true
footer: true
---
<section class="card">

I created this page as a portfolio in which you will see some of my interesting projects in my private and professional life. I designed it to showcase some of my work with different technologies.

All projects are sorted by date except the last part (**Little Projects**). Those projects are short weekend project. Just for fun.

</section>

<section class="card">
<a name="anchor002"></a>
# Figebot - Workout while working
[{% img shadowImg http://fuse.microsoft.com/content/img/fuse_logo.png %}](http://fuse.microsoft.com/)

During my time at the FUSE Labs (Microsoft Research) I developed with [Kati London (MSR)](http://www.katilondon.com/bio.html) and [Noah Liebman(NU)](https://noahliebman.net/) a two tier tool to persuade co-workers to do more (mico)exercises during work hours. The reason for that was that most societies move to a more and more rigid office type workplace which creates many long term health issues. The two tier were divided into a screen based notification system and a social robot (NAO) based notification system.

<iframe width="100%" height="315" src="//www.youtube.com/embed/aZkmNqpJCcM?rel=0" frameborder="0" allowfullscreen class="shadowImg"></iframe>

Before participants could use one of each systems, they hat to set their daily goals. We didn't want to impose preset goal for all employees. Depending on each own goal, one of our systems would reach out to them and provoke a micro exercise.
{% img shadowImg /images/projects/fidgebot4.jpg %}

After the participant is set up. Our system will use one of the following two methods. Participant one would get a screen based notification. We simply used a modern HTML5 notifications for that.
{% img shadowImg /images/projects/fidgebot5.png 250 %} For participants two, we would send a notification to NAO to her wake up. NAO would than walk to the participant and ask if she/he wants to do a short break with her (Yes NAO is female).

If the participants agrees NAO would start a random micro-excersice. In the following pictures NAO and the participants are dancing the [chicken dance](https://www.youtube.com/watch?v=4xmV5uHWNag). Always amuses Microsoft employees.
{% img shadowImg /images/projects/fidgebot2.gif 400 %}{% img shadowImg /images/projects/fidgebot3.gif 400 %}


**Project link(s):** [Working Out While Working](http://blog.fuselabs.org/post/97150732716/working-out-while-working), [Fidgebot by the Numbers](http://blog.fuselabs.org/post/97247581736/fidgebot-by-the-numbers), [Fidgebot: Robot Experience](http://blog.fuselabs.org/post/97308195741/fidgebot-robot-experience) <br />
**Project Presentation: ** https://mix.office.com/watch/1txuvzwh356d8 <br />

**Technologies Used**

* [Python](https://www.python.org/) Used as webserver as well as NAO script language
* [NAOqi](http://doc.aldebaran.com/2-1/naoqi/index.html) Is the SDK used to control [NAO](https://www.aldebaran.com/en/humanoid-robot/nao-robot) robots

</section>


<section class="card">
<a name="anchor001"></a>
# Quarto - from paper prototype to high fidelity laser cut
{% img shadowImg /images/projects/quarto3.jpg %}
About ten years a ago my mom introduced me to a board game called [Quarto](http://en.wikipedia.org/wiki/Quarto_%28board_game%29). At the time it was the most awarded game ever (That's what the package said ;) ). When moving to Vienna and later to Christchurch I lost track of this fabioulous strategy game. A couple of month ago I remembered again and tried to find it in local stores. But I couldn't. But since I was so excited to show it to my partner, I decided to just build it on my own.

Most game mechanics are not related to the actual graphics/fidelity/aesthetics of the game. So I decided I go for a simple paper prototype. As you can see in the image above, this prototype has everything needed for the game (**The game has 16 pieces. Each piece has 4 characteristics that makes it unique.**). After playing it for a while we realized some parts would not work out perfectly. Especially the size of the pieces. When you sit in the wrong angle it is very hard to see which part is bigger than the other.

{% img shadowImg /images/projects/quarto5.jpg 300 %}
{% img shadowImg /images/projects/quarto4.jpg 400 %}
After the game worked as expected, except the size problem we decided to create a high fidelity laser cut version (First board in the above image.). To solve the size problem we decided to exchange the different sizes with a spiral. For the colors we used two types of colored plastic and the board was made out of wood.

If you look carefully you will see that the finished game and the fresh game field have a different color. That is because we smoothed it with oil. That gives it a nice shiny color and makes it long lasting.

After playing a bit with the new hi-fi game we saw that some pieces looked similar when turned around. To make sure we always use the top side of the piece, we added a yellow dot at the back. **Happy Playing**.


** Technologies Used**

* [Inkscape](https://inkscape.org/en/) is an Open Source alternative to Adobe Illustrator. It's perfect for simple SVG shapes needed for the laser cutter
* **Laser cutter** is a high precision 2D cutting tool


** Resources **

* [quarto.svg](/images/projects/quarto.svg) is the SVG file to create your own game

</section>

<section class="card">
<a name="anchor1"></a>
# Robot Peer Pressure and Conformity Experiments
{% img shadowImg /images/projects/myNaoFriends.JPG %}
During my PhD at the [HITLabNZ](http://www.hitlabnz.org/index.php?option=com_jresearch&view=member&task=show&id=356&Itemid=253) (University of Canterbury, New Zealand) I will ask two main questions. **First, what is the most persuasive technique for robots to change human speech. Second, how can this change influence people's opinion.** To find and compare this techniques I use social science experiments as intellectual model. In my first experiment I recreated the famous [Asch](http://en.wikipedia.org/wiki/Asch_conformity_experiments) and [Sherif](http://en.wikipedia.org/wiki/Muzafer_Sherif) conformity experiments and extended them with regular and irregular words. The goal is to see if a group of social robots can create a conformity effect like humans. (*While writing this text, I was not done with collecting all data. The results will be added to this text as soon as I'm done with data collection.*) I believe it is important to understand how persuasive social robots can be and what this could mean for our social life. This would be especially of interest if most robots were developed by a hand full of companies and those companies could remotely change the robots behaviour. Mass media could/can not be used to change the opinion of humans since it misses the social interaction between media and consumer. Social robots on the other hand, could add exactly this missing link.


{% img shadowImg /images/projects/DSC_4179.JPG 600 %}
<br />

** Technologies Used**

* [Aldebaran NAO](http://www.aldebaran-robotics.com/en/) social robot
* [NAO api](https://community.aldebaran-robotics.com/doc/1-14/index.html) for remote controlling
* [Deployd](http://deployd.com/) as simple node server for user tracking

** Publications**

* [A peer pressure experiment: Recreation of the Asch conformity experiment with robots](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6942730&tag=1)
* [Participants converge to humans but not to humanoid robots in an English past tense formation task](http://www.hitlabnz.org/index.php/people?view=publication&task=show&id=1588)

</section>


<section class="card">
<a name="anchor2"></a>
# Rehabilitation Game
<iframe width="100%" height="315" src="//www.youtube.com/embed/rrZrV4t98H0?rel=0" frameborder="0" allowfullscreen class="shadowImg"></iframe>
For my master's thesis at the [Vienna Institute of Technology (HCI Group)](http://igw.tuwien.ac.at/hci/) I created a "Positive Impact Game as a Contribution to Movement Rehabilitation". When a person looses his/her, he/s does not just face a physical challange but also a psychological challenge. Most of the time engineers try to help participants by creating tools which focus only on the physical (engineering) challenges and leave out the person as human being with feelings. My approach was to set the psychological situation of the participant in the middle and build a rehabilitation game around the person. My project builds up on the "Virtual Reality Training for Upper Limb Prosthesis Patients" project developed by Vienna Institute of Technology (Interactive Media Systems Group) and Otto-Bock. Their project was a typical engineering approach which focused "only" on movement rehabilitation to limit the time until a person can start with rehabilitation.

Altogether rehabilitation in the case of a lost arm combines five main problems

1. Repeating Tasks are Boring
2. Prosthesis Production time
3. 6 Months for wound healing
4. psychological problems
5. psychological feedback

Task 1,2 and 3 were already solved by the previous team. My work was focused on point 4 and 5.

{% img shadowImg /images/projects/finalMapSituation.png 600 %}

To include the psychological problems in a game I tried to reflect the situation of the patient in the game. Since my game was built as a prototype it included 4 fixed situations: **death, help, create life, enjoy** (See figure above). The idea is that the patient is angry at the beginning. He/s just lost an arm. To get rid of the anger the patient can destroy trees and other surrounding objects (Attention: This approach is not suitable for everyone. For many people aggression makes the situation even worse). In the next step the participant can help burning trees by putting water on them. The idea is, that he/s feels "useful" again. This should help the patient to regain self-confidence. In the third step the participant can (pour flowers and trees) and they start to come a live. This should give her/him back the the confidence of creating something new on her/his own. The last step is about enjoyment. Event though a person lost an arm, should not mean he/s can not enjoy life anymore.


** Publications **

* [Positive Impact Game as a Contribution to Movement Rehabilitation](https://www.ims.tuwien.ac.at/publications/tuw-219779)


** Technologies Used**

* [Unity3D](http://unity3d.com/) was used as game engine
* [Open Tracker](http://studierstube.icg.tugraz.at/opentracker/) was used as tracking hardware

</section>


<section class="card">
<a name="anchor3"></a>
# SportMate - The Group Activity Wrist Band
{% img shadowImg /images/projects/prore2.png 300 %}
{% img shadowImg /images/projects/prore3.png 300 %}
<iframe width="100%" height="315" src="//www.youtube.com/embed/SjAfv6yWv_E?rel=0" frameborder="0" allowfullscreen class="shadowImg"></iframe>
<iframe width="100%" height="315" src="//www.youtube.com/embed/9VUYxXamAbg?rel=0" frameborder="0" allowfullscreen class="shadowImg"></iframe>
SportMate was a one year project in the last year of my master's study. The purpose of this project was to develop a prototype starting with research, expert interviews, cultural probes, educative probes, provocative probes, creating different scenarios, creating personal experience and finishing with a prototype. At the end of this paper we presented our work to industrial leaders.

The idea of SportMate was to motivate people to do more sport and to make them aware of how much sport they already did. To do so we created a wrist band which shows how much sport one person -or the group he/s belongs to- did in one week. The goal is that all people in one group make enough sport to reach the group goal. Group goals are combinations of individual goals. Only if all people reach their own individual goal the group goal is fulfilled. By indicating on the band that one person in the group makes sport, all other people should feel guilty not doing sport. It can be seen as a type of peer pressure for a good cause.  

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
<a name="anchor4"></a>
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
<a name="anchor5"></a>
# Heute App
{% img shadowImg /images/projects/heute.png 300 %}
Heute" is Austria's biggest news paper. My job was to integrate the epaper system and maintain the app.

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
<a name="anchor6"></a>
# ÖAMTC Android-App
{% img shadowImg /images/projects/oeamtc.png 300 %}
{% img shadowImg /images/projects/oeamtc2.png 300 %}
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
<a name="anchor7"></a>
# Fetal Movements
<iframe src="https://docs.google.com/presentation/d/1DQKcvNDja9XUM54EY9cwV6gZtf2BuVBeHUQZM6ikVV4/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="800px" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"  class="shadowImg"></iframe>
At the end of my master's degree, I made a project for a class called "Beyond the Desktop and Building Interface and Interaction Technologies" which was a mobile hardware prototype. Coincidentally a friend of mine who was attending this course with me got pregnant. But she had a problem. Her partner was in Norway at that time when she was in Vienna. So we decided to create a tool to transfer the movements of the baby in her belly to her partner in Norway. This was the birth of the fetal movement prototype.



**Team Members:** 4 <br />
**Affiliation:** Master in Media Informatics, Vienna Institute of Technology<br />

** Technologies Used**

* Android as twitter bridge
* Twitter as communication tool
* Arduino Lilipad with force sensitive resistors to measure the babies movements
* Bluetooth for communication with the belt

** Publications**

* [Can you feel this - Sharing fetal movements over a distance](https://docs.google.com/file/d/0BydzO1mEr3Hld3pXNWluXzR5UlU)

</section>

<section class="card">
<a name="anchor8"></a>
# Tag A Price
{% img shadowImg /images/projects/screencapture-beta-tagaprice-org2.png %}
{% img shadowImg /images/projects/screencapture-beta-tagaprice-org3.png %}
**In one sentence:** TagAPrice is a Consumer-Generated Location-Aware Price Comparison Service

This project has been created as my bachelor practicum. The idea of TagAPrice is to make the grocery market fully transparent. We buy groceries almost every day but we have no simple solution to find out where we get the cheapest product. TagAPrice tries to help to solve the problem.

The project is divided into three main parts. First a store database. Second a product database. And third, a price database to combine the other two datasets. Right now, TagAPrice is in sleep mode. That means we have no time to develop or add more data. We tried to find investors but three years ago it was very hard to find someone who wants to support such a project. Right now, I'm working only on one part of the platform. I want to create a mobile app that uses a receipt as input and extracts all products and prices from it. As soon as this is done we can restart to integrate the data into the full project.

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
<a name="anchor9"></a>
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
<a name="anchor10"></a>
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
<a name="anchor11"></a>
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
<a name="anchor12"></a>
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
<a name="anchor13"></a>
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
<a name="anchor14"></a>
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
<a name="anchor15"></a>
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
<a name="anchor16"></a>
# Little Projects

## Twitter pos/neg stock analyser
I want to find out if the positive and negative news about a company and companies products on twitter reflect the stock market. If yes, is twitter faster or slower than the real stock movements.

The source can be found on my [github account](https://github.com/BrandiATMuhkuh/twitter-stock-predicter). But the project is in a very early stage.

**Technologies Used**

* [NodeJs](nodejs.org) as easy programming environment. Awesome for prototyping
* [Twitter node package](https://npmjs.org/package/twitter) to for twitter streaming
* [Twitter Streaming API](https://dev.twitter.com/docs/streaming-apis) for realtime streaming.

## All Foursquare location on one Google Map
{% img shadowImg /images/projects/foresquareSuperMap.png %}
In October 2013 someone posted on [Hackernews](https://news.ycombinator.com/item?id=6513074) a link to a ~1Gb [Fouresquare](https://foursquare.com/) dataset. Since I enjoy working with geo-data, I though why not posting all foursquare locations on google map, using the google maps cluster library.

At the end I added 336792 unique points on google map. It took about 1 minute to read the data from the database (~500Mb) using websockets but about 10 minutes to visualise them. As soon as the cluster library reaches around 1000 objects it became much slower.

**Technologies Used**

* Websockets for data transfair
* [Deployd](http://www.deployd.com/) as simple nodejs server
* Google Maps Api
* [Google Maps Ultility Library](https://code.google.com/p/google-maps-utility-library-v3/) for clustering

## Talk with a chatbot
{% img shadowImg /images/projects/robot.jpg 300 %}
This is a prove of concept where I only use client side HTML5 tools so you can use your voice to chat with a chatbot. It should run with every modern browser, but not on mobile browsers (Mobile browsers have a security feature for recording a voice). You can try it [here](https://googledrive.com/host/0BydzO1mEr3HlSEpOdFJNQVpzZms/index.html)

**Technologies Used**

* [personalityforge](http://www.personalityforge.com/) API used as chatbot brain
* [jsonp.jit.su](jsonp.jit.su) used as JSONP proxy
* [Google Translate Hack](thttp://translate.google.com/translate_tts?tl=en&q=This is awesome) used as text to speech tool
* [HTML5 Voice Recognition](http://updates.html5rocks.com/2013/01/Voice-Driven-Web-Apps-Introduction-to-the-Web-Speech-API) used as Speech to Text
* [Google App Script](https://developers.google.com/apps-script/) used as backend service
* Google Drive used as server

</section>
