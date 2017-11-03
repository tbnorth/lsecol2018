# Applications of agent-based modeling to nutrient movement Lake Michigan
<!-- .slide: data-state="hide-head" -->
<!-- .slide: data-background="img/png/title.png" data-background-size="contain" -->

<!--

## Terry N Brown, James Pauer, Tom P Hollenhorst

http://tbnorth.github.io/solm_agents
-->



## Cell (or grid) based models

- divide space up into squares, maybe layered (3D)
- represent levels / categories of phenomena across
  space uniformly (fully mixed) within cells
- time steps move content between cells (mass balance,
  concentration, etc.)


<div style="position:relative;height:0;padding-bottom:75.0%"><iframe src="https://www.youtube.com/embed/AJpi2ShsUfg?rel=0&amp;controls=1&amp;showinfo=0?ecver=2" width="480" height="360" frameborder="0" style="position:absolute;width:100%;height:100%;left:0" allowfullscreen></iframe></div>



## Agents

- exist at a specific point in space
- can have multiple static and varying attributes
- can interact with surrounding agents (and cells)
  based on distance etc.
- added and removed from the model over the model's
  runtime



## Agents for continuous phenomena

- historically agent based modeling focused on distinct
  entities (fish in streams, etc.)
- modern computational power allows large numbers of
  agents to approximate continuous phenomena



## Cell (grid) based models

- computationally efficient (*if* vectorized)
- cover modeled space completely
- integrate with GIS etc.



## Agents

- more precise for some spatial questions
- can more easily represent complex life histories
- can represent more complex spatial arrangements



<!-- .slide: data-background="img/png/gridagent000.png" data-background-size="contain" -->


<!-- .slide: data-background="img/png/gridagent010.png" data-background-size="contain" -->


<!-- .slide: data-background="img/png/gridagent020.png" data-background-size="contain" -->


<!-- .slide: data-background="img/png/gridagent030.png" data-background-size="contain" -->



## Nearshore model

- Nearshore - where nearshore stuff happens
- Nearshore stuff: trib. loads, resuspension, long shore flow, etc.
- Fuzzy boundary, nearshore ~100% of the time at 5 m, but
  maybe only 5% of the time at 50m
- Trib. loads retained in nearshore for a long time, relative
  to seasonal dynamics



<div style="position:relative;height:0;padding-bottom:75.0%"><iframe src="https://www.youtube.com/embed/ihdx9SCcS5Q?rel=0&amp;controls=1&amp;showinfo=0?ecver=2" width="480" height="360" frameborder="0" style="position:absolute;width:100%;height:100%;left:0" allowfullscreen></iframe></div>



<div style="position:relative;height:0;padding-bottom:75.0%"><iframe src="https://www.youtube.com/embed/z2cA9vZoPkA?rel=0&amp;controls=1&amp;showinfo=0?ecver=2" width="480" height="360" frameborder="0" style="position:absolute;width:100%;height:100%;left:0" allowfullscreen></iframe></div>



<div style="position:relative;height:0;padding-bottom:75.0%"><iframe src="https://www.youtube.com/embed/LKLIabY-y6c?rel=0&amp;controls=1&amp;showinfo=0?ecver=2" width="480" height="360" frameborder="0" style="position:absolute;width:100%;height:100%;left:0" allowfullscreen></iframe></div>



<!-- .slide: data-background="img/png/nearshore_contrib0.png" data-background-size="contain" -->
<!-- .slide: data-background-color="white" -->


<!-- .slide: data-background="img/png/nearshore_contrib1.png" data-background-size="contain" -->
<!-- .slide: data-background-color="white" -->


<!-- .slide: data-background="img/png/nearshore_contrib2.png" data-background-size="contain" -->
<!-- .slide: data-background-color="white" -->


<div style="position:relative;height:0;padding-bottom:75.0%"><iframe src="https://www.youtube.com/embed/9xWGsL7qCIg?rel=0&amp;controls=1&amp;showinfo=0?ecver=2" width="480" height="360" frameborder="0" style="position:absolute;width:100%;height:100%;left:0" allowfullscreen></iframe></div>



## Direction

- *possible* future work: a tool that:
- shows relative contributions to nearshore from
  different tribs.
- shows impact of timing of loads (flow, fertilizer
  application dates, etc.)
- gives “as of yesterday” estimates of current
  conditions



## Challenges

- Visualization - complex systems, but avoid complex
  interfaces
- Loadings - realistic **daily** loading data for all major
  Great Lakes tribs. not readily available
- Integration with watershed / landscape models
- Validation - multi-year / date / location data on nearshore
  conditions scarce



## Contact

Brown.TerryN@epa.gov

Pauer.James@epa.gov

Hollenhorst.Tom@epa.gov

