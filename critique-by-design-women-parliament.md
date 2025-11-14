# Visualizing Women’s Parliamentary Representation Across the EU


## Step one: the visualization

The original visualization "Seats held by women in national parliaments and governments" can be found below:

<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/f03a052f-bd00-4b51-8d80-d1716fcb05e4" />

I chose this visualization because I’m really interested in how voices show up in policy spaces. As someone studying public policy, I think a lot about who gets to participate in shaping laws and institutions, and who doesn’t. Women are still underrepresented across many fields, especially in political leadership, so I wanted to look at whether there has been progress and how that progress differs across countries.

The EU felt like a particularly interesting case study because it’s such a diverse political region. Countries vary widely in their political cultures, histories, and gender norms, so a single dataset about women’s parliamentary representation has potential to tell a rich story. This Eurostat graphic seemed like a good starting point, but also an example of how complexity makes patterns harder to see.

## Step two: the critique
I evaluated the visualization using Stephen Few’s Data Visualization Effectiveness Profile. Overall, the chart contains valuable information, but several design choices hold it back from being truly effective.

On the positive side, the underlying data is genuinely meaningful. It covers a long enough time span to show whether countries have made real progress in women’s parliamentary representation, and the formatting itself is clean and professional. It also clearly cites Eurostat, which makes the visualization feel trustworthy and anchored in an authoritative source.

But even with all those strengths, the chart is hard to interpret in practice. With more than 25 countries shown as overlapping lines, it becomes virtually impossible to track any single trend without getting lost. The colors are so similar that I kept having to reference the legend, which is placed far from the data and adds even more cognitive load. There’s also no real narrative or takeaway to help the viewer understand what matters. Everything is presented with equal visual weight, so the story quickly gets buried in the noise. 

Overall, the visualization comes close to being useful, but it ultimately asks the viewer to work far too hard. That made me want to redesign it in a way that highlights a clearer message. That recognizes that women deserve equitable political representation, and that the pace of progress (or the lack of it) really does vary dramatically across countries. By simplifying and reframing the view, I hoped to make those differences easier to see and understand.


## Step three: Sketch a solution
I began by sketched out a few ideas on paper, such as the one below.

<img width="1395" height="2048" alt="image" src="https://github.com/user-attachments/assets/2c60f17d-de71-4982-aed6-0608fdbcbae7" />


My first goal was to break the information into **two visuals** that complemented each other instead of one overly busy one:

1. **A simple line chart** that focuses on only a handful of countries (top performers, lowest performers, and the EU average).

2. **A bar chart** showing where those same countries stand as of the latest year of data, 2019.

Another goal was to preserve the time element, but also give viewers a snapshot that clearly shows the gap between leaders and laggards. I also experimented with grouping colors by meaning (greens for high representation, oranges for low) to give the visuals a more narrative feel.



## Step four: Test the solution

I shared my drawn wireframe with two classmates and asked the following questions.
 

| Question | Interview 1 (MSPPM student with an information technology background) | Interview 2 (MISM student with a data science background) |
|----------|-------------------------------|------------------------------|
| What do you think this is? | Said the second sketch looked like a revised or simplified version of the original | Immediately recognized the first as a “change over time” chart.|
| What is it telling you? | Thought the title aligned with the visuals and could follow the trends easily | Understood it as showing women in government across various countries |
| Anything confusing? | Noted that the color differences were unclear in my sketch | Didn’t understand what the colors were supposed to represent |
| Intended audience? | Said UN or development orgs | Said government or policymaking audiences |
| Anything to change? | Suggested making the title more specific | Recommended using color more deliberately to signal meaning |


The main takeaway was that the concept of splitting the visualization into two charts worked well. Both people understood what I was trying to show without much explanation. However, both mentioned color confusion, which made me rethink how intentional my palette needed to be. Their feedback reinforced the importance of consistency (greens for high performers, oranges for low performers) and clearer labeling. It also pushed me to tighten the title so the message felt more explicit and easier to grasp at a glance.

## Step five: build the solution

Below is my redesigned visualization, built in Datawrapper.

<img width="1680" height="1078" alt="pWZ0M-changes-in-women-s-parliamentary-representation-across-the-eu-2009-2019-" src="https://github.com/user-attachments/assets/1005551a-eae7-4d70-aef7-ae0c2e904531" />
<img width="1744" height="740" alt="DcLAw-eu-countries-leaders-and-laggards-in-women-s-parliamentary-representation-2019-" src="https://github.com/user-attachments/assets/8f37f4da-1212-4570-b615-0f2450e7d770" />

I didn’t originally plan to do two charts combined into one multi-element visual, but once I sketched out ideas, it became clear that one chart alone couldn’t do everything well. The line chart helps answer questions about progress. Who has improved? Who has stayed flat? Who has consistently led? But line charts can’t show magnitude or ranking as clearly as a simple horizontal bar chart. Pairing the two allowed me to show  the trajectory and the current reality which felt important for a topic like representation, where progress and current status both matter.

The original dataset had so many lines so I made the  choice to include only the top three performers (Sweden, Finland, Belgium) and the lowest three performers (Cyprus, Malta, Hungary) with the EU average for a baseline reference. 

These extremes are where the clearest differences show up and they reinforce the story I’m trying to tell. This visualization isn’t trying to be a full statistical analysis, but rather trying to help the viewer see how dramatically experiences differ across the EU.

One of the biggest pieces of feedback I got from my peers was about the colors in my sketch, as they didn’t know what the colors meant. That pushed me to be much more intentional with the palette. Using graduated shades of greens to indicate high representation/a positive outcome and oranges to indicate low representation/a concerning outcome matches viewers' natural associations with these colors. This ended up being one of the most important improvements, because it removes cognitive friction and helps people immediately understand which countries are doing better or worse.

After testing, I realized I needed titles that were straightforward but still conveyed the main idea without overwhelming the reader.

For the line chart, “Changes in Women’s Parliamentary Representation Across the EU, 2009–2019” tells you what’s being measured, who it applies to, and what time period is included. For the bar chart, I wanted something that hinted at inequality more explicitly. “EU Countries: Leaders and Laggards in Women’s Parliamentary Representation (2019)” communicates that the chart is not just raw values.

The hardest part was finding the sweet spot between simplification and oversimplification. Initially, I considered showing only the EU average and the two extreme countries, but that felt too narrow and didn’t capture the diversity of political contexts in the EU. On the other hand, the full dataset was way too chaotic. The top/bottom three approach ended up being the best compromise.

Compared to the original Eurostat visualization, my redesign directs the reader toward the main story instead of overwhelming them with every detail and highlights the equity gap more clearly. By using color meaningfully to communicate differences, we can separates progress from “current status,” which makes these elements easier to interpret. My aim was to remove unnecessary visual clutter in order for the design to feel more accessible for a policymaking or general-interest audience. Even though the EU has made progress overall, the experience of women in politics looks very different depending on where they live. Some countries hover near 50% representation, while others struggle to reach even 15%. Visualizing this contrast in a clear way felt like an important part of telling a more honest and policy-relevant story.

## References
- Eurostat. “Seats held by women in national parliaments and governments.”  
- MakeoverMonday dataset archive: https://makeovermonday.co.uk  
- Stephen Few, *Data Visualization Effectiveness Profile* 

## AI acknowledgements
I used ChatGPT to help refine some of the narrative language. All sketches and the visualization redesign are my own.
