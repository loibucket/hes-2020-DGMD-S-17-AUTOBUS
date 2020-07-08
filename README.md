# AutoBUS/VRS: Autonomous Basic Universal Shuttle / Virtual Rail System
2020 DGMDS17 Robotics, Autonomous Vehicles, Drones, and Artificial Intelligence @ Harvard University Extension School

**Autonomous** - level 5 no human involvement, besides an emergency stop button \
**Basic** - uses single camera, no complicated LIDARs or multiple camera systems \
**Universal** - non-proprietary, can replace buses, trains, subways, etc.., quickly adjust capacity/frequency by adding/reducing number of cars running on demand, the future of mass public transit \
**Shutte** - carries people from point A to point B to point C, 

**1. Team Name: AutoBUS/VRS**

**2. Team Members and Roles:**\
Loi Cheng\
Philip Eisner\
Nathanaiel Landi\
Eric Ding\
Yikun Shen

**3. Goal of the Project:** (Describe here which autonomous navigation challenge you want to solve: example: lane following with collision avoidance, solving intersections, April tags, follow an object, slam etc...)

A proof of concept autonomous virtual rail shuttle system with a NVIDIA waveshare jetbot.  The shuttle runs on dedicated paths, and follows visual "rail" lines, instead of actual steel rails.  The project would involve building a reliable lane following system that can be operated 24/7.  Special markers at stations is recognized by the shuttle to make automated stops and departures.  The shuttle should have frontal obstacle detection and can make emergency stops as needed.  Additional features like multiple routes, express/local shuttles, hub stations, may also be implemented

**4. Software and Developing tools:**

Anaconda, Jupyter Notebooks, Python

a. include a GitHub repository

https://github.com/loibucket/autobus/

b. any other tools? (example: dropbox, google drive, slack, google collab, etc.)

**5. Hardware used:**

NVIDIA Jetson and Jetbot System with Camera

**6. Team Meeting Schedule: (tentative hours to meet with your team every week)**

As needed, otherwise use Slack

**7. List of Milestones, week by week:**

Week 1. Setting up a laptop, developing environment, build robot, operate the robot.

Week 2. Test robot basic functions.

Week 3. Protoype a lane following system.

Week 4. Prototype stations stops

Week 5. Prototype obstacle detection and auto stopping

Week 6. Demonstration

Week 7. Document results

**8. Other comments:**

**TODO LIST**\
\
All: Setup Jebot, to at least run on manual mode\
\
Have 1-2 members individually solve each sub-task\
\
*Sub-tasks, required mininum features:*\
a) Make jetbot follow a line, and design the line, ex. color, thickness, uniqueness, etc.\
b) Make jetbot recognize special markings on floor or on standing sign, and design the markings\
c) Make jetbot go, stop for x secs, and go again\
d) Make jetbot stop if obstacle is detected, start again if obstacle is cleared, (ex. another jetbot stopped at station in front)\
d.optional) distinguish between waiting for another jetbot ahead, or a person, or animal, etc..
e) Add "emergency stop" button somewhere in code\
\
*Sub-tasks, optional, advanced features*\
f) Program each jetbot to follow different color line\
g) Differentiate each station by markings, ex. name, local or express stop (stop if time is ???, else skip station, or stop if bot is local, skip if bot is express), annouce station stops over speakers...This is xx train...next stop is...transfer available to the...shuttles...\
h) Improve speed\
i) Weather situations, ex. snow, partially blocked markings\
j) Run continously, go to depot station on low battery\
k) Design routes prototypes based on some city, eg Boston red/green/blue line, NYC ACE 123 456 7, assign 1-3 jetbot to each route, assign jetbot as local or express, etc..\
l) Schedule jetbots to run different routes by time of day\
j) Automatic recharge at depot station\
etc...\
