---
group: Informative Path Planning
tags:
  - "#InformativePathPlanning"
---
Context:  Cited when describing informative path planning

#InformativePathPlanning 
 
nonmyopic - not nearsighted 

Problem description:
- You select the best subset of observation locations subject to constrained resources
	- Trade off occurs from gathering information about the environment, and exploiting that information 
- NP-hard
- You want to find the subset of locations that are most informative
-  

Algorithm proposed:
- Attempts to address exploration -exploitation tradeoff
- Attempts to plan for possible observations made in the future
- The benefit of exploration is the adaptivity gap - between adaptive and a nonadaptive algorithm in terms of the uncertainty of the environment (how adaptive are you)


Notes:
- Path planning application - search and rescue
- These involve uncertain environments with complex dynamics
- Nonadpative (offline algorithms) - plan and commit before any observation
