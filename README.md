# fp-azimmer8-hoiyi

# Projecting Carbon Emissions
Alec Zimmer (azimmer8@uw.edu)
Hoiyi Ng (hoiyi@uw.edu)


### Development Process
Getting up to speed in D3 took a large amount of time, but we were helped out by A3. Hoiyi spent a large amount of time trying to coordinate the slider and play button for the maps. Alec ended up spending a good amount of time coordinating different interactive parts of the code - making sure that things would reset properly when the page is refreshed, that mousing out from a hover will return a line to its previous color rather than a set one (in case a line is excluded by a brush), etc. Alec also spent a decent amount of time trying to restructure data into the format that supported the task at hand.

For making the line maps, the plan of making line charts and allowing selection of different variables was in place from the start. After making those, the biggest issue with them was dealing with the excess of data as lines crowded out each other. The rest of the development process for the line charts focused on increasing readability: adding multiple region options, hovering to display country names, and brushing to subset the data.

Our visualization is a combined effort of Alec and Hoiyi with Alec focusing on creating line charts and Hoiyi extending the maps from our A3 submission. The work distribution can be briefly broken down as follows:

Maps: Primarily Hoiyi
* World maps - Hoiyi
* Getting initial map displayed - Hoiyi and Alec
* Loading in the data - Hoiyi and Alec
* Creating hover icons - Hoiyi
* Legend - Hoiyi
* Modifying hover icon text - Alec
* Slider - Hoiyi
* Map animation - Hoiyi
* Zooming - Hoiyi
* Speeding up data access to update immediately - Alec
* Hover style - Hoiyi
* Dropdown menu - Hoiyi

Line charts: Alec
* Line charts and interactivity - Alec

Other:
* Organization/setting up github/formatting submission - Alec
* Project proposal - Alec
* Progress presentation - mostly Alec
* Poster - mostly Hoiyi
* Final project paper - Alec and Hoiyi


### Abstract (from paper):

The goal of our visualization is to display how carbon emissions of different countries change over time. Our primary users are scientists and researchers who want to use the data to quickly gain a sense of overall carbon trends and patterns over the past 50 years worldwide, and how they relate to population size and economic output. By allowing users to interact with animated world maps and line charts, our visualization encourages researchers to develop scientific questions and specific analyses. In this paper, we will discuss related work that inspired our choice of visualization and details of our work. 

[Poster](poster-azimmer8-hoiyi.pdf) [Paper](paper-azimmer8-hoiyi.pdf)

## Running Instructions
Download the files to a folder and run index.html which will bring up the map (though not through Chrome since it won't load in the data). The drop-down menu at the right can be used to switch between the two maps and the line chart. The line chart can be opened directly by running index_lines.html.
