## 2D Trypanosome Motility Analysis Pipeline

This project implements a full analysis pipeline for brightfield videos of T. brucei using the MATLAB Image Processing Toolbox. The workflow includes background correction, temporal filtering, and cell detection via threshold-based segmentation. Cell centroids (center of mass) is tracked across frames to produce trajectories from which the average velocity is extracted. Additionally, the flagellum tip and posterior end can also be tracked, which gives the ability to extract essential swimming parameters.
