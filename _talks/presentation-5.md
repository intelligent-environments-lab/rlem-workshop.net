---
name: "ComfortLearn: Enabling agent-based occupant-centric building controls"
speakers:
  - Matias Quintana
  - Zoltan Nagy
  - Federico Tartarini
  - Stefano Schiavon
  - Clayton Miller
categories:
  - presentation
permalink: "/:collection/:categories/Presentation 5"
---

##### Abstract
The intersection of buildings control and thermal comfort modeling may seem obvious, but there are still prevalent challenges in combining them. “Occupant centric” control strategies are mainly trained using building data but rarely leverage occupants’ feedback. While thermal comfort models are developed using occupants’ data but are seldom integrated into building controls. To bridge this gap, we developed an open-source simulation tool named ComfortLearn. ComfortLearn is an OpenAI Gym-based environment that leverages historical building management system data from real buildings and existing longitudinal thermal comfort datasets for occupant-centric control strategies and benchmarking. We used an evaluation metric named ‘exceedance’ to evaluate occupants’ thermal comfort and provide a more realistic picture than traditional evaluations like comfort bands. This setup allows the analysis of different building control strategies and their effect on real occupants, based on empirical data, without the need for computationally expensive co-simulations. A theoretical case study implementation shows that an as-is schedule-based controller complies with its comfort band more than 93% of the time, but the simulated occupants are comfortable for only 25% of the occupied time.