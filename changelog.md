# Changelog

In order to receive a regrade on this submission you **must** fully answer the following. Incomplete or missing answers will result in no regrade. 

## 1. Clearly list all changes you made from your last submission to this submission.

### `index.js`
- Color map: Replaced `d3.schemeTableau10` with a custom 12-color palette explicitly mapped via `.domain()` and `.range()`, ensuring every family has a unique, distinct color in both charts.
- Pie chart labels: Removed the angle threshold that was hiding labels on small slices. Replaced inline centroid labels with an external leader-line system: all 12 family names are now displayed outside the pie with polyline connectors. Added a collision-resolution algorithm that spreads overlapping labels apart vertically so no two labels overlap.
- Pie chart interactivity: Added highlight behavior to pie slices — clicking a slice dims all others to 30% opacity and keeps the selected slice fully visible. Clicking the same slice again resets all opacities. Info text clears back to default on deselect.
- Bar chart interactivity: Extended click behavior to display an info message showing the selected family's name, language count, and percentage of the full dataset (e.g. "Indo-European: 14 languages (37.8% of dataset)"). Info text resets on deselect.
### `index.html`
- Wrapped each chart and its info text in a `<div class="chart-wrapper">` for layout and styling purposes.
- Added `<p id="bar-info">Click a bar to see details.</p>` beneath the bar chart.
- Updated page `<title>` and `<h1>` from "Language Families" to "World Language Families by Speaker Count".
### `style.css`
- Switched font to Inter (via Google Fonts) for a cleaner, more modern look.
- Changed background from a flat color to a subtle linear gradient.
- Styled the `h1` as a white card with rounded corners and a drop shadow.
- Added `.chart-wrapper` layout so each chart and its info badge sit together as a unit.
- Styled `#bar-info` and `#pie-info` as matching white badge elements with padding, border-radius, and box-shadow.
- Softened axis line colors and added `cursor: pointer` and `transition: opacity` to interactive elements.

## 2. Reflect on your experience prioritizing, working on, and completing this assignment. Moving forward, what changes will you make in these areas to work towards better first submissions of assignments? 

I would be more cautious in terms of the asthetic of the web page. Sometimes displaying all the information is just the first step, making the web page more asthetically pleasing is part of the process as well. Other than that, I will also find ways to label all the values on the pie chart, even though some slices might be small and hard to label, but labelling them can make the visual overall more informative and clear. 

## 3. Reflect on your learning from this resubmission. What content were you shaky on in the pervious submission, and how did you augment your learning to do better in this submission? What learning strategies did this redo help you develop that you will use on future first submissions of assignments? 

I was shaky on how to label the pie chart even when the slices are small and hard to put the value on the slice. I research online and found out that there are other more effective ways to label small slices pie chart, and apply them to my visualization. In the future, when I encounter hard to label visualizations, instead of giving up I will conduct more research and try to find solutions that apply to my situation. 