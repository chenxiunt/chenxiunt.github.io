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

<br clear="left"/>


-----------------------
**Master Students**
* Harshitha Gorrepati (2022 Spring --) 
* Bharath Datta Chary Vadla (2022 Fall --)


-----------------------
**Alumni**
* Ervin Centeno (B.S. at Rowan University, 2019) First employment: Digital Associate at Wal Mart
* Ce Pang (B.S. at Rowan University, 2020) First employment: Software Engineer at Barclays Bank US. 
* Pinal Mehta (M.S. at Rowan University, 2020) First employment: Software Engineer at IBM.  
* Tanuja Polineni (M.S. at UNT, 2022) First employment: Software Engineer at Tricentis

<div class="people">

{% for y in page.roles %}
  <h2 class="roles">{{role}}</h2>
  {% bibliography -f papers -q @*[roles={{y}}]* %}
{% endfor %}

</div>

