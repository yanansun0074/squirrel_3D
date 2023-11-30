# Squirrel_3D

## Intro
This is a repo for 3D data visualization of 2018 Central Park Squirrel Census. 

Find the data here: https://data.cityofnewyork.us/Environment/2018-Central-Park-Squirrel-Census-Squirrel-Data/vfnx-vebw

All the visualization is made out of the dataset above in Blender. To run the script and generate the visualization, make sure to download Blender (https://www.blender.org/) first.

## Work samples
- Hectar scatter plot: https://skfb.ly/oO6sN
- Activity bar chart: https://skfb.ly/oO6tn

## How to view in Blender
1. Have Blender installed on your computer
2. Pull the repo
3. open ".blend" files
4. Toggle the collections to hide and unhide objects
5. Click on the "Scripts" Tab to view all the scripts (see how to run scripts below)

e.g. "Bar Chart Collection" and "Scatter Plot Collection" to see work sample 1 and 2.

<img width="345" alt="Screenshot 2023-11-28 at 11 29 04" src="https://github.com/yanansun0074/squirrel_3D/assets/116763187/2fadb118-a14a-4478-a79d-623b7e7fdbf7">

## How to run scripts in Blender
1. In ".blend" file, open "Scripting" workspace. 
2. Use the "browser text to be linked" button to switch between scripts.
- if you could not find any script file open in Blender, Select "Text" >>> "Open", open the files file from "Scripts" folder with corresponding names.
3. Run it with "run script" button (little triangle). The button will run the current script only.
<img width="1440" alt="Screenshot 2023-11-28 at 11 49 37" src="https://github.com/yanansun0074/squirrel_3D/assets/116763187/7cb40608-2413-488b-bf43-58afa8c29ffd">

4. Console output

- For Windows user: Editor Type >>> Python Console

- For MacOS user: few extra steps 🙄 to follow from this tutorial - https://www.youtube.com/watch?v=RbQCzk-ef3g

- I'm not sure about other operating systems

Before run "Scatter_Black", "Scatter_Cinnamon", and "Scatter_Gray", **be sure to create a sphere object with corresponding material in the viewport and select that object.** This is to take advantage of linked objects that save spaces, so that you won't find a 400 MB file when exporting😢. 












##### Author: Yanan Sun
##### All rights reserved
