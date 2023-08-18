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
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/people/Sourabh.png' | relative_url }}" alt="" title="Sourabh Yadav"/>
    </div>
    <div class="col-sm-4">
        <b>Sourabh Yadav</b> <br>
        Ph.D. student (2022 Spring --) <br><br>
        Data privacy, Machine Learning, Deep Learning, and Blockchain <br><br>
        Email: Sourabh.Yadav AT unt.edu <br>
        <a href="https://scholar.google.com/citations?user=Luc18E4AAAAJ&hl=en">Google scholar</a>
    </div>
    <div class="col-sm-5">
        Sourabh received his MS degree in Artificial Intelligence and Robotics and have been an active researcher in the subject since 2018. Currently, he is working on location privacy protection in time-sensitive spatial crowdsourcing and cooperative perception of autonomous vehicles. He is leading the project "<a href="https://chenxiunt.github.io/projects/SpatialAgent/">SpatialAgent</a>" in MCLab. 
    </div>  
</div>  
<br>

<div class="row justify-content-md-center">
    <div class="col-sm-3">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/people/Xinpeng.png' | relative_url }}" alt="" title="Xinpeng Xie"/>
    </div>
    <div class="col-sm-4">
        <b>Xinpeng Xie</b> <br>
        Ph.D. student (2023 Fall --) <br><br>
        Sensor perception <br><br>
        Email: TBD <br>
        
    </div>
    <div class="col-sm-5">
        Xinpeng received his BS degree in Automation from Sichuan University, P. R. China. 
    </div>  
</div>  
<br>

<div class="row justify-content-md-center">
    <div class="col-sm-3">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/people/Gaoyi.jpg' | relative_url }}" alt="" title="Gaoyi Chen"/>
    </div>
    <div class="col-sm-4">
        <b>Gaoyi Chen</b> <br>
        Ph.D. student (2023 Fall --) <br><br>
        Data privacy <br><br>
        Email: TBD <br>
        
    </div>
    <div class="col-sm-5">
        Gaoyi received his BS degree in Telecommunication Engineering from Zhengzhou University, P. R. China.   
    </div>  
</div>  
<br>

<div class="row justify-content-md-center">
    <div class="col-sm-3">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/people/Ruiyao.jpg' | relative_url }}" alt="" title="Ruiyao Liu"/>
    </div>
    <div class="col-sm-4">
        <b>Ruiyao Liu</b> <br>
        Ph.D. student (2023 Fall --) <br><br>
        Data privacy <br><br>
        Email: TBD <br>
        
    </div>
    <div class="col-sm-5">
        Ruiyao received his BS degree in Automation from Sichuan University, P. R. China.  
    </div>  
</div>  
<br>

<br clear="left"/>


-----------------------
**Master Students**
* Harshitha Gorrepati (2022 Spring --) 
* Bharath Datta Chary Vadla (2022 Fall --)
* Padma Priya Dirisala (2023 Spring --)

-----------------------
**Undergraduate Students**
* Eichelle Turner (2023 Fall --) 
* Kelsey Nichols (2023 Fall --)

-----------------------
**Alumni**
* Ervin Centeno (B.S. at Rowan University, 2019) First employment: Digital Associate at Wal Mart
* Shangwen Ma (B.S. at Rowan University, 2019) Transferred to University of Colorado Boulder
* Ce Pang (B.S. at Rowan University, 2020) First employment: Software Engineer at Barclays Bank US. 
* Pinal Mehta (M.S. at Rowan University, 2020) First employment: Software Engineer at IBM.  
* Tanuja Polineni (M.S. at UNT, 2022) First employment: Software Engineer at Tricentis

<div class="people">

{% for y in page.roles %}
  <h2 class="roles">{{role}}</h2>
  {% bibliography -f papers -q @*[roles={{y}}]* %}
{% endfor %}

</div>

