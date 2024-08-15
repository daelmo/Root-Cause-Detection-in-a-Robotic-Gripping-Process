# Counterfactual Root Cause Analysis via Anomaly Detection and Causal Graphs

This work was published in this [publication](https://doi.org/10.1109/INDIN51400.2023.10218245).

This repository contains datasets with and without anomalies, plots, videos and the causal graph of a robotic gripping process.


![]([my_video.mov](https://raw.githubusercontent.com/daelmo/Root-Cause-Detection-in-a-Robotic-Gripping-Process/main/videos/Normal.mp4))

As the work is part of a research project on collaborative kinematics, the work piece is not gripped by one but two cooperating robots. 
This has no influence on the root cause detection algorithm. Only the datasets include twice as much robot axis than for a single industrial robot.


### Repository Structure
The notebook 'Calculate JRCS.ipynb' contains the Python Code.

`videos` includes the videos for the normal and one anormal scenario.

`plots` includes the plots for each feature of the normal dataset.

`causal graph` includes the adjacency matrix of the true causal graph, and simple lists about the measured features and the inspected rootcauses.

`datasets` includes the normal dataset and two datasets including faults produced by root causes.

### Citation

Cite the work as:

```

@inproceedings{rehak2023counterfactual,
  title={Counterfactual Root Cause Analysis via Anomaly Detection and Causal Graphs},
  author={Rehak, Josephine and Sommer, Anouk and Becker, Maximilian and Pfrommer, Julius and Beyerer, J{\"u}rgen},
  booktitle={2023 IEEE 21st International Conference on Industrial Informatics (INDIN)},
  pages={1--7},
  year={2023},
  organization={IEEE}
}
```
