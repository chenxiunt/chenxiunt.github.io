---
layout: page
permalink: /People/
title: People
roles: [Director, Ph.D., Master, Undergraduate]
nav: false
---

I am fortunate to work with several bright students:

-----------------------
**Ph.D. Students**



<br>

<div class="row justify-content-md-center">
    <div class="col-sm-3">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/people/Sourabh.jpg' | relative_url }}" alt="" title="Sourabh Yadav"/>
    </div>
    <div class="col-sm-4">
        <b>Sourabh Yadav</b> <br>
        Ph.D. student (2022 Spring --) <br><br>
        Data privacy, Machine Learning, Deep Learning, and Blockchain <br><br>
        Email: Sourabh.Yadav AT unt.edu <br>
        <a href="https://scholar.google.com/citations?user=Luc18E4AAAAJ&hl=en">Google scholar</a>
    </div>
    <div class="col-sm-5">
        Sourabh received his MS degree in Artificial Intelligence and Robotics and have been an active researcher in the subject since 2018. Currently, he is working on location privacy protection in time-sensitive spatial crowdsourcing and cooperative perception of autonomous vehicles.  
    </div>  
</div>  
<br>

<div class="row justify-content-md-center">
    <div class="col-sm-3">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/people/Mingxuan.jpg' | relative_url }}" alt="" title="Mingxuan Li"/>
    </div>
    <div class="col-sm-4">
        <b>Mingxuan Li</b> <br>
        Ph.D. student (2023 Spring --) <br><br>
        Cloud computing, Spatial Computing, and Data privacy<br><br>
        Email: LiMingxuan AT my.unt.edu <br>
        <a href="https://scholar.google.com/citations?user=3cG4lEEAAAAJ&hl=zh-CN&authuser=2">Google scholar</a>
    </div>
    <div class="col-sm-5">
        Mingxuan Li received his MS degree in Circuit and Systems at Beijing Jiaotong University and BS degree in Electronic Information Engineering at Capital Normal University in China. He was a senior engineer at China Unicom Research Institute engaged in research topics related to cloud computing, edge computing, and mobile Internet. Currently, he is working on location privacy problems in mobile crowdsourcing, deep generative models, etc.    
    </div>   
</div>  


<br clear="left"/>


-----------------------
**Master Students**

Harshitha Gorrepati (2022 Spring --) 

Bharath Datta Chary Vadla (2022 Fall --)


-----------------------
**Alumni**

Ce Pang (B.S., 2020) Currently studying at Santa Clara University and still collaborating with our lab. 

Tanuja Polineni (M.S., 2022) Current employment: Tricentis

<div class="people">

{% for y in page.roles %}
  <h2 class="roles">{{role}}</h2>
  {% bibliography -f papers -q @*[roles={{y}}]* %}
{% endfor %}

</div>

