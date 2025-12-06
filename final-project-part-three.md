| [home page](https://mjvn9.github.io/Telling-Stories-With-Data-Portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The Final Data Story
My final project is published on Shorthand and can be viewed here: [*Flood Risk in Manhattan: A Quick-Start Guide for Emergency Planners*](https://carnegiemellon.shorthandstories.com/telling-stories-with-data-final-project-part-2/index.html).

---

# The Audience
One of the biggest changes between Part II and Part III was clarifying and then narrowing down the audience for this project. Earlier in the process, I designed the story with **two distinct groups** in mind:
1. **New York City Emergency Management and planning staff** as they need clear information about where flood vulnerability intersects with essential services.  
2. **Manhattan residents** who could benefit from an accessible explanation of flood risk in different neighborhoods and the facilities they rely on that may be exposed.

As I progressed, I realized that trying to  serve both audiences equally at the same time made the story less focused. Their needs and motivations are quite different from residents. Feedback from class and the teaching team reinforced the idea that there may already be sufficient public-facing tools to help New Yorkers understand their flood risk, but not necessarily as many resources designed for for emergency planners who would use it in operational decision-making.

Therefore for Part III, I decided to pivot fully toward NYC emergency planning professionals and reframe the project as a **“quick start guide”**. It was meant to be something concise and actionable. This audience is invested in understanding where critical facilities (hospitals, schools, child-service locations, and public safety sites) overlap with high-risk flood zones, since these sites affect emergency access and response coordination.

Focusing on a single stakeholder group made the story more purposeful aligned with my own resilience-planning perspective on the issue.

---


# Other Changes Made Since Part II
After the audience shift, there were other major changes that shaped the final story.

First, I revised how I **categorized neighborhood-level flood risk**. In Part II, I experimented with grouping Manhattan census tracts into generic “low,” “medium,” and “high” risk categories. After gathering user feedback, I changed gears to a more intuitive method of assigning each tract a **Flood Vulnerability Index value from 1 to 5**, where 5 represents the highest exposure. Emergency planners are used to working with numeric scales, so I felt that this detail would communicate risk levels more clearly.

Second, I significantly changed **how critical infrastructure is visualized**. My original plan had symbolized point maps showing each facility type individually. While this worked in sketches, the actual Tableau output was cluttered and visually overwhelming. My solution was to replace the symbol map with a **density map**, so  planners can quickly identify clusters of essential services without being overwhelmed by overlapping icons. This will reduce cognitive load and support faster interpretation which is crucial for this audience.

These changes made the narrative more coherent and better suited for emergency planning workflows.

---


# Final Design Decisions
### • Adding guiding annotations
I added annotations within the Tableau visualizations to highlight patterns/insights directly on the charts. This ensures important findings are visible without long explanations.

### • Structuring the story as a step-by-step guide that emphasizes action
The final narrative is designed as a workflow:

1. Identify neighborhoods with the highest risk  
2. Map critical facilities within those areas  
3. Pinpoint hotspots where risk and infrastructure overlap  
4. Determine which facility types are most exposed  
5. Turn findings into actionable planning steps  

The story ends with a section on **“What This Means for Manhattan”** to summarize how planners can turn this information into decisions. 

---

# Final Thoughts
This project reinforced how important it is to design with a specific audience and purpose in mind. I learned that simplifying visual information is usually more effective than trying to show everything at once, especially for stakeholders who need to interpret data quickly. If I had more time, I would explore adding an interactive element where planners could filter by facility type or simulate future flood scenarios. 

Looking back, I’m very pleased with how this story evolved. Finding the right audience, adding details to the visuals, and steering the story toward actionable steps helped this go from a general flood-risk overview into a useful tool.

---

## AI Acknowledgements
I used AI to help me brainstorm wording and refine the language in some sections of this assignment. All project ideas, sketches, and visual concepts are my own.

---
## References & Citations

Bravo, L. (2017). *Panoramic photography of Brooklyn Bridge* [Photograph]. Unsplash.  
https://unsplash.com/photos/panoramic-photography-of-brooklyn-bridge-_QdFx92MO2U  

Domas, E. (2019). *Untitled* [Photograph]. Unsplash.  
https://unsplash.com/id/foto/cakrawala-kota-dekat-air-laut-AtQeGdQzXQ8  

Getty Images. (2024). *Aerial View of Buildings in Manhattan at Night / NYC* [Photograph]. Unsplash.  
https://unsplash.com/photos/aerial-view-of-buildings-in-manhattan-at-night-nyc-xjb6IQqHN84  

New York City Department of City Planning. (2016). *Flood Risk in NYC* [Report]. NYC.gov.  
https://www.nyc.gov/assets/planning/download/pdf/plans-studies/climate-resiliency/flood-risk-nyc-info-brief.pdf  

NYC Open Data. (2024). *Facilities Database – Shapefile* [Dataset].  
https://data.cityofnewyork.us/City-Government/Facilities-Database-Shapefile/2fpa-bnsx  

NYC Open Data. (2024). *New York City’s Flood Vulnerability Index* [Dataset].  
https://data.cityofnewyork.us/Environment/New-York-City-s-Flood-Vulnerability-Index/mrjc-v9pm/about_data  

Pahade, A. (2025). *Untitled* [Photograph]. Unsplash.  
https://unsplash.com/photos/a-city-street-filled-with-lots-of-traffic-next-to-tall-buildings-chuISVgHji4  

Sikkema, K. (2017). *Traffic light sign underwater* [Photograph]. Unsplash.  
https://unsplash.com/photos/traffic-light-sign-underwater-_whs7FPfkwQ  

Surico, J., & Underwood, N. (2025, October 15). *What New York Can Do to Survive Flooding*. The New York Times.  
https://www.nytimes.com/interactive/2025/10/15/nyregion/new-york-climate-flooding-solutions.html  

Turgeon, C. (2021). *Untitled* [Photograph]. Unsplash.  
https://unsplash.com/photos/people-walking-on-park-near-high-rise-buildings-during-daytime-AUmq5VsgL3g  

Untitled [Photograph]. Freepik.  
https://www.freepik.com/free-photo/air-polluted-city-monotone-landscape-photography_15665644.htm#fromView=keyword&page=1&position=6&uuid=1866e19e-f1f9-46e1-bd62-2d48656242a4&query=32+hazy+cityscape+shot  

Wolbert, A. (2020). *Untitled* [Photograph]. Unsplash.  
https://unsplash.com/it/foto/una-vista-dello-skyline-di-una-citta-dallacqua-zreHGxdZWrQ  

---
