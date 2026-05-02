# SDS-CSC-235-hw03: Interacting with Data

## Outline

This repository contains the starter code and instructions you will need for this assignment; fork and then clone it to your machine.  

In this assignment you will create two interactive visualizations using the `d3.js` library. The data you will visualize is included in the `index.js` starter file. You will need to modify index.html, style.css, and index.js from this repository to make your webpage. 

In class we looked at the basics of D3 selections, data joins, scale functions, and axes. To complete this assignment, you will need to supplement your learning. A good starting point is [D3 in Depth](https://www.d3indepth.com/introduction/), but there are plenty of additional free resources available. Remember, we are using version 7 of D3 (older resources may use previous versions, with methods that are no longer supported).  

## Phase 1: Bar chart 

Familiarize yourself with the data provided in `index.js`. Each observation is a language. Variables include language, family, branch, first_language_millions, second_language_millions, total_millions (millions refers to number of speakers). **You should not directly edit `myData`**. 

Use D3 to create a bar chart that shows the frequency of each language family in the data. You bar chart must:

1. Be built using D3
2. Be titled
3. Include correctly titled and labeled x and y axes
4. Highlight a bar if clicked by the user (and un-highlight a highlighted bar if clicked) 

To find frequencies, you might consider looking into `d3.rollup`. Some starting points for this include the [D3 development documentation](https://devdocs.io/d3~7) and [this tutorial on Observable](https://observablehq.com/@d3/d3-group).

To add interaction, you might consider looking at the Event handling section of the selections chapter of D3 in Depth](https://www.d3indepth.com/introduction/).   


## Phase 2: Pie chart

Use D3 to create a pie chart that shows the proportion of each language family in the data. Your pie chart must: 

1. Be built using D3
2. Be titled
3. Be properly labeled
4. Add text to the webpage with the language family and corresponding proportion of any pie slice that is clicked  

You might consider looking more into the shapes chapter of [D3 in Depth](https://www.d3indepth.com/introduction/) to help with this part of the assignment. 


 ## Submission

 If this is your first submission of this assignment: fill out `rubric.md`, push your completed files to github, and submit your repo on Gradescope.

 If this is a revised submission of this assignment: fill out `reflection.md`, `rubric.md`, push your completed files to github, and submit your repo on Gradescope. 







