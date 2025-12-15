
Link: https://cse-robotics.engr.tamu.edu/dshell/papers/icra2023obs.pdf

Characteristics of the problem: 
- A robot answers questions about its environment
- Questions are related to places 
- Questions involve conditional or contingent relationships between properties
- The system's state is partially observable
- Elements can be fully known or only within certain locations ([LOMDP](Locally%20Observable%20Markov%20Decision%20Processes))


Main Point:
- We can exploit deducible information 
- The information of the world is in a concise representation via Reduced Ordered Binary Decision Diagrams
- The main question for the algorithm guy is to choose where, when, observations should be made to capture data for certain specifications



Core Ideas: 
- We ask robots questions rather than telling them what to do
- Data acquisition exists in [information path planning](Nonmyopic%20Adaptive%20Informative%20Path%20Planning%20for%20Multiple%20Robots.md) and [information gathering](Sampling-based%20otion%20Planning%20for%20Robotic%20Information%20Gathering) - They are good at getting large quantities of data
-  Rather than useful aggregated statistical analysis of data - let's get the finer relationships directly from the world
- The problem is similar to a fields in **active sensing, sensor selection, triage of captured data**
- The knowledge acquisition family is close cousins of **EQA** - of which Shell's work involves "perceptual challenges" - issues with perceiving


Active Sensing:
* [[Planning to chronicle: Optimal policies for narrative observation of unpredictable events]]
* [[Particle filter based information-theoretic active sensing]]
* [[Online optimal active sensing control]]

Sensor Selection: 
* [[Minimizing the cardinality of an events set for supervisors of discrete-event dynamical systems]]
* [[Sensor selection for detecting deviations from a planned itinerary]]
* [[Diagnosability of Discrete-Event Systems]]
* [[Minimal sensor activation and minimal communication in discrete-event systems]]
* [[NP-Completeness of Sensor Selection Problems Arising in Partially Observed Discrete-Event Systems]]
* [[A General Approach for Solving Dynamic Sensor Activation Problems for a Class of Properties]]

Triage of captured Data:
* [[Optimal Online Data Sampling or How to Hire the Best Secretaries]]

EQA - Embodied question answering:
-  [[Embodied Question Answering]]
- [[Embodied Question Answering in Photorealistic Environments with Point Cloud Perception]]

Questions for Shell:
- "Such methods may be too indiscriminate for those needs" - pg1 - wth does that mean


Extra stuff:
* Papers that involve partial information
	* [[Filtering and Planning in Information Spaces]]
	* [[Belief space planning assuming maximum likelihood observations]]
* Trees for efficient solving plans are similar [first order logic](https://www.geeksforgeeks.org/artificial-intelligence/first-order-logic-in-artificial-intelligence/) , but different for tree's predominant on [action](Behavior%20Trees%20in%20Robot%20Control%20Systems)


Follow up paper: [[Knowledge acquisition plans Generation, combination, and execution]]


