# Root-Cause-Detection-in-a-Robotic-Gripping-Process


This repository contains datasets with and without anomalies, plots, videos and the causal graph of a robotic gripping process.


<video src='https://raw.githubusercontent.com/daelmo/Root-Cause-Detection-in-a-Robotic-Gripping-Process/main/videos/Normal.mp4' width=180/>

As the work is part of a research project on collaborative kinematics, the work piece is not gripped by one but two cooperating robots. 
This has no influence on the root cause detection algorithm. Only the datasets include twice as much robot axis than for a single industrial robot.


### Repository Structure

`videos` includes the videos for the normal and one anormal scenario.

`plots` includes the plots for each feature of the normal dataset.

`causal graph` includes the adjacency matrix of the true causal graph, and simple lists about the measured features and the inspected rootcauses.

`datasets` includes the normal and two data sets including faults produced by root causes.
