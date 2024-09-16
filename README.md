# Code repository for *Deep learning-based predictions of gene perturbation effects do not yet outperform simple linear methods*

This repository contains the code to reproduce our analysis.

- The **notebooks** folder contains the R scripts used for the analysis and to make the figures
  - [Double Perturbation Analysis](htmlpreview.github.io/?)
  - [Single Perturbation Analysis](htmlpreview.github.io/?)
- The **benchmark** folder contains the scripts to reproduce the benchmark results
  - The **benchmark/src** contains individual scripts to run each method
  - The **benchmark/conda_environments** and **benchmark/renv** contain the details about the software versiona
  - The **benchmark/submission** contains the script to launch the scripts using the my [custom](https://github.com/const-ae/MyWorkflowManager) workflow maanger
