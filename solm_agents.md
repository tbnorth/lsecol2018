<!-- .slide: data-background="img/png/title.png" data-background-size="contain" -->

<!--
# Applications of agent-based modeling to nutrient movement Lake Michigan

## Terry N Brown, James Pauer, Tom P Hollenhorst

http://tbnorth.github.io/solm_agents
-->



## Cell (or grid) based models

- divide space up into squares, maybe layered (3D)
- represent levels / categories of phenomena across
  space uniformally (fully mixed) within cells
- timesteps move content between cells (mass balance,
  concentration, etc.)



## Agents

- exist at a specific point in space
- can have multiple static and varying attributes
- can interact with surrounding agents (and cells)
  based on distance etc.
- added and removed from the model over the model's
  runtime



## Agents for continuous phenomena

- historically agent based modelling focused on distinct
  entities (fish in streams, etc.)
- modern computational power allows large numbers of
  agents to approximate continuous phenomena



## Cell based models

- computationally efficient (*if* vectorized)
- cover modelled space completely
- integrate with GIS etc.



## Agents

- more precise for some spatial questions
- can more easily represent complex life histories
- can represent more complex spatial arrangements




Abstract

As part of an ongoing project aiming to provide useful information for nearshore management (harmful algal blooms, nutrient loading), we explore the value of agent-based models in Lake Michigan. Agent-based models follow many individual “agents” moving through a simulated system. Individually simulated fish in a modeled stream are a common example of agent-based modeling, but modern computing power allows such large numbers of agents to be processed they can approximate continuous phenomena like nutrient distribution in lakes. They complement fixed-cell (or grid) models, and hybrid models combining both representations are possible. By tracking identity and state (time and place of origin, internal state, interaction with environment, and interaction other agents) over time, agent-based models make it easy to ask and answer complex questions. What's the residence time of tributary water in the nearshore? How do lake wide flows differ seasonally and inter-annually? How is water exchanged between Green Bay and Lake Michigan? We include examples of state of the art visualization techniques - combining model results with advanced visualization techniques helps user interpret and ultimately apply data to their problems.


