#### A brief survey : ai in robotics


-----------
> #### Contents

- [Timeline](#timeline)
- [Misc](#misc)
- [Robotics concepts](#robotics-concepts)
  - [ROS](#ros)
  - [Kinematics](#kinematics)
  - [Perception](#perception)
  - [Controls](#controls) 
  - [DL for Robotics](#dl-for-robotics)
  - [Localization](#localization)
  - [SLAM](#slam)
  - [Reinforcement Learning for Robotics](#reinforcement-learning-for-robotics)
  - [Path Planning and Navigation](#path-planning-and-navigation)
- [Libraries](#libraries)
- [Drones](#drones)
- [Literature Review](#literature-review)
- [Startups](#startups)
- [Appendix](#appendix)


[Back to top](#contents)

-----------------

#### Timeline

[Back to top](#contents)

- [Outline of robotics](https://en.wikipedia.org/wiki/Outline_of_robotics)
- [History of robots](https://en.wikipedia.org/wiki/History_of_robots)
- [Infographic: The evolution of robotic](https://www.digitalpulse.pwc.com.au/infographic-evolution-robots-ai/)
- [ros history](https://en.wikipedia.org/wiki/Robot_Operating_System)
- [Robotics_middleware](https://en.wikipedia.org/wiki/Robotics_middleware)

----------------------------

#### Misc

[Back to top](#contents)

- [On AI and Robotics
Developing policy for the Fourth Industrial Revolution](https://policyatmanchester.shorthandstories.com/on_ai_and_robotics/index.html)
- [deloitte: AI, robotics, and automation: Put humans in the loop](https://www2.deloitte.com/insights/us/en/focus/human-capital-trends/2018/ai-robotics-intelligent-machines.html)
- [Views of AI, robots, and automation based on internet search data](https://www.brookings.edu/research/views-of-ai-robots-and-automation-based-on-internet-search-data/)
- [The Evolution Of AI And Robotics Will Be Amazing (And Painful)](https://www.forbes.com/sites/forbestechcouncil/2017/12/28/the-evolution-of-ai-and-robotics-will-be-amazing-and-painful/#272396af4597)
- [Artificial Intelligence And Robotics Will Lead To More Jobs, If We Do It Right](https://www.forbes.com/sites/forbesbusinessdevelopmentcouncil/2018/03/08/artificial-intelligence-and-robotics-will-lead-to-more-jobs-if-we-do-it-right/#4be2eec24190)
- [Global Competition Rises for AI Industrial Robotics](https://www.techemergence.com/global-competition-rises-ai-industrial-robotics/)
- [What is the role of Artificial Intelligence (AI) in Robotics?](https://www.quora.com/What-is-the-role-of-Artificial-Intelligence-AI-in-Robotics)
- [Infographics show jobs most likely to be lost to robots](https://bigthink.com/robby-berman/infographics-show-jobs-most-likely-to-be-lost-to-robots)
- [Stanford: Introduction to Robotics](https://see.stanford.edu/Course/CS223A)
- [Robot Hall of Fame](https://en.wikipedia.org/wiki/Robot_Hall_of_Fame)
- [Competitions in artificial intelligence](https://en.wikipedia.org/wiki/Competitions_and_prizes_in_artificial_intelligence)
- [MIT-TR: All Robotics stories](https://www.technologyreview.com/c/robotics/)
- [spectrum.ieee.robotics](https://spectrum.ieee.org/robotics)
- [letsmakerobots](https://www.robotshop.com/letsmakerobots/)
- [How do I learn Robotics?](https://www.quora.com/Whats-the-best-way-to-start-learning-robotics?redirected_qid=770465)
- [Free NXT Lego MindStorms NXT-G code tutorials](http://www.drgraeme.net/DrGraeme-free-NXT-G-tutorials/ChV4.htm)
- [47 Programmable Robotics Kits](http://www.intorobotics.com/47-programmable-robotic-kits/)
- [Robotics Couses](http://wiki.ros.org/Courses)
- [ETH Zurich: Institute of Robotics and Intelligent Systems](http://www.iris.ethz.ch/)
- [robotigniteacademy](https://www.robotigniteacademy.com/en/)
- [EDX Robotics courses](https://www.edx.org/course?search_query=robotics)
- [Coursera: Robotics Specialization](https://www.coursera.org/specializations/robotics)
- [Udacity ND: Become A Robotics Software Engineer](https://in.udacity.com/course/robotics-software-engineer--nd209)
- [Udacity ND: Flying Car](https://in.udacity.com/course/flying-car-nanodegree--nd787)

-------------


### Robotics concepts

#### ROS

[Back to top](#contents)

- [ROS core stacks](https://github.com/ros)
- [ROS package list](http://www.ros.org/browse/list.php)
- [Find a Robot by tags](https://robots.ros.org/tags/)
- [wiki.ros](http://wiki.ros.org/)
- [Core ROS Tutorials](http://wiki.ros.org/ROS/Tutorials)
- [A Gentle Introduction to ROS](https://cse.sc.edu/~jokane/agitr/)
- [89-685: Introduction to Robotics](http://u.cs.biu.ac.il/~yehoshr1/89-685/)


<p>ROS areas include:
</p>
<ul><li>a master coordination node</li>
<li>publishing or subscribing to data streams: images, stereo, laser, control, actuator, contact ...</li>
<li>multiplexing information</li>
<li>node creation and destruction</li>
<li>nodes are seamlessly distributed, allowing distributed operation over multi-core, multi-processor, GPUs and clusters</li>
<li>logging</li>
<li>parameter server</li>
<li>test systems</li></ul>
<p>ROS package application areas will include:
</p>
<ul><li>perception</li>
<li>object identification</li>
<li><a href="/wiki/Segmentation_(image_processing)" class="mw-redirect" title="Segmentation (image processing)">segmentation</a> and recognition</li>
<li><a href="/wiki/Facial_recognition_system" title="Facial recognition system">Face recognition</a></li>
<li><a href="/wiki/Gesture_recognition" title="Gesture recognition">gesture recognition</a></li>
<li><a href="/wiki/Video_tracking" title="Video tracking">motion tracking</a></li>
<li><a href="/wiki/Egomotion" class="mw-redirect" title="Egomotion">egomotion</a></li>
<li><a href="/w/index.php?title=Motion_understanding&amp;action=edit&amp;redlink=1" class="new" title="Motion understanding (page does not exist)">motion understanding</a></li>
<li><a href="/wiki/Structure_from_motion" title="Structure from motion">structure from motion</a> (SFM)</li>
<li><a href="/wiki/Stereopsis" title="Stereopsis">stereo vision</a>: depth perception via two cameras</li>
<li>motion</li>
<li><a href="/wiki/Mobile_robotics" class="mw-redirect" title="Mobile robotics">mobile robotics</a></li>
<li>control</li>
<li>planning</li>
<li>grasping</li></ul>


---------------

#### Kinematics

- [Kinematics and Dynamics](https://people.mech.kuleuven.be/~bruyninc/robotics/H06U9B/20170928-KinDyn-nup.pdf)

-------------------

#### Perception

------------

#### Controls

--------------

#### DL for Robotics

------------

#### Localization

-------------

#### SLAM

-----------------

#### Reinforcement Learning for Robotics



------------

#### Path Planning and Navigation

[Back to top](#contents)

- [Reflections on Designing a Virtual Highway Path Planner Part 1](https://medium.com/@mithi/reflections-on-designing-a-virtual-highway-path-planner-part-1-3-937259164650)
- [Reflections on Designing a Virtual Highway Path Planner Part 2](https://medium.com/@mithi/reflections-on-designing-a-virtual-highway-path-planner-part-2-3-392bc6cf11e7)
- [Reflections on Designing a Virtual Highway Path Planner Part 3](https://medium.com/@mithi/reflections-on-designing-a-virtual-highway-path-planner-part-3-3-a36bf629d239)


-------------

#### Libraries

[Back to top](#contents)

- [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) : Python sample codes for robotics algorithms. 
- [highway-path-planning](https://github.com/mithi/highway-path-planning) : path-planning pipeline to navigate a car safely around a virtual highway with other traffic.
- [SLAM_AND_PATH_PLANNING_ALGORITHMS](https://github.com/jfrascon/SLAM_AND_PATH_PLANNING_ALGORITHMS) : 
- [Electric-Vehicle-Route-Planning-on-Google-Map-Reinforcement-Learning](https://github.com/Dungyichao/Electric-Vehicle-Route-Planning-on-Google-Map-Reinforcement-Learning) : User can set up destination for any agent to navigate on Google Map and learn the best route for the agent based on its current condition and the traffic. Our result is 10% less energy consumption than the route provided by Google map

-------------
#### Drones


-------------

#### Literature Review

[Back to top](#contents)


#### Surveys


- [Artificial Intelligence and Robotics](https://arxiv.org/ftp/arxiv/papers/1803/1803.10813.pdf), 2018.
- [Artificial Intelligence for Long-Term Robot Autonomy: A Survey](https://arxiv.org/pdf/1807.05196.pdf), 2018.
- [Artificial Intelligence-Based Techniques for Emerging Robotics Communication: A Survey and Future Perspectives](https://arxiv.org/ftp/arxiv/papers/1804/1804.09671.pdf), 2018.
- [A Survey of Knowledge Representation and Retrieval for Learning in Service Robotics](https://arxiv.org/pdf/1807.02192.pdf), 2018.
- [A Survey of Deep Learning Techniques for Mobile Robot Applications](https://arxiv.org/pdf/1803.07608.pdf), 2018.
- [A Survey of Deep Network Solutions for Learning Control in Robotics: From Reinforcement to Imitation](https://arxiv.org/pdf/1612.07139v4.pdf), 2018.
- [Embodied Evolution in Collective Robotics: A Review](https://arxiv.org/abs/1709.08992v2), 2018.
- [Autonomous development and learning in artificial intelligence and robotics: Scaling up deep learning to human--like learning](https://arxiv.org/abs/1712.01626v1), 2017.
- [Towards Lifelong Self-Supervision: A Deep Learning Direction for Robotics](https://arxiv.org/abs/1611.00201v1), 2018.


#### RL

 - [Multi-Goal Reinforcement Learning: Challenging Robotics Environments and Request for Research](https://arxiv.org/abs/1802.09464v2), 2018.
  - Policy Gradient Reinforcement Learning for Fast Quadrupedal Locomotion (Kohl, ICRA 2004) [[Paper]](http://www.cs.utexas.edu/~pstone/Papers/bib2html-links/icra04.pdf)
  - Robot Motor SKill Coordination with EM-based Reinforcement Learning (Kormushev, IROS 2010) [[Paper]](http://kormushev.com/papers/Kormushev-IROS2010.pdf) [[Video]](https://www.youtube.com/watch?v=W_gxLKSsSIE)
  - Generalized Model Learning for Reinforcement Learning on a Humanoid Robot (Hester, ICRA 2010) [[Paper]](https://ccc.inaoep.mx/~mdprl/documentos/Hester_2010.pdf) [[Video]](https://www.youtube.com/watch?v=mRpX9DFCdwI&list=PL5nBAYUyJTrM48dViibyi68urttMlUv7e&index=12)
  - Autonomous Skill Acquisition on a Mobile Manipulator (Konidaris, AAAI 2011) [[Paper]](http://lis.csail.mit.edu/pubs/konidaris-aaai11b.pdf) [[Video]](https://www.youtube.com/watch?v=yUICAkSQTZY)
  - PILCO: A Model-Based and Data-Efficient Approach to Policy Search (Deisenroth, ICML 2011) [[Paper]](http://mlg.eng.cam.ac.uk/pub/pdf/DeiRas11.pdf)
  - Incremental Semantically Grounded Learning from Demonstration (Niekum, RSS 2013) [[Paper]](http://people.cs.umass.edu/~sniekum/pubs/NiekumRSS2013.pdf)
  - Efficient Reinforcement Learning for Robots using Informative Simulated Priors (Cutler, ICRA 2015) [[Paper]](http://markjcutler.com/papers/Cutler15_ICRA.pdf) [[Video]](https://www.youtube.com/watch?v=kKClFx6l1HY)
  - Robots that can adapt like animals (Cully, Nature 2015) [[Paper](https://arxiv.org/abs/1407.3501)] [[Video](https://www.youtube.com/watch?v=T-c17RKh3uE)] [[Code](https://github.com/resibots/cully_2015_nature)]
  - Black-Box Data-efficient Policy Search for Robotics (Chatzilygeroudis, IROS 2017) [[Paper](https://arxiv.org/abs/1703.07261)] [[Video](https://www.youtube.com/watch?v=kTEyYiIFGPM)] [[Code](https://github.com/resibots/blackdrops)]
  - An Application of Reinforcement Learning to Aerobatic Helicopter Flight (Abbeel, NIPS 2006) [[Paper]](http://heli.stanford.edu/papers/nips06-aerobatichelicopter.pdf) [[Video]](https://www.youtube.com/watch?v=VCdxqn0fcnE)
  - Autonomous helicopter control using Reinforcement Learning Policy Search Methods (Bagnell, ICRA 2001) [[Paper]](http://repository.cmu.edu/cgi/viewcontent.cgi?article=1082&context=robotics)

 
 
--------------


![ai_r](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/05-ai-in-robotics/ai_r.JPG)


------------------
#### Startups

[Back to top](#contents)

- [Robotics Startups - AngelList](https://angel.co/robotics)
- [Know Your Industries: 90+ Market Maps Covering Fintech, CPG, Auto Tech, Healthcare, And More](https://www.cbinsights.com/research/industry-market-map-landscape/)
- [Robotics Market Map: 80+ Robot Startups Working In Factories, Homes, And Hospitals](https://www.cbinsights.com/research/robotics-startups-market-map-company-list/)
- [Mining Companies Have Led On Autonomous Vehicle Adoption. Now They’re Going After The Next Phase Of Automation.](https://www.cbinsights.com/research/mining-companies-autonomous-vehicles-automation-expert-intelligence/)
- [Anti-Drone Technology: 4 Solutions Keeping Unmanned Aircrafts From Flying Where They’re Not Welcome](https://www.cbinsights.com/research/anti-drone-tech-expert-intelligence/)
- [Mr. Robot At Home: 50+ Consumer Robot Startups Helping To Clean, Cook, And More](https://www.cbinsights.com/research/robots-consumer-startups-market-map/)
- [How Google, Foxconn, GE, And Other Corporate Investors Are Betting On Robotics Startups](https://www.cbinsights.com/research/robotics-startups-corporate-investing/)
- [Robotics M&A: Acquisitions Reach New High In 2015 Boosted By Flurry Of Industrial Deals](https://www.cbinsights.com/research/top-acquirers-robotics-startups-ma-timeline/)
- [Robotics Market Map: 80+ Robot Startups Working In Factories, Homes, And Hospitals](https://www.cbinsights.com/research/robotics-startups-market-map-company-list/)
- [AI, Robotics, And The Future Of Precision Agriculture](https://www.cbinsights.com/research/ai-robotics-agriculture-tech-startups-future/)
- [Future Factory: How Technology Is Transforming Manufacturing](https://www.cbinsights.com/research/future-factory-manufacturing-tech-trends/)
- [drones-startup-market-map](https://www.cbinsights.com/research/drones-startup-market-map/)
- [The Robotics Ecosystem: Startup Funding By Category Broken Down In One Infographic](https://www.cbinsights.com/research/robotics-deals-consumer-enterprise-medical/)

--------------------------------------


#### Appendix

[Back to top](#contents)


![Rise-of-robotics-1](http://usblogs.pwc.com/emerging-technology/wp-content/uploads/2017/03/Rise-of-robotics-1.png)

----------------

![Rise-of-robotics-2-1](http://usblogs.pwc.com/emerging-technology/wp-content/uploads/2017/03/Rise-of-robotics-2-1.png)

------------

![robot_planet_2016_2](https://cbi-blog.s3.amazonaws.com/blog/wp-content/uploads/2017/01/robot_planet_2016_2.png)

------------

![Robotics_corporates_BSG_q316](https://cbi-blog.s3.amazonaws.com/blog/wp-content/uploads/2016/09/Robotics_corporates_BSG_q316.png)

-------------------

![robotics_MnA_20160818-2](https://cbi-blog.s3.amazonaws.com/blog/wp-content/uploads/2016/08/robotics_MnA_20160818-2.png)

----------------

![AI_robotics_Agriculture1](https://cbi-blog.s3.amazonaws.com/blog/wp-content/uploads/2017/07/AI_robotics_Agriculture1.png)

----------------

![robots3](https://s3.amazonaws.com/cbi-research-portal-uploads/2018/03/15191614/robots3.png)


--------------

![RnD](https://s3.amazonaws.com/cbi-research-portal-uploads/2018/03/13120644/RnD.png)

--------------

![180405-Future-Factory-V4](https://s3.amazonaws.com/cbi-research-portal-uploads/2018/04/05171259/180405-Future-Factory-V4.png)

---------------

![Drones-Market-Map-High-Resolution](https://cbi-blog.s3.amazonaws.com/blog/wp-content/uploads/2017/06/Drones-Market-Map-High-Resolution.png)

-----------

![consumer_robots_map_q3-16](https://cbi-blog.s3.amazonaws.com/blog/wp-content/uploads/2016/10/consumer_robots_map_q3-16.png)


-------------

![robotics_treemap_2016_2](https://cbi-blog.s3.amazonaws.com/blog/wp-content/uploads/2016/10/robotics_treemap_2016_2.png)

------------

![robotics_deals_category_2016_1](https://cbi-blog.s3.amazonaws.com/blog/wp-content/uploads/2016/10/robotics_deals_category_2016_1.png)

--------------

![automation-jobs-likely-to-be-automated](https://content.creditloan.com/media/automation-jobs-likely-to-be-automated.png)

------------

![automation-visualizing-the-time](https://content.creditloan.com/media/automation-visualizing-the-time.png)


--------------

![automation-the-value-of-person-hours](https://www.creditloan.com/media/automation-the-value-of-person-hours.png)


--------------

![automation-job-automation-by-education-level](https://www.creditloan.com/media/automation-job-automation-by-education-level.png)

-----------------
