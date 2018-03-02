---
layout: page
title: Publications of Darshan Santani
permalink: /publications/
---

### Venues in Social Media: Examining Ambiance Perception Through Scene Semantics ###

<p class="puba"> Yassir Benkhedda, Darshan Santani, Daniel Gatica-Perez | <span class="pubv">ACM MM 2017</span> </p>

In this research, we address the question of what visual cues, including scene objects and demographic attributes, contribute to the automatic inference of perceived ambiance in social media venues. We first use a state-of-art, deep scene semantic parsing method and a face attribute extractor to understand how different cues present in a scene relate to human perception of ambiance on Foursquare images of social venues. We then analyze correlational links between visual cues and thirteen ambiance variables, as well as the ability of the semantic attributes to automatically infer place ambiance. We study the effect of the type and amount of image data used for learning, and compare regression results to previous work, showing that the proposed approach results in marginal-to-moderate performance increase for up to ten of the ambiance dimensions, depending on the corpus. [**PDF**]({{ site.baseurl }}/assets/papers/acm-mm-17.pdf)

<img src="../assets/images/acm-mm-17.png" width="700" height="260" hspace="35" />

---

### InnerView: Learning Place Ambiance from Social Media Images ###

<span class="puba"> Darshan Santani, Rui Hu, Daniel Gatica-Perez | <span class="pubv">ACM MM 2016</span> </span>

In this paper, we build upon our [earlier work]({{ site.baseurl }}/assets/papers/acm-mm-15.pdf) on characterizing ambiance of indoor places. We present a methodology to automatically infer impressions of place ambiance, using generic deep learning features extracted from images publicly shared on Foursquare. We base our methodology on a corpus of over 45,000 images from 300 popular places in six cities. Our results indicate the feasibility to automatically infer place ambiance with a maximum R<sup>2</sup> of 0.53 using features extracted from a pre-trained convolutional neural network. We found that deep learning features consistently outperformed individual and combinations of several low-level image features (including Color, GIST, HOG and LBP) to infer all the studied ambiance dimensions. Our work constitutes a first study to automatically infer ambiance impressions of indoor places from deep features learned from images shared on social media. [**PDF**]({{ site.baseurl }}/assets/papers/acm-mm-16.pdf)

---

### The Night is Young: Urban Crowdsourcing of Nightlife Patterns ###

<span class="puba"> D. Santani, J-I. Biel, F. Labhart, J. Truong, S. Landolt, E. Kuntsche, D. Gatica-Perez | <span class="pubv">UbiComp 2016</span> </span>

<div style="float: left">
	<img src="http://idiap.ch/~dsantani/assets/images/ubicomp-16.jpg" width="260" height="210" hspace="0" />
</div>

This work outlines the design and implementation of a large-scale mobile crowdsensing study (called [Youth@Night](https://www.youth-night.ch/)) to capture and examine the nightlife patterns and behavior of young people in two cities of Switzerland. Using smartphones, we conducted an "in-the-wild" study with more than 200 participants over a period of three months to capture in-situ data on places, social context and nightlife activities. During the study, we also asked participants to record mobile videos capturing the ambiance of visited places. The study resulted in a total of 1,394 unique place visits and 843 videos that spread across diverse place categories (including personal homes and public parks), social and ambiance variables. Using the video dataset, we conducted a computational analysis to measure the extent to which automatically extracted loudness and brightness of places represent the crowdsourced annotations by both in-situ participants and external online observers. [**PDF**]({{ site.baseurl }}/assets/papers/ubicomp-16.pdf) \|\| [**Slides**](http://www.slideshare.net/dsantani/the-night-is-young-urban-crowdsourcing-of-nightlife-patterns)

---

### SenseCityVity: Mobile Crowdsourcing, Urban Awareness, and Collective Action in Mexico ###

<span class="puba"> S. Ruiz-Correa, D. Santani, B. R. Salazar, I. Ruiz-Correa, F. A. Rendon-Huerta, C. O. Carrillo, B. C. S. Mexicano, A. H. A. Garcia, R. H. Beltran, D. Gatica-Perez | <span class="pubv">IEEE Pervasive Computing 2017</span> </span>

<div style="float: left">
	<img src="../assets/images/sensecityvity.jpg" width="280" height="280" hspace="0" />
</div>

This work describes SenseCityVity, an approach to engage and support youth of a city in Mexico to investigate, document,and reflect upon urban problems though mobile crowdsourcing. SenseCityVity focused on the development of a mobile crowdsourcing platform; the deployment of an Urban Data Challenge, co-designed by our research team and actors to collect geo-localized images, audio and video; and the analysis, appropriation, and creative use of the collected data for community reflection and artistic creation. Our approach integrates mobile technology with community practices involving a large population of young people for urban engagement. The collective action generated a new multimedia data set that is rich in content and is enabling a number of studies towards the understanding of the urban landscape of cities in the Global South. [**PDF**]({{ site.baseurl }}/assets/papers/pervasive-16.pdf)

---

### Looking at Cities in Mexico with Crowds ###

<p class="puba"> Darshan Santani, Salvador Ruiz-Correa, Daniel Gatica-Perez | <span class="pubv">ACM DEV 2015</span> </p>

<!--
<div style="float: left">
	<img src="../assets/images/acm-dev-15.jpg" width="280" height="250" hspace="0" />
</div>
-->

We conducted a study to examine urban perceptions of three cities in central Mexico (Guanajuato, Leon and Silao), which integrated a mobile crowdsourcing framework to collect geo-localized images of urban environments by a local youth community, and an online crowdsourcing platform to gather impressions of urban environments along twelve physical and psychological dimensions. Our study resulted in a collection of 7,000 geo-localized images containing outdoor scenes and views of each city’s built environment, including touristic, historical, and residential neighbourhoods; and 156,000 individual judgments from MTurk. Statistical analyses showed that outdoor environments can be reliably assessed with respect to most urban dimensions by the observers of crowdsourced images. Finally, we investigated whether the perceptions of urban environments vary across different times of the day and found that places in the evening are perceived as less happy, pleasant and preserved, when compared to the same place in the morning. [**PDF**]({{ site.baseurl }}/assets/papers/acm-dev-15.pdf) \|\| [**Tech4Dev Poster**]({{ site.baseurl }}/assets/papers/tech4dev-16-poster.pdf)

<img src="../assets/images/city-image-corpus.png" width="700" height="260" hspace="35" />

---

### Loud and Trendy: Crowdsourcing Impressions of Social Ambiance in Popular Indoor Urban Places ###

<p class="puba"> Darshan Santani, Daniel Gatica-Perez | <span class="pubv">ACM MM 2015</span> </p>

<div style="float: left">
 <img src="../assets/images/acm-mm-15.jpg" width="250" height="250" hspace="0" />
</div>
We conducted a study to examine how images collected from social media can be used for the crowdsourced characterization of indoor ambiance impressions in popular urban places. We designed a crowdsourcing framework to understand suitability of images as data source to convey place ambiance, to examine what type of images are most suitable to describe ambiance, and to assess how people perceive places socially from the perspective of ambiance along 13 dimensions. Our study is based on 50,000 Foursquare images collected from 300 popular places across six cities worldwide. We showed that reliable estimates of ambiance can be obtained for several of the dimensions and most aggregate impressions of ambiance are similar across popular places in all studied cities. [**PDF**]({{ site.baseurl }}/assets/papers/acm-mm-15.pdf) \|\| [**Slides**](http://www.slideshare.net/dsantani/loud-and-trendy-crowdsourcing-impressions-of-social-ambiance-in-popular-indoor-urban-places)

---

### CommuniSense: Crowdsourcing Road Hazards in Nairobi ###

<p class="puba"> Darshan Santani, Jidraph Njuguna, Tierra Bills, Aisha W. Bryant, Reginald Bryant, Jonathan Ledgard, Daniel Gatica-Perez | <span class="pubv">MobileHCI 2015</span> </p>

Nairobi is one of the fastest growing metropolitan cities and a major business and technology powerhouse in Africa. However, Nairobi currently lacks monitoring technologies to obtain reliable data on traffic and road infrastructure conditions. In this work, we investigated the use of mobile crowdsourcing as means to gather and document Nairobi’s road quality information (potholes and speed-bumps). We first presented the key findings of a city-wide road quality survey about the perception of existing road quality conditions in Nairobi. Based on the survey’s findings, we then developed a mobile crowdsourcing application, called CommuniSense, to locate, describe, and photograph road hazards; and further we tested our application through a two-week field study. Moreover, we proposed to use online crowdsourcing to verify whether submitted reports indeed depict road hazards. [**PDF**]({{ site.baseurl }}/assets/papers/mobilehci-15.pdf) \|\| [**Slides**](http://www.slideshare.net/dsantani/communisense-crowdsourcing-road-hazards-in-nairobi) \|\| [**EPFL Press**](http://actu.epfl.ch/news/an-app-to-steer-clear-of-kenya-s-road-hazards/)

<img src="../assets/images/mobilehci-15.jpg" width="650" height="400" hspace="50" />

---

### #-grams: Twitter Pulse from Hashtag Co-Occurrence Networks ###

<p class="puba">Darshan Santani, Daniel Gatica-Perez |
<span class="pubv"> ACM Web Science Data Visualization Challenge 2014</span> </p>

In this work, we designed a visualization to understand and explore the hashtag co-occurrence dynamics on four eventful days in November 2012. The visualization highlights the utility of Twitter as a medium to capture global and local events via event-specific ephemeral hashtags, while at the same time the visualization tracks the ubiquity of non-ephemeral hashtags (e.g.,news, games, music, etc.) on each selected day. <span class="label-default"> Best Student Visualization Award </span> [**Viz**]({{ site.baseurl }}/assets/papers/websci-14-viz.pdf) \|\| [**Idiap Press**](http://www.idiap.ch/scientific-research/news/darshan-santani-wins-best-student-entry-award-at-webscience-data-visualization-challenge-2014) 

<img src="../assets/images/websci-14.png" width="750" height="280" hspace="10"/>

---

### The Young and the City: Crowdsourcing Urban Awareness in a Developing Country ###

<p class="puba"> Salvador Ruiz-Correa, Darshan Santani, Daniel Gatica-Perez | <span class="pubv">Urb-IoT 2014</span> </p>

We presented a crowdsourcing study that studied impressions of urban spaces by young inhabitants in Guanajuato, Mexico. Our goal was to obtain collective perceptions from the local inhabitants of the city, and more specifically youth (16-18 year-old) about issues like danger, accessibility, and dirtiness. We collected over 9,000 judgments for 102 photos of outdoor urban spaces in Guanajuato. We presented reliability and response analyses and demonstrated how local youth can provide relevant urban insights in a crowdsourcing setting. [**PDF**]({{ site.baseurl }}/assets/papers/urb-iot-14.pdf)

---

### Speaking Swiss: Languages and Venues in Foursquare ###

<p class="puba"> Darshan Santani, Daniel Gatica-Perez | <span class="pubv">ACM MM 2013</span> </p>

<div style="float: left">
	<img src="../assets/images/acm-mm-13.jpg" width="280" height="210" hspace="0" />
</div>

In this work, we examine a basic facet of multiculturalism through the lens of language use across multiple cities in Switzerland. Using data obtained from Foursquare over 330 days, we presented a descriptive analysis of linguistic differences and similarities across five urban agglomerations in Switzerland. English is the dominant language amongst the majority of Foursquare users, and global cities show a larger proportion of English usage in comparison to more local cities. Another finding was that the relative rankings of secondary languages in different cantons (e.g, French in German-speaking Bern) as per national census data matched Foursquare's trends. While obviously Foursquare users do not represent a fair sample of the Swiss population, our findings suggested the potential of Foursquare to complement census data to monitor cultural trends in urban settings. We believe that these results can be equally appealing to other contemporary multicultural nations. [**PDF**]({{ site.baseurl }}/assets/papers/acm-mm-13.pdf) \|\| [**Poster**]({{ site.baseurl }}/assets/papers/acm-mm-poster-13.pdf) \|\| [**Local Press**](http://www.idiap.ch/scientific-research/news/social-media-switzerland-writes-in-english)

---

### Revisiting the Generality of the Rank-based Human Mobility Model ###

<p class="puba"> Darshan Santani, Daniel Gatica-Perez | <span class="pubv">PURBA Workshop at Ubicomp 2013</span> </p>

In this paper, using a statistical methodology, we found that a rank-distance distribution, which in recent research has been suggested to be a universal mobility law across cultural, demographic and national boundaries, does not follow a power-law distribution as originally claimed. Using a large-scale dataset obtained from Foursquare in Switzerland and New York City, we showed that place transitions can be better explained using a log-normal and power-law with exponential cutoff model. Our study suggested that urban mobility patterns are more nuanced than previously reported and that goodness-of-fit tests need to be done in view of the generality of human mobility models. [**PDF**]({{ site.baseurl }}/assets/papers/purba-13.pdf) \|\| [**Slides**](http://www.slideshare.net/dsantani/purba-13-26570355) \|\| [**Supplementary Material**]({{ site.baseurl }}/assets/papers/purba-13-suppl.pdf)

---

### Understanding and Improving a GPS-based Taxi System ###

<p class="puba"> Darshan Santani, Rajesh Krishna Balan, C. Jason Woodard | <span class="pubv">MobiSys Demo 2008</span> </p>

In this paper, we study a unique dataset (at least it was one of its kind in 2007): GPS location traces from a large taxi fleet operator in Singapore. This data provided an intriguing research setting, as we could view taxi drivers as boundedly rational, imperfectly informed, and economically motivated humans controlled partly via an automated dispatching mechanism and partly by their own behavioral rules. Our initial work examined the collective system dynamics from the (contradicting yet correlated) perspectives of passengers, drivers and the fleet operator. We proposed a method for evaluating the efficiency of the system over time and geographic zone. [**Technical Report**]({{ site.baseurl }}/assets/papers/research-report-08.pdf)
