---
layout: page
title: Vehicular Geo-Obfuscation
description: The goal of this project is to protect vehicle location privacy in various location based applications. 
img: /assets/img/logo/project-V-obfuscation.png
importance: 1
---

**Task 1: Traffic flow aware inference attacks.** Thinking like an adversary, we propose a new threat model that leverages traffic flow information to recover vehicles’ exact locations from other types of information, such as braking signals or perturbated locations. We describe the target vehicle’s mobility by a *hidden Markov model (HMM)* (Figure 1), and then track the vehicle’s exact locations using the Viterbi algorithm (Figure 2). 

<div class="row justify-content-md-center">
    <div class="col-sm-9">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/TrafficAdapter_HMM.png' | relative_url }}" alt="" title="Figure 1. HMM model"/>
    </div>
</div>
<div class="caption">
    Figure 1. HMM model: the vehicle’s exact location is considered as a hidden state, while its sensor information/perturbated location is considered as an observable state; the HMM transition matrix, which can be learned using the traffic flow information, describes the probabilities of the vehicle traveling between the locations over the map. 
</div>

<div class="row justify-content-md-center">
    <div class="col-sm-9">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/TrafficAdapter_inference.png' | relative_url }}" alt="" title="Figure 1. Example: Accuracy of location tracking using the vehicle traffic flow information."/>
    </div>
</div>
<div class="caption">
    Figure 2. Example: a traffic aware attacker can accurately track a taxicab’s locations (in Shenzhen mobility trace dataset) even when the taxicab’s location has been obfuscated with a state-of-the-art obfuscation algorithm.
</div>

Publications: **Sigspatial 2022**, **IPSN 2020**

The MATLAB code of vehicle location tracking has been released [here](https://github.com/chenxiq1986/vehicle-traffic-flow-aware-attack).

---

**Task 2: Location obfuscation over the road networks**. Considering that individual vehicles’ mobility is restricted by various road environments, including traffic flows and local road network topology, our objective is to design time-efficient obfuscation techniques to protect vehicles' location privacy against the traffic-aware inference attacks. 


<div class="row justify-content-md-center">
    <div class="col-sm-9">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/TrafficAdapter_Framework.png' | relative_url }}" alt="" title="Figure 3. Framework of location obfuscation"/>
    </div>
</div>
<div class="caption">
    Figure 3. Framework of location obfuscation: Vehicles need to report their locations to the server. We consider a passive attack where attackers can eavesdrop on vehicles' reported locations  breached by the server. 
</div>

Publications: 
**TMC 2020**, **CIKM 2020**, **ICDCS 2019**

---

**Task 3: Vehicle Spatial Crowdsourcing (SC) Platform**. We have built a prototype of SC, which encompasses essential features such as task request/assignment and geo-obfuscation. To enhance user accessibility, we've created an Android application utilizing the Google Maps API, as depicted in Figure 4. The application enables users to register/log in as either a requester or a worker. Requesters can conveniently upload tasks with specified locations, while workers can download a Geo-Obfuscation (GO) matrix from the server. Using this matrix, a worker can choose an obfuscated location and potentially receive a task assignment from the server. Upon receiving a task, the worker has the option to accept it by clicking the "accept" button, triggering the display of a navigational route on the map guiding them to the task location.

<div class="row justify-content-md-center">
    <div class="col-sm-9">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/SCmobile.png' | relative_url }}" alt="" title="SCmobileUserInterface"/>
    </div>
</div>
<div class="caption">
    Figure 4. User Interface: Task requester (left) and Worker (right). 
</div>
Publications: NA

