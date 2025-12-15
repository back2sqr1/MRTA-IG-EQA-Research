
Goal: I want to ask robots questions and have them go out and probe the information from the environment

What the paper does: Presents a method that a robot system (Multi-robot) can efficiently answer questions on the basis of reasoning about observations that they made


Problem Characteristics:
- Robot-agnostic
- Plans are represented by a decision graph
- Differences arise with the plan (the knowledge to acquire) and the executor (selecting the appropriate actions), the interface is the cost model 
- Tasks come in the form of multiple queries - can be synthesized into a single composite task
- The world is represented through possible semantics - check into [[Reactivity and statefulness, Action-based sensors, plans, and necessary state |model checking]]
- Tree structure resembles [[Behavior Trees in Robot Control Systems |behavior trees]] and [[Reactivity and statefulness, Action-based sensors, plans, and necessary state |procrustean graphs]]

Core ideas:
- Separate "what is known" and "how it is learned"
- Leverage informational overlap between multiple simultaneous queries
- Tries to illustrate best plan quality
- Historical context: [[Strips, A new approach to the application of theorem proving to problem solving|STRIPS]] system - resolution theorem prover to answer questions of particular models
- "What if instead of answering questions about models of the world, we form plans whose purpose is to answer questions about the world itself?" -dumb dumb
- Point of the paper: Generalize the structure of knowledge-gathering plans to multiple robots
- Information path planning involves selecting actions based on the potential to enable the robot to gather information 
	- **Differs in that "we lay stress on knowledge - as distinguished from data per se"**
	- Our algorithms differ by directing robots toward the collection of data based on prior knowledge  (from the world and observations)
- Knowledge acquisition distinctly lasers into observation, leaving any action based questions to the executors
- Follows a similar work of embodied question answering - which tends to focus on overcoming the difficulties of robot perception, emphasizing the value that can be extract from prior work knowledge

Notes on writing:
- Related work begins in a historical context
	- Work is related to active sensing, sensor selection, and informative path planning


Problems feature uncertainty:
- [[Filtering and Planning in Information Spaces]]
- [[Locally Observable Markov Decision Processes]]
- [[Belief space planning assuming maximum likelihood observations]]

Active sensing:
* [[Planning to chronicle: Optimal policies for narrative observation of unpredictable events]]
* [[Particle filter based information-theoretic active sensing]]
* [[Online optimal active sensing control]]

Sensor Selection:
* [[Minimal sensor activation and minimal communication in discrete-event systems]]
* [[NP-Completeness of Sensor Selection Problems Arising in Partially Observed Discrete-Event Systems]]
* [[A General Approach for Solving Dynamic Sensor Activation Problems for a Class of Properties]]

Information path planning:
- [[Branch and Bound for Informative Path Planning]]
- [[An Efficient Sampling-based Method for Online Informative Path Planning in Unknown Environments]]
- [[Online Informative Path Planning for Active Information Gathering of a 3D Surface]]


Procrustean Graphs:
- [[Toward a language-theoretic foundation for planning and filtering]]

Embodied Question answering:
* [[Embodied Question Answering]]
* [[MQA- Answering the Question via Robotic Manipulation]]
* [[Depth and Video Segmentation Based Visual Attention for Embodied Question Answering]]
* [[Embodied Question Answering in Photorealistic Environments with Point Cloud Perception]]
* [[Multi-Target Embodied Question Answering]]