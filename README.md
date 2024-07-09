Box Size Optimization Project

Project Summary

This project was initiated to address the need for reducing packaging costs in my current workplace, particularly for aftermarket products. It provided a valuable opportunity to hone my skills in data analysis, clustering techniques, and project management. I utilized Python libraries such as pandas and numpy for data manipulation, matplotlib and seaborn for data visualization, and scikit-learn for implementing machine learning algorithms. Through this project, I gained experience in using advanced analytical methods to make data-driven decisions and collaborated effectively with a team to achieve consensus.

Introduction
With the demand for reducing packaging costs, particularly for aftermarket products, the idea of box size optimization emerged. After several failed attempts by multiple departments, this topic was suggested as a Green Belt project to explore potential benefits.

Initial Analysis
The first analysis was conducted using Excel to determine which boxes had potential for standardization, considering factors like raw material, engraving, and color. This analysis identified 253 boxes with potential for standardization, prompting a clustering analysis to find average box sizes.

Clustering Analysis
A K-means clustering analysis was chosen for its flexibility in adjusting the "K" variable to find the optimal strategy. An Elbow curve was created as a starting point, which suggested K=4 as a good initial value. However, based on the team's expertise, it was decided to significantly increase the value to better identify averages.

After extensive analysis, we settled on K=50. This value was used to identify the most common box sizes and calculate a theoretical mean for each cluster.

Team Consensus
In collaboration with the team, a tolerance margin was established for the clusters. This margin defined the acceptable size variation for each cluster, allowing us to determine which part numbers could be considered for each cluster size.
