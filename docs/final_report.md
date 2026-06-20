
GutCheck
Submitted By: Alex Huang, Euvene Kae, Sahej Sachdeva, Benson Zhang
					
											
Design Thinking and Communication Program
Professors Meghan Geigner and Zachary Berent
McCormick School of Engineering and Applied Science
Northwestern University
Evanston, Illinois 60208

June 5, 2026

Table of Contents
1 Background and Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8

2 Design Concept and Rationale . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  9

   2.1 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  9

   2.2 Mounting/Enclosure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  9

   2.3 Components . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 10

   2.4 Requirements . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13

3 Future Development . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  15

   Physical Enclosure . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15

   Electrical . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15

   Data Pipeline . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  15

Appendix A: Project Definition . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  17

Appendix B: Research Appendix . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  20

   Part A: Secondary Research Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  20

      BA.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  20

      BA.2 Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  20

      BA.3 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  21

      BA.4 Discussion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 26

   Part B: Interview with Contractor . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28

      BB.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28

      BB.2 Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28

      BB.3 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28

      BB.4 Discussion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  30

   Part C: Interview with Local Hardware Stores . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  30

      BC.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 30

      BC.2 Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 31

      BC.3 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 31

      BC.4 Discussion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 34

Appendix C: Safety Evaluations and Ethical Concerns . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 35

   H.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  35

   H.2 Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  35

   H.3 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .   36

      Ethical Concerns . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 36

      Safety Concerns . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 37

   H.4 Discussion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 38

Appendix D: Instructions for Construction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  39

   G.1 Materials and Equipment . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  39

   G.2 Enclosure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  39

   G.3 Sensor and Battery . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 40

   G.4 Final Assembly . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 43

   G.5 Waterproofing . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44

   G.6 Website . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 45

Appendix E: Mockups and Testing . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  46

   C.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  46

   C.2 Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .  46

   C.3 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 46

      Testing with Gutter . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 49

      Enclosure Iteration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 56

      Final Enclosure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 59

   C.4 Discussion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 63

Appendix F: Design Review Appendix . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 65

   G.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 65

   G.2 Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 65

   G.3 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 65

   G.4 Discussion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66

Appendix G: Website Usability Appendix . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66

   J.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66

   J.2 Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66

   J.3 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 67

   J.4 Discussion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 67

Appendix H: Bill of Materials . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 68

References . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 69











1  Background and Introduction
Climate and weather conditions constantly affect the lives of millions worldwide, with these natural processes impacting infrastructure from large-scale systems to individual homes. Rain is a constant and natural phenomenon that can cause infrastructure damage, particularly if the infrastructure's overall design has flaws in its construction. One particular point of focus is the gutter system, as although this has been an effective solution for directing water away from rooftops, there are still issues with clogging that could damage these gutters. Gutter damage costs Americans $100-200 annually, with other water damage to homes, such as flooding, raising the cost to up to $14,000 due to negligence in gutter maintenance [1]. This exemplifies the importance of maintaining gutters on homes, as it could help save Americans thousands of dollars annually, underscoring the significance of this issue. 
Our goal is to create a sensor-website pipeline that would allow for the detection of water flow in gutters, creating a system that could analyze the different levels of water flow to give the user feedback on how critical the water flow is to determine whether or not there is a need for them to check on the gutters on their homes (see Appendix A). Research was conducted to explore existing patents, examine the solutions developed, and identify gaps where we could create our design (see Appendix B). Further research was done on gutters to understand how the design of these gutters will affect the device and attachment pieces necessary to create an optimal design, with this secondary research being corroborated with primary research conducted in the form of in-person and online interviews with local contractors and experts in the field of home retail (see Appendix B). With this goal in mind, we also considered the ethical impacts of our solution, focusing on the significance of false readings, environmental concerns, and over-reliance on automation (see Appendix C).

2  Design Concept and Rationale
2.1 Overview
	Our design GutCheck mounts directly on top of a gutter, replacing two of the gutter hangers. The design uses two ultrasonic sensors to create a differential-pair measurement, determining the flow rate and whether the gutter is clogged. Refer to our website to see the design and its components in better detail. We have also established requirements that we will meet with the completion of product design (see Appendix A).

Figure X: GutCheck
2.2 Mounting/Enclosure
	Our enclosure for electrical components also serves as a mount. Taking inspiration from a gutter hanger, the GutCheck replaces two of the gutter hangers and bolts into the fascia. This was to fulfill the stability requirement. To create stable mounting points for all electrical components, we decided to 3D print our enclosure from polycarbonate (PC). The 3D print allows for the enclosure to be very lightweight and waterproof. Other materials such as PLA and PETG were considered as they are common types of 3D printing materials. Still, after considering the attributes and properties of the three materials, PC was considered the most ideal (see Figure Water Bottle). To seal the actual enclosure (another requirement) and make it waterproof, we used silicone to cover the lips and the circular sensor cutouts. The enclosure was created by printing an STL file, which will be available to users so they can 3D print the product for assembly (see Appendix D, Enclosure).

Material/Properties
PLA
PETG
PC
Density (g/cm3)
1.24
1.25
1.20
Heat Deflection Temp (C)
57
68
117
Melting Temp (C)
160
N/A
228
Tensile Strength (MPa)
35
51
55
Breaking Elongation Rate (%)
12.2
9.5
3.8
Bending Modulus (MPa)
2750
1950
2310
Bending Strength (MPa)
76
75
108

Figure Water Bottle: 3D Print Material Comparison
2.3 Components 
Electrical
To actually detect clogs, we decided on a few components. To sense the clogs, we chose an IP67 UART Ultrasonic Range Sensor. This sensor uses no moving components, increasing its longevity. The sensor is also waterproof, rated IP67. The blind zone for this sensor was also acceptable (3cm) (see Appendix B, Part A, Ultrasonic Sensors). We are also using an ESP32 Devkit to take in the data from the ultrasonic sensors. The ESP32 Devkit worked seamlessly with our sensor and would allow the user to receive data quickly. To help users visualize the data, we created an app design that would transfer data recorded by our sensors and display the conditions of the gutter to users (see Appendix E, Website Design). To power the entire system, we are using the Adafruit Waterproof 3×AA Battery Holder. This battery holder is waterproof and delivers the correct voltage and current to the system. Silicon was used to help prevent water from entering the enclosure and to act as an adhesive. This was added to the product after the design review comments, ensuring it would be waterproof, using a different product suggested by a different group (see Appendix F).

Figure X: ESP32 DevKit

Figure X: Ultrasonic Sensor

Figure X: Battery Holder
Dashboard
	For the data collected to be useful, we decided on creating a web application to display the data to the user. Our data pipeline uses a Supabase backend server, where it receives, organizes, and manipulates data in a PostgreSQL database. Supabase also handles our user authentication using its built-in Supabase Auth.
	Our database runs on a unique hierarchical system: users, houses, (gutter) systems, and (gutter) sensor. Each of which are assigned a randomly generated 16-byte UUID. A user first creates an account, which is stored within the authentication schema. Each user account can then create a house. Each house can host any number of gutter systems. Finally, each gutter system can have up to eight gutter sensors assigned to it. Each gutter sensor uses its ESP32's unique MAC address for identification. This information is included with each data packet sent by a sensor. It allows the server to sort incoming data packets against its set of already-registered sensors. This also allows the user to set the order of sensors in a gutter system such to 
	Supabase also takes care of manipulating the data sent by sensors. We implemented a simple moving average (SMA) algorithm. Ultrasonic sensors are prone to inconsistent readings due to environmental factors. This algorithm prevents any momentary sudden change in value to trigger a false positive reading of a clog. Given the output of the SMA, the server also computes the difference between neighboring sensors to determine whether or not a clog has been detected. From our testing, we determined that an appropriate spectrum of risk should have different severities at differences of 1.5, 2.5, and 3.5 cm (see Appendix E, Testing with Gutter). 
	The front end of the dashboard is what the user will see. It uses React.js Javascript library for its improved application speed over systems that interact directly with a browser’s Document Object Model. This is especially useful since we can expect rapidly changing UI instances (changing status lights, graphical display of sensor data, etc.). We decided to use a user-friendly UI of a simple colored dot, which has a green, yellow, amber, and red state. These correspond to the different severity levels, with green representing no clog detected. The user can then expand the view to access graphs and real-time measurements of each sensor. This provides the option for users to see sensor data without overwhelming them out the box.
2.4 Requirements
Detects when clog occur
The two ultrasonic sensors differential pair measurement showing a different water level determines a clog.
Waterproof
The enclosure itself is waterproof
The electrical components are sealed using silicone
The battery pack is already waterproof
Secure when attached
The entire enclosure is bolted into the fascia (a strong wooden board), providing accurate readings and stabilizing our product
Lightweight (so as not to damage the gutter)
The 3D printed enclosure itself is lightweight (3.74 oz)
With only 3 components the entire enclosure is 5.75 oz
Loadbearing
The enclosure, when attached to ideal nondeformable surfaces at its contact points, can sustain up to 66 kg of force on its upward-facing flat surfaces (data based on Solidworks FEA Simulations)
Due to being bolted into the wood, the force in which the sensor can sustain becomes dependent on the forces sustainable by the gutter, gutter mounting system, and the fascia.
Notifies homeowner promptly
After testing, the user is notified promptly within 30 seconds (although it is important to note this varies based on connection and server load)








3 Future Development
Physical Enclosure
To start with we've talked about the physical enclosure. We want the physical enclosure to be adaptable to gutters of many different sizes. Ideally, we want something universal. Either that, or we want to stick with a model that supports all 5-, 6-, and 7-inch standard K-style gutters. And finally, we also want to move away from cheap plastic parts. Although our current design uses polycarbonate 3D printing, it will be more structurally sound and ultimately longer-lasting if we design it from a different kind of metal, whether that is through CNC or 3D printing.
Electrical
In terms of electrical systems, we want to improve the enclosure of our electrical components and have dedicated slots for them. This is to reduce the amount of rattling around you, and in case you decide to shift the product or something like that. A motherboard that just floats in a cavity within our sensor isn't ideal. The sensor itself can be improved to reduce its footprint. We can make a custom PCB and set it up using a breadboard development kit, which improves signal integrity and supports custom electronics, allowing us to add more sensors and reduce the overall footprint of our product. Other sensors can include:
Infrared-based tracking for better water flow detection.
Capacitive leaves and capacitive metal contact plates that also allow us to detect better water flow rate rather than just water level.
A more reliable, more robust board with buttons and user-interactive features. This will also better streamline our pairing process.
Data Pipeline
We want to improve our UI so we can more accurately tell the user which part of the gutter is plugged. Right now, we are only relying on sensor readings, so users still have to use a bit of deduction to figure out which part of their gutter system is clogged (see Appendix G). Additionally, we also want to streamline the data storage system. The database is currently very linear; it is a structured database, and we have not considered what happens when a user has, let's say, 500, with some absurdly high amount of gutters. This will also flow into our UI and the different ways it will show these sensors. There are probably better ways to optimize these things. 



Appendix A: Project Definition
Project Title: 
Client: American Homeowners
Team Members: Euvene, Alex, Sahej, and Benson
Date: 5/6/2026
Version: 3
POV Statement:  
American homeowners need a way to detect gutter clogs to prevent water leaks and foundation damage.
Project Deliverables:
Final report
Final prototype 
Final presentation
Constraints: 
Deadline of June 4, 2026
Budget of $100 for prototype
Users and Stakeholders: 
Homeowners with gutters
User Profile:
	Many homeowners across the US experience weather damage. These damages can cause severe structural damage to a home, leaving many citizens with high costs and stress. Because people often do not check the health of their roofs, these areas are more susceptible to permanent damage, which usually requires the replacement of expensive parts. The most common source of damage is clogs caused by leaves and ice in gutters that prevent water from flowing. Many gutter systems can help homeowners prevent water damage, but they all require a full replacement.
Illustrative User Scenario:
This scenario is based on conducted primary and secondary research. (see Appendix B)
Chris, a contractor in Louisiana, enjoys providing American homeowners with the improvements they want. However, a large part of his job consists of repairing damage caused by hurricanes and heavy rains in the areas. Every day, he sees houses that have water damage to their roofs or foundations. Many homeowners forget to check their roofs for gutter damage, leading to roof leaks and mold. This means that a lot of Chris’s time is spent repairing these damages.
Oftentimes, repairing water damage requires removing the existing infrastructure. Chris has to remove the roof tiles, gutters, or interior walls and completely replace them when he encounters water damage, not to mention the foundation repairs he may have to make. Chris has noticed new technologies that can prevent roof leaks and gutter damage, but they all require a high upfront cost and the complete replacement of existing roofing and gutter systems. Because of this, a device that could better equip the current gutter systems in American homes to detect damage would greatly aid Chris and many homeowners.
(see next page for the project requirements)







Table 1. Project Requirements


Requirements
Metrics
Units
Ideal value
Allowable value
As-built
Detects when clog occurs
Differential pair of measurements
cm
10% >
5%


Waterproof
Mock IP Rating
IP
IP54
IP42


Secure when attached
Shake Test
?
Doesn’t break
Doesn’t break


Lightweight (so as not to damage the gutter)
Total system mass
lbs
2 lbs
3 lbs


Loadbearing
Total system mass + object
lbs
10 lbs
10 lbs


Notifies homeowner promptly
Clog to notification time
Minutes
5 minutes
10 minutes








Appendix B: Research Appendix
Part A: Secondary Research Summary
BA.1 Introduction
	Section 16 of Design Thinking and Communication was assigned to develop a problem related to the UN Global Goals. With Goal 11: Sustainable Cities and Communities in mind, our group decided to develop a solution to mitigate rooftop pollution in buildings. Given the scope of the issue, our goal was to develop a deeper understanding of the various factors contributing to mold, water damage, and rooftop pollution in homes in the US. 
After an initial round of research and ideation, our team pivoted to sensing gutter clogs. To do this, we had to research gutters and sensors.  Our group also researched existing gutter sensing patents to understand the intellectual property landscape and identify design constraints. For materials, our group also researched different 3D printing materials.
BA.2 Methodology
	To better understand the effects of mold and rooftop pollution, each member researched a different cause of water damage and mold, as well as a corresponding solution. By focusing on the prevention, detection, and repair of this damage, our goal was to understand the root cause of our initial problem. This research was conducted on April 26, 2026, using government websites, such as the CDC and the Insurance Institute, as well as academic journals, to obtain statistical information and to understand the root causes of mold and rooftop pollution. The search terms used were: “mold”, “roof pollution”, “ponding water”, “rooftop”. 
On May 3, 2026, our group conducted research through Google Scholar and general websites. The search terms used were: “ultrasonic sensor”, “drainage system clog detection”, “waterproof water level sensor”. Additional research was conducted on patents related to gutter designs to establish existing solutions and identify potential solutions from these patents. Research was conducted on May 1, 2026, using the Google Patents search engine, which allowed us to find various gutter patents that might be related to our problem space. The search terms used were "gutter solutions," which led us to a link that provided the specifications and patent for the rain gutter screen. On May 6, 2026, our group conducted research through Google Patents and the USPTO public patent database. The search terms used were: "gutter monitoring apparatus," "gutter clog detection IoT," "gutter overflow sensor." Material selection research was conducted on May 21, 2026, through Google Scholar and general websites. The search terms used were: "polycarbonate filament outdoor use," "PC filament heat resistance," and "best 3D printing filament for outdoor applications."
BA.3 Results
Impact of Mold and Roof Pollution
	According to a CDC study, 47% of residential buildings in the US contain mold, contributing to higher rates of asthma and respiratory diseases [1]. There are a variety of mold species that are caused by many factors, including dust, moisture, and roof leaks. Mold is prevalent across the US [3]. While most molds are not harmful to human health, extended exposure to indoor mold can cause symptoms such as asthma, mood changes, and weakened immune systems [4]. These damages are often expensive to repair, impacting many families in the US [1].
	Many factors can cause mold growth in households, ranging from environmental conditions to household behaviors. A study at the University of Cincinnati found that air conditioning, carpet, the home's age, the current season, and dust mites can all contribute to mold growth [3]. Because these characteristics are associated with lower-income households, this research suggests that lower socioeconomic position is associated with moldier homes [3]. 
A major cause of mold is water damage. Around 14,000 people in the US are affected by water damage daily, and 29% of all home insurance claims are due to water damage and freezing [4]. The most common causes of water damage are severe weather, clogged gutters, and leaking pipes [4]. These issues leave many Americans with high repair costs and little insurance payouts. Roof pollution can also cause mold by blocking drains and damaging roof coatings, leading to leaks and water buildup [4]. Ways to control mold in a household include monitoring humidity with a hygrometer (which measures humidity as a percentage), running exhaust fans, and installing outdoor drain pipes [5]. However, many homes lack these measures [5].
	Ponding water is any standing water that remains after 48 hours. One inch of ponding water can weigh more than 5.2 pounds per square foot. [6] While ponding water affects the actual load on the building, it also affects the environment and the building's coating and can cause mold within the building. The stagnant water itself promotes the growth of algae and mold, compromising the integrity of the coating and raising health concerns for those inside. [6]
Current Solutions
Humidity is an issue that can lead to mold, so companies such as SEMCO Inc. have developed packaged rooftop units that can independently maintain both temperature and humidity while delivering any desired outdoor-air percentage, working closely with the U.S. Department of Energy and Oak Ridge National Laboratory [2]. This device was then used to target a particular audience of Timber Ridge Elementary School in suburban Atlanta [2]. The classroom had a relative humidity above the 60-percent guideline, with this percentage rising to 70 or even 80 percent after implementing an HVAC system to cool the room [2]. With the implementation of the unit developed by SEMCO Inc., the humidity level dropped below 50 percent, making it much more bearable for the students at the elementary school [2].
Another solution was developed in Africa, as a study observed how people in Owerri were attempting to store rainwater collected from rooftops [7]. There were three main storage vessels utilized: plastic, metal, and earthenware pots, and block/cemented tanks [7]. The roofs were also made of different materials, as some were stone-coated while others were aluminum, introducing different potential contaminants that could be displaced from the rooftops by rainwater. Through examining the solution that the Owerri people were attempting by using these storage vessels to catch the rainwater, the study concluded that the vessels themselves were contaminating the vessel water more significantly than the rooftop pollutants, as bacterial organisms in these vessels such as E. coli are resistant to antibacterial drugs, making bacterial contamination from the vessels much more harmful than the physicochemical properties of the rainwater harvesting the rooftop contaminants in Nigeria [7]. 
Regulatory Concerns
The US Environmental Protection Agency (EPA) currently states that there are no set standards for mold-detecting devices or consumer-level purification devices [8]. The Illinois Department of Public Health (IDPH) also states that testing is not necessary if mold is evident in homes, and that there are no standards currently in place that define acceptable levels of mold in homes or even limit the utility of testing devices for mold [9].
Gutter Research
Some solutions could help prevent mold or improve rainwater drainage through gutters. This is a preexisting solution, yet there are still limitations to this system due to overflow, backflow, degradation in quality over time, and other issues that stem from environmental factors. A group in Europe, composed of Italian and English researchers, developed an alternative to gutters in the form of a “sponge” [10]. Using mineral wool, this “sponge” collects water and slowly releases it over time, preventing overflow and water pooling in the gutters during heavy rainfall [10].
Sensors
Ultrasonic sensors measure distance by emitting a 40kHz sound pulse and recording the time taken for the echo to return. In the research paper “Smart Drainage Monitoring System and Clog Detection with IoT,” the authors used an ultrasonic sensor to detect changes in water level in drainage systems. When a clog is detected, the water level rises, reducing the distance reading and flagging the system. This is a similar use case to gutters and has proven effective [1]. Another reason ultrasonic sensors were chosen was that they measure water level without submerging any components [2].
Other sensors were researched as well like contact sensors. Contact sensors are susceptible to corrosion, biofouling, mechanical wear, and contamination [3]. Float switches detect water level by rising and falling with the water, but moving parts can get stuck or damaged, requiring regular maintenance [3]. These other sensors have moving parts or are in contact with water, leading to decreased longevity and increased repair risk [3].

Ultrasonic Sensors
To determine which ultrasonic sensor to use, we had specific criteria for durability, MCU compatibility, and price that all had to fit. For resolution, a sensor with a lower blind zone distance was necessary. A blind zone distance is the range in front of the sensor where unstable output can occur [4]. For a gutter, specifically, around 3 centimeters was desired to ensure accurate readings. Because the sensor is outdoors and exposed to rain, a sealed housing was desired. The ultrasonic sensor is ideally compatible with an ESP32 MCU. Due to budget limitations, we set our restraints to around 20 dollars. We ended up choosing the PWM DC5V Ultrasonic Sensor. 
Rain Screen Gutter
The objective of this invention is to provide an improved gutter screen design that facilitates the separation of water from foreign matter and improves the method of installing the gutter screen at the gutter interface. The system also provides orifices to accommodate draining the minor water defection caused by dew []. The gutter is installed by providing a depth gauge to determine the placement of the leading edge of the screen beneath the end shingles or other roofing material at the roof edge, and means for attaching the discharge edge of the screen to the side and outside edges of the gutter [].

Figure rat. The top sectional perspective view of an installed section of gutter screen
Gutter sensing patents
Five patents were identified covering gutter monitoring and clog detection. One patent has a roof mounted sensor combining ultrasonic sensors with a camera in a single housing [1]. A companion method patent covers a software workflow that separates a debris height from a liquid height to compute the remaining flow depth, and generates a maintenance schedule against a flood risk threshold [2]. A third patent disclosed an early electronic gutter overflow sensor with a solar panel, rechargeable battery, and wireless transmitter [3]. However, this patent lapsed in 2008 [3]. 
Patents and our design
The two active high risk patents are both assigned to HD Sharman Ltd. The risk in the
first patent is the joining of the camera and the sensor, by removing the camera entirely from the detection unit eliminates infringement [1]. The risk in the second patent is the predictive scheduling algorithm, a simple threshold based alert does not separate debris from liquid heights and does not generate a maintenance schedule, placing it outside the claim [2]. 
Material Selection
PC filament outperformed alternatives across all categories for outdoor enclosures:
Heat resistance: PC maintains structural integrity up to ~110–150°C, far exceeding PLA (~60°C), which would deform on a sun-baked roofline
Impact resistance: PC absorbs sudden impact energy without cracking, making it resilient against falling debris or hail
UV resistance: PC offers strong UV radiation resistance, preventing degradation and discoloration from prolonged sun exposure
Chemical resistance: Resists oils, greases, and solvents, relevant for gutter runoff containing organic debris
Electrical insulation: As an effective electrical insulator, PC provides passive protection for the enclosed ESP32 and ultrasonic sensor circuitry
BA.4 Discussion 
Constraints
Due to the lack of any standards for mold detection and remediation, any proposed solution we come up with will not have a benchmark to compare with [8]. Another constraint is cost. Mold disproportionately affects lower-income households, so any solution must be accessible and affordable. With solutions already in place, our solutions must be feasible to install. If the solution involves water retention, it must account for the load-bearing capacity of the existing roof. 
Sensor Limitations

Ultrasonic sensors are not without limitations. Ultrasonic sensors all have a blind zone as mentioned earlier, and need to be mounted at specific heights. Additionally, heavy rainfall can interfere as the scattering water droplets can affect readings, this requires a filter to get proper readings. [2]
Rain Screen Patent
This patent introduces a rain mesh blocking system that helps filter the pollutants or byproducts of rainwater down a roof. The attachment pieces of the installation process could help us determine how to attach our sensor, as we could come up with a similar but not the same attachment piece that is shown in Figure rat (see labeled 7 on Figure rat). We could also use the gutter drawing drawn in Figure rat for our gutter mock up, as we would need a gutter of some sort that would be able to test the sensor that we are trying to make. 
Gutter Sensing Patent Limitations
Both HD Sharman patents are active and broadly claimed, meaning any pending continuations that have not yet been published may expand [1][2]. Due to the fact that one patent protects a method rather than a device, the algorithm needs to be changed rather than just physical features [2]. 
Material Limitations
	PC is not perfect, it requires elevated print temperatures and one needs to prepare the filament carefully before printing. PC also does cost more than PLA or ABS.

Part B: Interview with Contractor
BB.1: Introduction
	To gather more information about our problem space, we conducted an interview with Chris from Hudco Construction LLC, a contractor in Northern Louisiana who works with floods and water damage daily. This interview was conducted by Sahej, who focused on current solutions and the faults that he faces every day. Topics discussed include foundation issues, roof leaks, gutter damage, and humidity issues.
BB.2 Methodology
	This interview was conducted on April 22, 2026, at 3:00 PM over the phone. A list of questions was produced by the team collectively and then asked by Sahej. During the interview, notes were taken on the important points, and the call lasted 30 minutes and was recorded to ensure no information was missed.
Chris contractor questions *was not sure how to link
BB.3 Results
Flood Damage and Structural Effects
	As a contractor from Louisiana, Chris often sees foundation issues caused by flooding and clay-heave soils in the area. Clay soil can cause cracks in the home foundation, as well as shifting and settling, which is why he considers it one of the hardest and most serious repairs. He also discussed how flood levels of about 2 to 12 inches inside a home require removing the lower section of a wall’s drywall and insulation to dry out the structure. 
	To prevent this messy, labor-intensive process, home builders can make certain materials and design choices. Vinyl plank flooring and many types of tile are more durable and water-resistant, though they still must be removed if foundational damage occurs. In terms of structural considerations, contractors can add galvanized metal studs to the bottom of a home, but these are still susceptible to rust. There is also often a bottom seal plate installed in the foundation of homes, but the treatment on these wood plates can degrade over time, leaving them susceptible to mold and rot. Overall, prolonged exposure to moisture can damage both studs and the structural framing of homes.
Roofing Materials and Performance
	Another susceptible area of the house is the roof. Chris emphasized that roofs are among the most dangerous areas for water damage because homeowners often overlook them. Also, visible signs of roof leaks do not become obvious until they have caused serious damage. There are two types of damage to shingled roofs (the most common): granule loss and exposed fiberglass. The loss of granules is visible around the house, especially on concrete, and exposed fiberglass creates bleached spots on the roof, which are a sign of roof aging. However, there are ways to mitigate this degradation.
The best roofing material for harsh environments is metal roofing, which is not as common in homes. These roofs are more durable in general, but they can still sustain dents from large hail events. There are also many synthetic roofing slates made from an ABS/vinyl composite. These expensive slates have a long lifespan and are strong against rain and hail, but they are vulnerable to wind uplift because they are not securely fastened to the roof.
Other than the roof, windows and wall penetrations are among the most critical weak points in a home. Similarly, there are systems in place to waterproof these areas. Chris explained that the traditional system used is a Tyvek house wrap, which is both breathable and water-resistant. However, these can have tears and rips, which is why a newer ZIP system has been created. Chris said these are more beneficial because the coating seams are taped, but they are more common in Northern areas.
Gutter and Drainage Issues
	A key part of controlling water on a roof is the gutter system. Chris discussed that the basic design of a gutter usually allows water to flow outward because the edge connected to the roof is higher than the outside edge. However, a key cause of failure is water flowing behind the gutter, which leads to fascia rot. If this area is exposed to water over the long term, water travels along the soffit and into the walls, causing mold. Additionally, if the downspouts from these gutters drain near the home's foundation, this can cause mold and foundation damage.
Mold Growth
	The common causes of mold growth that Chris encounters are slow roof leaks and poor HVAC ventilation. He explained that older homes in Louisiana often have their air handlers in closets rather than the attic, which can lead to poor airflow and mold. A modern solution to air ventilation problems is a variable-speed HVAC system, which has built-in dehumidification and automatically activates above 40% humidity.
	Chris also said that the most common areas for moisture problems are bathrooms and under sinks. If these problems go uncleaned, mold can spread into other parts of the home, causing health issues. Modern security companies like Vivint and SimpliSafe have created moisture and leak sensors for these areas, but these are expensive for homeowners and have a small detection range.
BB.4 Discussion
	Overall, Chris pointed out many foundational issues in homes that can be very harmful if left undetected. Most of these problems occur in older, outdated homes, which are common in the southern US. New technologies are being developed to help homeowners detect and prevent mold and water damage, but they are often expensive and not widely known. Therefore, our project should focus on being accessible to homeowners whose homes lack newer technologies.
Part C: Interview with Local Hardware Stores
BC.1: Introduction
To narrow the scope of our problem space and gain more insight into how mold is affecting homes in Evanston, we decided to contact multiple in-person sources who are experts in the area. Two members of our team conducted interviews with local experts on prevalent mold issues and consulted them on which direction they would see fit for our project to explore.
BC.2 Methodology
Alex and Euvene went to local hardware stores in Evanston—Lemoi Ace Hardware and Lowe’s —to consult the employees there about mold prevention, mold remediation, current solutions, and areas where they think improvements could be made. They went at around 3:00 pm on April 21, 2026, spending about 90 minutes on the interview and getting to all the stores via Lyft. The notes were recorded on Euvene’s phone, while Alex came up with the questions on his phone to ask the hardware experts. The gentleman who offered time to speak with us at Ace was Scott Evans, and the employee at Lowe’s was Mike.
BC.3 Results
Current solutions
Scott immediately mentioned, when we came up to him about mold issues, providing a spray containing a solution known as concrobium (See Figure dog). This solution is popular for mold removal because it is relatively simple to apply. The solution can be sprayed onto the area of mold growth, then wiped off with a paper towel, and the process repeated until the mold is completely removed. Scott did mention that mold is more destructive to drywall than to plaster, which is actually a good thing for most Evanston homes, as they are made of plaster walls. This was the only solution Scott could mention to us, and Mike didn’t provide another solution at Lowe’s other than introducing a different brand of concrobium.
 
Figure dog. Concrobium brand shown at Lemoi Ace Hardware Store

Figure cat. Concrobium brand shown at Lowe’s
Prevention
This was a question that stumped both of the individuals we interviewed, as there is truly no way to prevent mold from growing in Evanston homes. We live next to a large body of water, so moisture levels are high in this area, making mold inevitable. There are HVAC systems and filters installed in most homes that help reduce moisture levels and reduce the prevalence of mold, but there is truly no way to prevent mold from growing or appearing in homes.
Causes for Mold
Our conversation with Scott led us to learn a lot more about how mold forms in homes. Apparently, mold is most prominent in bathrooms and basements. Bathrooms made sense to us because there is a lot of moisture, especially after showers or baths. However, the topic of basements led us to discover that rainwater actually leaks through the ground and hits the groundwork of most homes, which is made of clay. The clay is incredibly dense, so water is displaced from the clay and travels down the home and into the basement, which then causes puddles to form in the basements of homes, making them susceptible to mold. There are solutions for this particular issue as well, such as shields (often made of plastic) that block water and prevent flooding in basements.
BC.4 Discussion
The insights we gathered from this primary research at the hardware stores were rather helpful, as we identified new issues or gaps we could explore as we continue to narrow down our problem space. Mold prevention is completely out of the question, as it's not possible, particularly given our remaining 6 weeks. We should look into areas such as the leaking water in the basement and provide an alternate solution to the plastic shields that are already in place. Rooftop filtering is another space we can focus on. We can create a mechanism to clean the gutters, which could be more affordable than existing solutions.
Appendix C: Safety Evaluations and Ethical Concerns
H.1 Introduction
While developing a prototype of the final design, many ethical and technical safety questions arose. To address these concerns, our team developed a list of potential issues and assessed their importance in our final design.
H.2 Methodology
To evaluate the design for safety and ethical issues, our team first brainstormed potential safety issues that could arise. These concerns were compiled into a Google Sheet, along with their implications, frequency, impact, and risk rating, as shown in Table GIRAFFE. Then, these concerns were used to iterate on the design.
	Link to safety evaluation: Safety Evaluation
Next, the top three ethical concerns identified during brainstorming were evaluated for their impact on American homeowners. Then, design iterations were developed to address these concerns.

Table giraffe. List of Safety Concerns and Implications 
H.3 Results
Ethical Concerns:
False readings and reliability
The sensor we employ on the gutters may be faulty at times, and external factors such as heavy rainfall can hinder its accuracy by exposing it to excessive water and affecting its position on the gutter. The flow rate is detected based on the angle, which can change due to external weight from rain. Other factors could be from animals, such as squirrels, that might come in contact with the sensor. Our response is to create a secure attachment piece that ensures the sensor is securely mounted on the gutter. Our idea is to 3D print a gutter enclosure that the sensor would sit in, with minimal interaction with external factors.
Environmental Concerns
The sensor we will be making requires batteries to function, which raises some environmental concerns. Batteries generate electrical waste, which we are trying to address within our given problem space. If time allows, we can change our solution's power source to explore the use of solar panels. This could help address the ethical issue of electronic waste and reduce battery use.
Over-reliance on automation 
With these sensors and an app that lets users track gutter condition, there may be over-reliance on the app, leading people to stop monitoring gutter quality. This could be an issue if readings are inaccurate. To solve this problem, we can add a feature to the sensor that provides an estimate of the reading's accuracy, such as “Your gutter is in x condition, 70% accurate.” This will prompt the owner to inspect their gutters in person, or at least have someone check them, limiting reliance on the sensor and ensuring at least a yearly check to verify the product is working properly and that no problems are apparent on the gutters.
Safety Concerns
	As shown in the table in GIRAFFE, many safety issues can arise from implementing this design. The sensor could be damaged by ice, debris, and high winds. This can be prevented by waterproofing the enclosure to improve its weather resistance. Additionally, the sensor could produce false readings due to water splashes and debris blockages, causing homeowners to have false concerns. Because of this, future iterations of the design could include a color sensor and a threshold for consecutive readings to ensure reliable readings (see Appendix __: Future Development). Lastly, users with limited mobility could struggle to install the device or do so incorrectly. Because of this, the design requires construction instructions to prevent installation mistakes.
H.4: Discussion
	After carefully considering all safety and ethical considerations, our team has decided to apply silicone waterproofing to the sensor enclosure to help prevent weather-related damage. Additionally, installation instructions will be included with the product distribution to help prevent incorrect angles when reading.


Appendix D: Instructions for Construction
G.1 Materials and Equipment
The following table lists all the materials needed to build the GutCheck Sensor.
Table 1: Materials Used for Construction
Material
Specifications
Quantity
PC Filament


1 kg
Bolts
M2 (X’X)
4 (?)
Threaded Inserts
M2x4
4 (?)
Wire
16 AWG
?
Silicone Seal Strip
2mmx6m
1







Note: See Bill of Materials (Appendix H) in report for details on cost and part numbers
The following tools/equipment are required to construct the device
3D Printer
Phillips Screwdriver
ESP32 DevKit
Ultrasonic Sensor
Waterproof Battery Holder
G.2 Enclosure
Download the STL files for the enclosure from our official website (also available in Google Drive).
Then slice it in any 3D printer slicer of your choice and print it using polycarbonate (PC) filament. Please refer to your filament and printer instructions for specific printing settings. A few things to note:
PC filament easily warps. It is recommended to use an enclosed printer
PC filament is hydroscopic. It is recommended to dry the filament prior to printing
G.3 Sensor and Battery
Take the ESP board and connector pins out of its anti-static packaging. 
Use a soldering iron to solder the connector pins to the ESP DevKit such that each GPIO pinhole has a connector extruding out of it.
Use female-to-male Dupont jumper wires to connect the pins labeled 16, 17, 3V3, and GND to the four pins of the ultrasonic sensor as shown in diagram below.



Use a 28-gauge wire stripper to cut 5 mm of wire insulation off the two ends (red and black wires) of the battery container.
Solder the (power and ground) exposed copper cables from the two ends of the battery container to the male end of a female-to-male DuPont jumper cable.
Connect the female end of the red cable from the battery pack to the GPIO connector pin labeled 3V3.

Figure X: ESP32 Pins
Connect the black cable of the Dupont jumper cable that is connected to the black end of the battery pack. The black wire of the battery pack to the male connector of the GPIO pin labeled GND. 
Insert 3 AA batteries into the battery container. 

Use the screws and nuts provided in the packaging to seal the four screw mounts and the four screw holes of the battery container. 

Figure X: Lid Screws
G.4 Final Assembly
Take the lid of the enclosure and flip it such that the extrusion, the rectangular extrusion, is facing upwards towards you. 
Take the ultrasonic sensor and route the cable output through the small cutout within the rectangular border on the lid. This should fit very snugly within the rectangle. Make sure that the two circular objects on the sensor (the transceiver and receiver of the ultrasonic sensor) are extruding out of the two holes on the bottom of the lid.
Take the ESP DevKit with the wires and insert the board with the long end of the connector pins facing away from the lid cut out of the enclosure. 

Figure X: Components in Enclosure
G.5 Waterproofing
Take the silicon tube and cut out 12.3 inches.
There should be a small lip around the lid insert. Glue gun and cover the corner edges with glue.
Measure out the silicon tube and line it against the glue along the edges. 
Add more glue between the two ends of the silicone tubing to make a complete connection.
Flip to the side of the lid where the circle cutouts are. 
Repeat step two on the small lip insets for the sensor's transceiver and receiver modules. 

Figure X: 
G.6 Website
Power on the two battery packs with a button on the top side. Should be depressed to indicate that power is flowing
Connect to the dashboard section of our website and wait ten seconds. Under Pairing, there should be devices that appear in the list.
Find the corresponding devices using the pairing sequence as a script on our website.


‌Appendix E: Mockups and Testing
C.1: Introduction
Given our problem space of gutters, our group decided to build a sensor to detect clogs. Our current mockup is called the Gutter Clog Detector.
C.2: Methodology
On May 2, 2026, we purchased a sensor on Amazon. On May 6, 2026, we purchased an additional sensor, two waterproof battery holders, and two ESP32 Dev Kits. We obtained a breadboard from Northwestern’s Electrical Engineering Lab. We ran the firmware to test whether the sensor would meet our needs. On May 7, 2026, we 3D-printed the sensor enclosure at the Ford Makerspace. On May 6, 2026, we conducted website testing with different student groups to assess appearance. On May 8, 2026, we ran testing using two different water buckets to measure the differential pair. On May 19, 2026, we ran testing using a 5-foot-long gutter section and a hose to test different scenarios.
C.3: Results
Sensor
Initially, we hooked the ultrasonic sensor and ESP32 to the breadboard to get basic readings and ensure the sensor would work. 

Figure 1: Initial sensor testing
After receiving the second ultrasonic sensor, we wired everything up and tested to confirm that the differential pair would work. The ESP32 Dev Kits host their own servers, and we were able to receive data from both to create the differential measurement. The website was able to detect the differential measurement, showing us that the sensors did in fact, work. With a differential measurement, we can eliminate the caveat that a single sensor provides, its dependency on gutter specifications. With two different measurements, the logic that the difference should be minimal is sound. 

Figure 2: Differential pair testing
	
Sensor Requirements Met
The main requirement we were testing for was clog detection. We used a single waterproof ultrasonic sensor to detect changes in water level, but were unable to measure the flow rate as we had hoped. With a single ultrasonic sensor, many assumptions must be made to determine whether a clog occurs. As a result, we determined that another sensor placed further down would create a differential measurement, giving us a more accurate reading. 
Initial Sensor Testing
No object (base case)
Used the flat back of a breadboard to simulate a “flat” reading (results displayed in Figure 1)
Used the palm of the hand to simulate a non-flat surface (results displayed in Figure 2)

*All figures below are Serial data output from ESP Devkit. Values are listed in the order: wave pulse (us), calculated distance (cm), calculated (mm), finalized distance (cm_moving_average)

Figure 3: No object (needs fixing)

Figure 4: Reading of back of breadboard (stationary + moving)

Figure 5: Reading of palm of hand (stationary + moving)
Sensor Testing
We then tested with both sensors. To test we used two different buckets of water, once with the same volume of water, and again with a different volume. The ultrasonic sensors were able to detect the water as well as the differential measurement. The website provided good data.

Figure 6: Differential testing (clear)

Figure 7: Differential testing data (clogged)

Testing with Gutter
After testing with the actual gutter portion, we realized that a threshold was not the way to go. We ran the tests in a few different situations, different flow rate, an unclogged gutter and a “clogged” gutter. The “threshold” that we found was around 2 to 2.5 cm. However,  what we determined was that rather than having a set threshold for what is considered clogged, a spectrum would be best in describing the gutter’s status. The flow of water and the flow rate are too different. For example, even if an object is detected, it could not affect the flow of water. Rather than using a set threshold, a spectrum can deliver more accurate readings to the user. 

Figure 1: Testing setup

Figure 2: Differential measurement with T = 2

Figure 3: Differential measurement with T = 2.5

Figure 4: Differential measurement with T = 3.5
As you can see, when the threshold was 3.5, there were points where obvious blockage was not outputting as a clog. At 3.5, the water level rose too high, so we had to stop testing. 
Enclosure

Figure 8: Enclosure CAD sketch
The enclosure mounting style was inspired by the Gutter Hanger (See Figure 9). The gutter hanger is used to secure the rain gutter to the fascia of the house. We thought that by our enclosure replacing a gutter hanger and mounting it in the same method, the sensor would be more stable, as well as still secure the gutter itself. 

Figure 9: Gutter hanger
The design requirement of being secure can be met by this style of enclosure and mount. The enclosure would be 3D printed, sealed, and bolted. The enclosure would be bolted to the fascia board (a solid board behind the gutter). This would assist in accurate readings and stability.

Figure 10: Enclosure 3D print
Enclosure Iteration
	Our first enclosure had a few problems. The enclosure had no mounting spots for the sensor, making it unreliable. For this iteration, we added slots for the ultrasonic sensor to sit in, built into the lid itself. We also reduced the footprint itself, making it smaller. The angle for the bolt was off, so we changed that as well.

Figure : Enclosure Version 2

Figure : Enclosure Lid Sketch

Figure: Enclosure Bottom View

Figure: Enclosure Side View
Final Enclosure
	For our final version of the enclosure, we were able to decrease the footprint of the entire enclosure by around 60%. In this final iteration, we moved the wire entrance to the top, waterproof sealed the lid using a silicone strip, used heat-set inserts to mount the lid, and printed using PC filament.

Figure X: Waterproof Seal

Figure X: Wire Entering Enclosure

Figure X: Heat Set Inserts for Lid
Enclosure Testing
To test the enclosure, we purchased a section of gutter. We then placed the enclosure on top of it. While the enclosure sat nicely on it, the angle to bolt in is not feasible and will be changed in the next CAD. We also discovered that the sensor slot that was initially created was a bit too small to fit the sensor. In future iterations, we will also be adding proper drill holes for the other components.
Website Design
	To develop a website design, two different simplistic designs were developed as shown in Figures 11 and 12. 

Figure 11: Website design mockup one

Figure 12: Website design mockup two
	These mockups allow the user to understand the flow rate in their gutters without checking their roofs, providing a simple, easy-to-use solution. Both options present the data that will be imputed by the sensor (for now, this is a text input). This will allow the device attached to users’ roofs to communicate with American homeowners. Figure 11 is simpler, allowing the user to clearly see the data, while Figure 12 adds a graphic to more aesthetically display the results to the user.
Website Testing
	To test the effectiveness of the two graphics, interviews were conducted with select focus groups to determine which would best help users understand the information.
	The first group was a Northwestern student cohort with diverse majors and passions. A majority of participants stated that the droplet graphic in Figure 12 provides a more professional look and can increase participation on the website. Because it is more aesthetically pleasing, they believe users will be more inclined to check their gutters, thereby increasing their awareness of clogs.
	The second group will be a group of Northwestern engineering students, who will be able to provide insight into design ideals and the clarity of both graphics. They stated that a simple display of the numbers is more effective at getting the point across. They also said that the water droplet could mislead users into thinking the number is a percentage, while it provides a pleasing graphic. Additionally, it was mentioned that the users will not understand the number as much as a normal, high, or low flow rate. Therefore, the normal or indicator word should be more of a focus than the flow rate number itself.
After receiving all the feedback, we ended up with this design:

Figure 13: Website design after testing
C.4: Discussion
Sensor Insights
The sensor is able to detect the water itself rather than the reflections
Two sensors were able to connect to each other, giving us a differential measurement that is a better fit for our project.
We still need to find the right threshold or have the users calibrate when installing.
We need to perform more testing on what is “clogged”.
For testing and getting better data, we will get a portion of the gutter to test on.
We need to think about what to do when debris is sensed
Really focus on determining metrics
Enclosure Insights
The enclosure space was a bit too tight for the sensor to fit
We need to CAD the mounting holes.
We need to adjust the angle in order to allow the bolt to go into the fascia.
Use silicone to seal the components
Website Insights
The website graphic should place more emphasis on telling the user the health of their gutter rather than the flow rate, while providing a visual to make it more appealing.
An additional page with the data we see in the backend would be nice for users who want




Appendix F: Design Review Appendix
G.1 Introduction
	After developing an initial sensor prototype, our team presented the project's current status and plans to classmates, professors, and an electrical engineer to gain insight into potential setbacks and solutions. From these insights, our team developed a plan to create a final deliverable and implement some aspects of the project in future development. 
G.2 Methodology
	On May 12, 2026, DTC Section 6 Team 2 presented their current project status, including sensor logic, a gutter enclosure, and website design, to classmates, professors, and an electrical engineer. The presentation included images of our initial sensor design, which was also shown to the class in person. Additionally, we were able to show the sensor's current data output layout and how we plan to use it to detect a clog. Lastly, we shared the results of our website design iterations and our current design plan to solicit additional feedback.
	Link to presentation: Design Review Team 6.2
G.3 Results
Sensor Design
A large part of the questioning about the sensor design focused on generalizing the current logic to different gutters and home designs. These concerns included accounting for differences in gutter depths, lengths, widths, and sensor spacing. Additionally, it would be important to understand how the sensors respond to different kinds of debris, such as a fully flooded gutter versus a stray twig directly in front of the sensor. It was also said that a specific differential value between the sensors should be tested to determine when there is a clog and what a normal value is. A key piece of feedback was that these differences indicate the final deliverable should be calibrated to a specific section of the gutter.
Enclosure Design
After reviewing the printed sensor enclosure and its attachment mechanism, it was decided that the current prototype does not have enough space to drill a hole and attach it to the gutter to mimic a gutter hanger. Different waterproofing options were also discussed, including silicone and a company that makes custom waterproof enclosures for electronic devices. This is an important consideration, as the sensor will be vulnerable to rooftop debris and other weather conditions.
Website Design
Lastly, feedback was received on the current website mockups. The students much preferred this design to previous mockups and stated that keeping a simple design is preferable to users. Although they stated that an intermediate option between normal and low would allow for leeway in the design and provide a more accurate description of the sensor reading. 
G.4 Discussion
Overall, our team’s main objective after the design review was to center the final deliverable on a specific piece of gutter rather than generalize metrics across all homes. This will enable a more feasible design over the remaining three weeks, resulting in more accurate data collection and testing. Additionally, we must specify metric values in our project definition so that we have defined goals during testing. Moving forward with the project, the enclosure will be reprinted with a larger attachment space, and a third data presentation option will be added to the website.
Appendix G: Website Usability Appendix
J.1: Introduction
	After developing the GutCheck website, our team decided to test its functionality with users. This was important for validating the developed design concept and identifying any potential glitches or unintended utility issues.
J.2: Methodology
	To test the usability of the GutCheck website, the Figma preview of the website design, which allows use without a connection to the sensors, was sent to fellow DTC 2 students along with a Google Form. This Google Form contained questions about button functionality, design aesthetics, and any unforeseen glitches. The responses were collected and analyzed to assess the overall usability of the GutCheck website.
	Link to Google Form: DTC Team 6.2 Website Usability Testing
 J.3: Results
	Although very few responses were received, the functionality of the “See more data” button was verified, which allows the user to open a separate page with their raw data. The overall aesthetics of the website were well received, and users who saw earlier iterations of the design appreciated the changes made (See Mockup Appendix). However, users who were not familiar with the design did have some confusion about the explanations of the indicators on the website and suggested that a more in-depth explanation of what a “good” indicator means would be helpful.
J.4: Discussion
	The results of the usability testing show that the website is functional for its basic uses and contains no unforeseen glitches. Additional testing when the website is connected to the sensor will be necessary to verify this, but it pertains specifically to the user interface. Users were pleased with the website's aesthetics and graphics, so no design changes are needed. Moving forward, our team will provide more in-depth explanations of the indicators, but it is also important to avoid overwhelming users with too much information.









Appendix H: Bill of Materials
Item
Specifications
Quantity
Cost
Link
Battery Holder


2
$14.64
Battery Holder
ESP32 DevKit


2
$19.89
ESP32
PC Filament


1 kg
$29.99
PC Filament
Bolts
M2x8
1 bag
$6.89
Screws
Wire
16 AWG
1
$6.89
Wires
Silicone Seal Strip
2mmx6m
1
$6.99
Seal
Threaded Inserts
M2x4
1 bag
$9.99
Inserts
Total Cost




$95.28



Table X: Bill of Materials






References
[1]“Gutter Statistics: The Data You Need to Know for 2026,” N Gutter, Jan. 31, 2026. https://ngutter.com/gutter-statistics/ (accessed May 30, 2026).
[1] “Mold,” Centers for Disease Control and Prevention, https://www.cdc.gov/mold-health/about/ (accessed Apr. 15, 2026). 
[2] Advanced AC Drives Key to Innovative Rooftop Hybrid Air-Conditioning Units. https://www.proquest.com/docview/214414561?OpenUrlRefId=info:xri/sid:primo&accountid=12861&sourcetype=Trade%20Journals.
[3] T. Reponen, L. Levin, S. Zheng, S. Vesper, P. Ryan, S. A. Grinshpun, and G. LeMasters, “Family and home characteristics correlate with mold in homes,” Environmental Research, vol. 124, pp. 67–70, Jul. 2013, doi: 10.1016/j.envres.2013.04.003.
[4] H. Levine, “Mold in the home: Identifying and treating the issue to prevent health problems,” Harvard Health, https://www.health.harvard.edu/healthy-aging-and-longevity/mold-in-the-home-identifying-and-treating-the-issue-to-prevent-health-problems (accessed Apr. 15, 2026). 
[5] S. Vecherin, M. Joyner, M. Smith, and I. Linkov, “Risk assessment of mold growth across the US due to weather variations,” Building and Environment, vol. 256, p. 111498, May 2024. doi:10.1016/j.buildenv.2024.111498 
[6]“Analysis on The Impacts of Ponding water on Roof Coatings” Accessed: Apr. 16, 2026. [Online]. Available: https://www.838coatings.com/wp-content/uploads/2024/03/ponding-water.pdf
[7] Nwachukwu, M. I. Effect of Different Storage Vessels on the Microbiological and Physicochemical Properties of Rainwater Harvested from Different Rooftops in Owerri, Nigeria. https://journalijecc.com/index.php/IJECC/article/view/4015/7905.
[8] US EPA, O. Are there Federal regulations or standards regarding mold? US EPA. https://www.epa.gov/mold/are-there-federal-regulations-or-standards-regarding-mold.(5)Mold 
[9] FAQs. dph.illinois.gov. https://dph.illinois.gov/topics-services/environmental-health-protection/toxicology/indoor-air-quality-healthy-homes/mold-faqs.html (accessed 2026-04-15).
‌[10] Ludovica Bellani; Schultz, O.; Schultz, O.; Coelho, L. G. Green Gutter as a Nature-Based Solution for a Mitigation and Adaptation Strategy in Urban Environments. Integrated Environmental Assessment and Management 2025. https://doi.org/10.1093/inteam/vjaf122.
[1]V. Sneha, V. Vinay, S. Ch, and S. Phani, “Smart Drainage Monitoring System and Clog Detection with IoT.” Available: https://thegrenze.com/pages/servej.php?fn=142_1.pdf&name=Smart%20Drainage%20Monitoring%20System%20and%20Clog%20Detectionwith%20IoT&id=3117&association=GRENZE&journal=GIJET&year=2024&volume=10&issue=2
[2]“MaxBotix Inc.,” MaxBotix, 2025. https://maxbotix.com/pages/ultrasonic-flood-level-monitoring
[3]“Rika Sensor” Rikasensor.com, 2018. https://www.rikasensor.com/blog/what-is-ultrasonic-water-level-sensor-and-how-does-it-work.html 
[4]“What is Blind Area of Ultrasonic Level Sensors-Holykell-Measuring Instrument,” Holykell.com, 2023. https://www.holykell.com/What-is-Blind-Area-of-Ultrasonic-Level-Sensors.html
[x] L. Pfeifer, “Rain Gutter Screen,” United States Patent, https://patents.google.com/patent/US4959932A/en?q=(gutter)&oq=gutter
[1] M. De Rozarieux and J. Moeller-Jensen, "Monitoring apparatus for guttering system,"
U.S. Patent US 11,650,181 B2, May 16, 2023. Assignee: HD Sharman Ltd. [Online].
Available: https://patents.google.com/patent/US11650181B2/en

[2] M. De Rozarieux and J. Moeller-Jensen, "System, method and apparatus for controlling
the operation of detection and monitoring apparatus for the condition of guttering and/or
roofs," U.S. Patent US 12,159,266 B2, Dec. 3, 2024. Assignee: HD Sharman Ltd. [Online].
Available: https://patents.google.com/patent/US12159266B2/en

[3] A. S. M. Aleali, "Gutter overflow detection device and system," U.S. Patent
US 6,786,091 B1, Sep. 7, 2004. [Online].
Available: https://patents.google.com/patent/US6786091B1/en




