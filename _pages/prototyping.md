---
layout: page
permalink: /prototypings/
title: Prototypings
description: This page introduce robotics hardware platforms I developed for research in Ph.D. degree from 2017 to now.

nav: true
nav_order: 3
---



<h4> <b> 1. ROS-based Multi-robot Testbed </b> </h4>
<div id='container'>
    <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/platforms/mrs_testbed.jpg' | relative_url }}" alt="" title="Multi-robot Testbed"  class="center" style='float: none;height: 100%; width: 100%; object-fit: contain'/>
    <figcaption class="figure-caption text-center"> [ROS-based Mobile Testbed for Multi-robot System.]</figcaption>
    <br>
    <p>We present a new multi-robot system as a means of creating a visual communication cue that can add dynamic illustration to static figures or diagrams to enhance the power of delivery and improve an audience's attention. The proposed idea is that when a presenter/speaker writes something such as a shape or letter on a whiteboard table, multiple mobile robots trace the shape or letter while dynamically expressing it. The dynamic movement of multi-robots will further stimulate the cognitive perception of the audience with handwriting, positively affecting the comprehension of content. To do this, we apply image processing algorithms to extract feature points from a handwritten shape or letter while a task allocation algorithm deploys multi-robots on the feature points to highlight the shape or letter. We present preliminary experiment results that verify the proposed system with various characters and letters such as the English alphabet.</p>
    <ul>
        <li>Videos:(1) Testbed: <a href="https://youtu.be/i6HtzHSfXWg" target="_blank">https://youtu.be/i6HtzHSfXWg​​</a>​, and (2) User study: <a href="https://youtu.be/E0ETeqvvxPk​​/" target="_blank">https://youtu.be/E0ETeqvvxPk​​</a></li>
        <li>Papers:(1) Ahreum Lee, <b>Wonse Jo</b>, Shyam Sundar Kannan & Byung-Cheol Min (2021) Investigating the Effect of Deictic Movements of a Multi-Robot, International Journal of Human–Computer Interaction, 37:3, 197-210, DOI: 10.1080/10447318.2020.1812908 ; <a href="https://www.tandfonline.com/doi/full/10.1080/10447318.2020.1812908​" target="_blank">Link​​</a>, and (2) <b>Wonse Jo</b>, J. H. Park, S. Lee, A. Lee and B. Min, "Design of a Human Multi-Robot Interaction Medium of Cognitive Perception," <i>2019 14th ACM/IEEE International Conference on Human-Robot Interaction (HRI)</i>, 2019, pp. 652-653, doi: 10.1109/HRI.2019.8673188; <a href="https://ieeexplore.ieee.org/abstract/document/8673188​" target="_blank">Link​​</a></li>
    </ul>
</div>


<h4> <b> 2. Opensource ROS2 Mobile Robot Platform: SMARTmBOT </b> </h4>
<div id='container'>
    <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/platforms/smartmbot.jpg' | relative_url }}" alt="" title="Multi-robot Platform: SMARTmBOT"  class="center" style='float: none;height: 100%; width: 100%; object-fit: contain'/>
    <figcaption class="figure-caption text-center"> [ROS2-based Mobile Robot Platform for Mutli-robot System, called SMARTmBOT.]</figcaption>
    <br>
    <p>We develop SMARTmBot, an open-source, low-cost mobile robot platform that can facilitate the research and education involving multi-robot systems. SMARTmBot runs on Robot Operating System (ROS) 2, using Raspberry Pi 4 as the mainboard computer. The hardware is composed of 3 layers of PCB, including various input and output devices. SMARTmBots as a swarm can form different types of formations, change their light either individually or as a whole, and measure the distance of nearby obstacles. In the future, we will utilize this platform to investigate the effects of a swarm/multi-robot on human perception and cognition. In addition, we will enable K-12 teachers and students to access this robot platform to promote their education and interests in STEM.​</p>
    <ul>
        <li> Repository: <a href="https://github.com/SMARTlab-Purdue/SMARTmBOT​​" target="_blank"> https://github.com/SMARTlab-Purdue/SMARTmBOT​​​​​</a>​</li>
        <li> Video: <a href="https://youtu.be/cn3vcqFgf90​" target="_blank">https://youtu.be/cn3vcqFgf90​​​​</a>​</li>
        <li> Paper: <b>Wonse Jo</b>, Jaeeun Kim, and Byung-Cheol Min, ``ROS2 Open-Source Swarm Robot Platform: SMARTmBot,'' <i>2021 International Conference on Robotics and Automation (ICRA)</i>, Workshop on Robot Swarms in the Real World: From Design to Deployment - Live Demonstration, Xi'an, China, May 30 - June 5, 2021.​ </li>
    </ul>
</div>



<h4> <b> 3. Environmental Unmannded Surfce Vessles: SMARTmBOAT series </b> </h4>
<h5> <b> (a) SMARTmBOAT-03 </b> </h5>
<div id='container'>
    <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/platforms/smartmboat-03.jpg' | relative_url }}" alt="" title="Water Monitoring USV Platform"  class="center" style='float: none;height: 100%; width: 100%; object-fit: contain'/>
    <figcaption class="figure-caption text-center"> [ROS-based Opensource Unmanned Surface Vehicle (USV) for water montioring, called SMARTmBOAT-03.]</figcaption>
    <br>
    <p>We propose a new, fully open-source, low-cost, and small-sized Unmanned Surface Vehicle (USV) for measuring near-surface water quality in real time in various environments. Existing commercial USVs are expensive and not fully based on open-source hardware, making it difficult to purchase them and to modify their designs and programming to suit various environments. In contrast, the USV platform proposed in this paper is completely open-source, from hardware to software; most parts of the platform can be 3D-printed, and it can be easily modified and upgraded in terms of both design and programming. The platform is equipped with off-the-shelf water sensors for acquiring data like as pH, turbidity, and temperature to measure water quality in real water resources (such as ponds, reservoirs, and lakes). Furthermore, we provide an Android application through which users can easily control the USV via Bluetooth and display the sensor and GPS data the platform generates. We validated the performance of the platform in terms of usability, mobility, and stability through field experiments in various locations, including both the USA and Peru. Moreover, we present a potential application and approach in which this platform can navigate autonomously by utilizing the Robot Operating System (ROS) and Bluetooth protocols.</p>
    <ul>
        <li> Repository: <a href="https://osf.io/wsnrt/​​​" target="_blank"> https://osf.io/wsnrt/​​​​​​​​</a>​</li>
        <li> Video: <a href="https://youtu.be/OBqA9pRZ8pM​" target="_blank">https://youtu.be/OBqA9pRZ8pM​​​​​</a>​</li>
        <li> Paper: <b>Wonse Jo</b>, Hoashi, Y., Aguilar, L. L. P., Postigo-Malaga, M., Garcia-Bravo, J. M., & Min, B. C. (2019). A low-cost and small USV platform for water quality monitoring. <i>HardwareX</i>, 6, e00076; <a href="https://www.sciencedirect.com/science/article/pii/S2468067219300367?via%3Dihub​" target="_blank">Link​​</a></li>
    </ul>
</div>

<h5> <b> (a) SMARTmBOAT-04 </b> </h5>
<div id='container'>
    <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/platforms/smartmboat-04.jpg' | relative_url }}" alt="" title="Reversible USV Platform"  class="center" style='float: none;height: 100%; width: 100%; object-fit: contain'/>
    <figcaption class="figure-caption text-center"> [ROS2-based Opensource Unmanned Surface Vehicle (USV) for water montioring, called SMARTmBOAT-04.]</figcaption>
    <br>
    <p>We propose a new and small USV platform to overcome the limitations of existing robot systems. The main feature of the proposed USV is that it is designed as a vertically symmetrical structure, so that it can continuously perform its mission even when the USV is capsized. Moreover, the USV system can automatically check whether the robot has been capsized via GPS and IMU sensors installed on the USV, and carry out the mission regardless of whether it is overturned, by controlling three waterproof servo motors according to the USV’s orientation, to rotate two main thrusters and the water sensor module. The USV measures water quality and depth in real-time through a Total Dissolved Solids (TDS) sensor, a temperature sensor, and a Ping sensor that measures water depth. A forward-facing camera allows the USV to autonomously avoid obstacles using computer vision. All data is transmitted in real-time to the user interface or main system using Robot Operating System 2 (ROS2), the latest robot middleware that supports real-time control.​</p>
    <ul>
        <li> Poster: <b>Wonse Jo</b>, Pou hei Chan, Chad T. Jafvert, Mauricio Postigo-Malaga, and Byung-Cheol Min, "Development of a Vertically Symmetrical Unmanned Surface Vessel (VSUSV) for Bathymetric and Water Quality Surveys of Surface Waters," <i>2020 the 7th Annual C4E Environmental Community Mixer, Purdue University</i>, Oct. 2020.</li>
    </ul>
</div>

<h5> <b> (a) SMARTmBOAT-05 </b> </h5>
<div id='container'>
    <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/platforms/smartmboat-05.jpg' | relative_url }}" alt="" title="Alage Removal USV Platform"  class="center" style='float: none;height: 100%; width: 100%; object-fit: contain'/>
    <figcaption class="figure-caption text-center"> [Low-cost Algae Removal Unmanned Surface Vehicle (USV) Platform, called SMARTmBOAT-05.]</figcaption>
    <br>
    <p>We introduce a small and low-cost unmanned surface vehicle (USV), the SMARTBoat 5, capable of removing harmful algal blooms (HABs), which are a rising environmental issue worldwide. The developed USV is a hovercraft type, operated by two propellers with duct fans; it is able to freely move even in shallow water and to approach shorelines. For eco-friendly, immediate, and safe control of algae, the USV is equipped with a novel water suction mechanism that enables it to actively collect algae without physical contact. In addition, it is equipped with a mesh net-based algae filter system that is easily disassembled and replaced. The USV system is supported by the Robot Operating System (ROS) for expandability and use in diverse applications. The performance of the proposed water suction mechanism and USV platform overall are validated through computational fluid simulation (CFD) and experiments in both lab and real environments.​​</p>
    <ul>
        <li> Repository: <a href="https://github.com/SMARTlab-Purdue/Harmful-Algae-Removal-USV​​​​" target="_blank"> https://github.com/SMARTlab-Purdue/Harmful-Algae-Removal-USV​​​​​​​​​</a>​</li>
        <li> Video: <a href="https://youtu.be/8BPvFbJgXho​" target="_blank">https://youtu.be/8BPvFbJgXho​</a>​</li>
        <li> Paper: <b>Wonse Jo</b>, J. Park, Y. Hoashi and B. Min, "Development of an Unmanned Surface Vehicle for Harmful Algae Removal," <i>OCEANS 2019 MTS/IEEE SEATTLE</i>, 2019, pp. 1-7, doi: 10.23919/OCEANS40490.2019.8962677; <a href="https://ieeexplore.ieee.org/document/8962677" target="_blank">Link​​</a></li>
    </ul>
</div>


<h4> <b> 3. Anti-noise Tapping Sound Generator and prediction </b> </h4>
<div id='container'>
    <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/platforms/tapping_generator.jpg' | relative_url }}" alt="" title="Anti-noise Tapping Sound Generator"  class="center" style='float: none;height: 100%; width: 100%; object-fit: contain'/>
    <figcaption class="figure-caption text-center"> [Anti-noise Tapping Sound Generator to Recognize Unknown Material Types.]</figcaption>
    <br>
    <p>For recognizing unknown material in search and recuse environment, we developed the anti-noise tapping sound generator that is making and recognizing the tapping sound to estimate types of the material. The system have two microphones and a solenoid. The two microphones are to reduce environmental noise for recording only tapping sound generated by the solenoid. Finally, the system was able to estimate types of following materials using MFCCs and SVM: cardboard, glass, metal, plastic, wall, wood, and empty.​</p>
    <ul>
        <li>Video: <a href="https://youtu.be/4VGntBByJWE" target="_blank">https://youtu.be/4VGntBByJWE​​</a>​</li>
        <li>Paper: S. Kannan, <b>Wonse Jo</b>, R. Parasuraman and B. -C. Min, "Material Mapping in Unknown Environments using Tapping Sound," <i>2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</i>, 2020, pp. 4855-4861, doi: 10.1109/IROS45743.2020.9341346; <a href="http://ras.papercept.net/images/temp/IROS/files/2147.pdf​" target="_blank">Link​​</a></li>
    </ul>
</div>


