##Robotic Swarms: Distributed Coordination Without Location

**Presentation**: http://martinrogalla.github.io/SurveyRoboticSwarms

##Authors

**Bas Metman** S.P.Metman@student.tudelft.nl

**Sjoerd van Bekhoven** svanbekhoven@gmail.com

**Martin Rogalla** M.J.Rogalla@student.tudelft.nl

##Supervisors

**MSc. Andreas Loukas** http://www.st.ewi.tudelft.nl/~loukasa/ | HB 09.030

**dr. Andrei Pruteanu** http://www.st.ewi.tudelft.nl/~andrei/ | HB 09.070

##Objective
The majority of algorithms for distributedly controlling large networks of robots, commonly referred to as swarms, are either location- or range-based. This means that each robot decides on its actions based on its own position and on the position of and/or distance to "near-by" robots. For example, in the multi-robot path planning problem robots cooperatively plan their movement so as to visit a set of known locations in minimal time (location-based algorithm). Similarly, in the dispersion problem, robots try to maximize the distance with their neighbors while maintaining them inside the communication range (range-based algorithm). 

We have to note that, obtaining precise location information is feasible, but also "expensive". Localization requires complex hardware that drains a considerable amount of energy (GPS transceivers  infrared/laser range-finders, Kinect-like video cameras, ultra-wide band radios, etc). Furthermore, more practical localization solutions tend to lack precision.

This research project is looking for distributed algorithms which function well with imprecise location and distance information. Such methods usually exploit wireless connectivity to infer spatial proximity. Your first task is to identify the key problems that have been and have NOT been solved by location-free algorithms (comparison to location- and range-based approaches). The second task is to figure out the main algorithmic techniques underlying these solutions. 

