<h1 align="center">ActiveBraidCrawler</h1>
<p align="center">
A bio inspired mobile robot capable of adapting its morphology to the surrounding environment through compliant structures and novel locomotion mechanisms. 
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
<h3 align="left">2)	Radial Actuators</h3>
The radial actuator converts the rotation of a servomotor into radial displacement. It is used to increase and decrease the diameter of the braided structure. It consists of a modified crank and slider mechanism, where the connecting rods of six individual sliding arms (radially arranged) are connected to a single crank, driven by a smart servo (Robotis-Dynamixel XM430-W210-R). Each sliding arms is connected to the inner surface of the braided structure through pin joints. The smart servo has an absolute encoder for position control and the its torque can be controlled by adjusting the input current, hence each servo acts as an actuator and a sensor.
<p align="center">
    <img width="500" src="https://github.com/ActiveBraid/ActiveBraidCrawler/blob/main/Image/Table%201.png" alt="">
</p>
<h4 align="left">Fabrication Instructions:</h4>
The fabrication files are attached and one should download the zip files named "Assembly Instructions". Extract it and it contains the coresponding PDFs
<h4 align="left">CAD files:</h4>
The CAD folder contains the Auto CAD files inside the zip folder
