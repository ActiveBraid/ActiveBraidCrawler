<h1 align="center">Active Braid Crawler</h1>
<p align="center">
A bio inspired mobile robot capable of adapting its morphology to the surrounding environment through compliant structures and novel locomotion mechanisms. 
</p>
<p align="center">
    <img width="500" src="https://github.com/ActiveBraid/ActiveBraidCrawler/blob/main/Image/img1.jpg" alt="">
</p>
<p align="center">
Fig 1: Active Braid Crawler - 3 section design
</p>

# Introduction
Mobile robots capable of accessing narrow and remote areas find applications in a verity of fields. Recent bio-inspired solutions are emerging, where the robot can adapt its morphology to the surrounding environment through compliant structures and novel locomotion mechanisms. 
Here we present the concept and design for a compliant mobile robot, able to move in open and constrained environments. The robot structure can deform both actively and passively to adapt to changes in the environment. A compliant braided structure converts the radial actuation into elongation/contraction, while the structure passively deforms to adapt to the environment. Differently from previous braided robots, the solution we present has three or more independent sections individually actuated by servomotors. The merit of such a design lies in the ability to produce different actuation patterns by varying the phase difference between the servomotors.
Concept and Design
The compliant in-pipe robot consists of two key parts: 
* A deformable compliant braid structure. 
* Radial actuators producing the deformation in the braided structure.
<h3 align="left">1) Complaint Braid Structure</h3>
The main structure of the robot is a braid i.e., a cylindrical shell consisting of clockwise and anti-clockwise sets of mutually interlaced, helical fibers. These crossed-linked helical array structures, ideally composed of non-extensible yet flexible fibers, exhibit some special modes of structural deformation. When extended or contracted axially, the structure is capable of considerable accommodation of strain since the helix angle of each fiber can change. Unlike a conventional braid, the design proposed in this work consists of 24 slender beams (12 clockwise and 12 anti-clockwise) all connected together through pin joints. As a result, each link deforms into a helical shape. A single link is divided into 17 sub-links. Pin joints are provided at the center of each sub-link, which keeps the two layers combined and yet produce the structural deformation required.  
<p align="center">
    <img width="500" src="https://github.com/ActiveBraid/ActiveBraidCrawler/blob/main/Image/img2.jpg" alt="">
</p>
<p align="center">
Fig 2: Assembled Braided Structure
</p>
<h3 align="left">2)	Radial Actuators</h3>
The radial actuator converts the rotation of a servomotor into radial displacement. It is used to increase and decrease the diameter of the braided structure. It consists of a modified crank and slider mechanism, where the connecting rods of six individual sliding arms (radially arranged) are connected to a single crank, driven by a smart servo (Robotis-Dynamixel XM430-W210-R). Each sliding arms is connected to the inner surface of the braided structure through pin joints. The smart servo has an absolute encoder for position control and the its torque can be controlled by adjusting the input current, hence each servo acts as an actuator and a sensor.
<p align="center">
    <img width="500" src="https://github.com/ActiveBraid/ActiveBraidCrawler/blob/main/Image/img3.jpg" alt="">
</p>
<p align="center">
Fig 3: Radial Actuator (CAD Design)

| # | *Name* | *Speed* | *Actuation* | *Dimensions* | *Weight* |
|---|   ---  |   ---   |     ---     |      ---     |    ---   |
| 1 | Active Braid - CrawlerActive Braid - Crawler | Hor free 22mm/sec Hor cons 72mm/sec Ver cons 27mm/sec | 3 Robotis Dynamixel XM-430-w210 (82g-3Nm) | Dia (min 120mm – max 165mm) Length (min 140mm – max 400mm) |   600g   |
| 2 | MRINSPECT-VII [1](http://vigir.missouri.edu/~gdesouza/Research/Conference_CDs/IEEE_IROS_2013/media/files/1164.pdf) | 25mm/sec | 1 DC motor | --- | --- |
| 3 | PAROYS-II [2](https://www.semanticscholar.org/paper/Development-of-an-actively-adaptable-in-pipe-robot-Park-Kim/4060ee24c6ad8664d54e3ad67b80dd1e1509dd96) | 41.6mm/sec | 3 RC servo motors 4 DC motors | Length 390mm Adaptable Dia 400-700mm | 7.8kg |
| 4 | Screw drive mechanism robot [3](https://www.researchgate.net/publication/224223037_Mobility_of_an_in-pipe_robot_with_screw_drive_mechanism_inside_curved_pipes) | --- | 1 DC motor | Length 156mm Dia 122-131mm | 0.9kg |
| 5 | Worm like robot [4](https://www.spiedigitallibrary.org/proceedings/Download?fullDOI=10.1117%2F12.2044262) | 12.8mm/sec | 8 RC servo motors | Length 581.5mm Dia 64-82.6mm | 810g |
| 6 | Origami [5](https://ieeexplore.ieee.org/document/6266749) | 18.5mm/min (0.3mm/sec) | NiTi coils | Length 100mm | 4.2g |
| 7 | Mesh worm [6](https://dspace.mit.edu/bitstream/handle/1721.1/72510/Rus_Peristaltic%20locomotion.pdf?sequence=2&isAllowed=y) | 3.47mm/sec | NiTi coil actuators | Length 200mm Dia 22mm | --- |
| 8 | Soft worm [7](https://www.researchgate.net/publication/280623097_Worm-Like_Robotic_Locomotion_with_a_Compliant_Modular_Mesh) | Hor free 4.3mm/sec | (6) Robotis Dynamixel MX-64T (126g-6Nm) | Dia (min 126mm - max 206mm) Length (min 1030mm - max1340mm) | 2.08kg |
<p align="center">
Table 1: Performance comparison with state of the art
</p>

<h4 align="left">Fabrication Instructions:</h4>
The fabrication files are attached and one should download the zip files named "Assembly Instructions". Extract it and it contains the coresponding PDFs
<h4 align="left">CAD files:</h4>
The CAD folder contains the Auto CAD files inside the zip folder



