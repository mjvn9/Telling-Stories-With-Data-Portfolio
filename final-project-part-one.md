| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Outline
For my final project, I’m exploring where critical infrastructure in New York City’s Manhattan borough overlaps with high coastal flood vulnerability. Manhattan has a dense network of essential services such as hospitals, public schools, fire stations, and public housing developments that people rely on every day. However, not all neighborhoods face the same level of exposure to flooding and the city’s own projections show that flood risk will continue increasing throughout this century.
 
My goal for this project is to create a visualization highlighting geographic hotspots where essential services fall inside the highest flood-risk areas. The focus will be a map of Manhattan neighborhoods shaded by flood vulnerability and symbols representing different infrastructure types. Putting these two pieces together should help the audience quickly see which places have both high risk and clusters of services that matter during emergencies.

> This project is aimed primarily at NYC emergency managers and planners, but also for residents who want a better understanding of how flooding could affect the essential systems in their communities. Ultimately, the visualization should help people see not just where flooding is likely but what it threatens, and where the city might focus future planning.

Using the Good Charts story arc structure, I want the viewer to feel like they’re being guided through the data step by step.

---

## **One-Sentence Summary**
**In Manhattan, a handful of neighborhoods combine high coastal flood risk with dense clusters of critical infrastructure, making them priority hotspots for resilience planning.**

---

## **User Stories**

-	As an NYC emergency manager, I want to see which neighborhoods have both high flood vulnerability and many critical facilities so I know where to prioritize resilience investments.

-	As a resident, I want to know whether my neighborhood’s essential services are at risk so I can better understand local vulnerabilities.

---

## **Setup:**
I start by establishing the context of everyday Manhattan as a dense borough with essential infrastructure that residents depend on. This section includes a neutral, baseline map. There is no flood shading yet as we just want to introduce the geography and the idea that these facilities are everywhere.

The key ideas in this stage are: Manhattan’s population and infrastructure density, and a simple outline map to set the geography.

---

## **Conflict:**

I introduce the **Flood Vulnerability Index** by neighborhood as a choropleth map. The viewer sees immediately that some neighborhoods are much more at risk than others. Then I overlay the infrastructure points such as hospitals, schools, public housing, etc. This is the turning point of the story, because the audience can now see where the darkest flood-risk areas overlap with clusters of essential services.

Ultimately, the viewer should start to wonder which neighborhoods they/we should really be worried about.

The key ideas in this stage are: choropleth map of the Flood Vulnerability Index, infrastructure points layered on top, clear legends for each facility type, annotations that highlight 2–3 hotspot neighborhoods.

---

## **Resolution:**
This last section will tie everything into a clearer story about priorities. The charts help confirm which neighborhoods show the most overlap.

**Visuals in this section:**
- A **horizontal bar chart** ranking neighborhoods by the number of at-risk facilities  
- A **pie chart** showing which facility types appear most often in high-risk areas
- A short conclusion about which neighborhoods emerge as highest priority for resilience planning

The goal is for the audience walk away with an more data-informed understanding of where vulnerabilities concentrate and what types of services are most affected. 

---

## Initial Sketches

> Sketch 1: Sets context about Manhattan before any data layers

<img src="https://github.com/user-attachments/assets/0f7704ce-5770-4413-aa29-efd543c48891" alt="Sketch 1" width="700" />


> Sketch 2: Shifting into conflict by showing uneven risk across neighborhoods
> Created through Canva

<img src="https://github.com/user-attachments/assets/95051306-698f-4624-b642-250de555eb45" alt="Sketch 2 map" width="700" />



> Sketch 3: Conflict is where risk meets infrastructure within certain hotspots
> Created through Canva

<img src="https://github.com/user-attachments/assets/d1905285-3054-4d40-b9d7-158e8770d7dc" alt="Sketch 3 map" width="700" />


> Sketch 4: Supports critical choice in where to focus planning
> > Created through Canva

<img src="https://github.com/user-attachments/assets/31ebfd7d-178f-4972-be2f-5e370117c33f" alt="Sketch 4 bar chart" width="700" />

> Sketch 5: Helps audience understand what kinds of vulnerabilities dominate
> > Created through Canva

<img src="https://github.com/user-attachments/assets/12d4020e-63f8-408e-86b8-9a0e05db343f" alt="Sketch 5 pie chart" width="700" />

---

# The Data
For this project, I’m using publicly available datasets from New York City that provide both neighborhood-level flood vulnerability information and the locations of key facilities across Manhattan. The Facilities Database includes the locations of hospitals, public schools, fire stations, and public housing developments.

I plan to filter this dataset to focus only on the types of services that matter most for basic daily needs and emergency response. The Flood Vulnerability Index is a way to compare risk across neighborhoods, which makes it useful for a choropleth map.

In Tableau, I’ll join or link these datasets by neighborhood boundaries, create the flood-risk map, and then overlay the filtered facility points on top. I’ll also use the same data to calculate summary counts for the bar and pie charts in the final story.
Below are the public datasets I plan to use:

| Name | URL | Description |
|------|-----|-------------|
| NYC Facilities Database | https://data.cityofnewyork.us/City-Government/Facilities-Database-Shapefile/2fpa-bnsx | Contains the locations of hospitals, schools, public housing, fire stations, and other city facilities. I will filter this dataset to only include the categories relevant to this project. |
| NYC Flood Vulnerability Index | https://data.cityofnewyork.us/Environment/New-York-City-s-Flood-Vulnerability-Index/mrjc-v9pm |Neighborhood-level index that measures social, infrastructural, and environmental vulnerability to flooding. Used for the choropleth shading.  
| NYC Coastal Flood Hazard Map Viewer |https://www.arcgis.com/apps/webappviewer/index.html?id=1c37d271fba14163bbb520517153d6d5 | Online reference map showing coastal flood hazard zones. I will use this mainly for context and verification. |

---

# Method and Medium

I will use Tableau to build the main visuals for this project, including the choropleth map, the infrastructure hotspot map, and the supporting bar and pie charts. Once those are finished, I will bring everything into a Shorthand story so I can present the project as a narrative that follows a story arc. 

The final product will be an interactive piece that mixes maps, charts, and short text explanations. My goal is to create something easy to follow for NYC emergency planners but is also accessible for residents who want to understand what’s going on in their neighborhood. 

---

## References

Berinato, S. (2023). Good charts, updated and expanded: The HBR guide to making smarter, more persuasive data visualizations. Harvard Business Review Press.

New York City Department of City Planning. (2016). Flood risk in NYC (Information brief). https://www.nyc.gov/assets/planning/download/pdf/plans-studies/climate-resiliency/flood-risk-nyc-info-brief.pdf

Surico, J., & Underwood, N. (2025, October 15). What New York can do to survive flooding. The New York Times. https://www.nytimes.com/interactive/2025/10/15/nyregion/new-york-climate-flooding-solutions.html

---

## AI Acknowledgements
I used AI to help me brainstorm wording and refine the language in some sections of this assignment. All project ideas, sketches, and visual concepts are my own.
