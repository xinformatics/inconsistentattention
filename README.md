# When Attention Fails: Pitfalls of Attention-based Model Interpretability for High-dimensional Clinical Time-Series Modeling [CHIL 2025]

## Getting Started

### Dependencies / Requirements
* torch==2.1.1
* matplotlib==3.7.2
* seaborn==0.11.2
* numpy==1.25.2
* tqdm==4.65.0
* scikit-learn==1.3.0


## Repository directories & files
+ [`01_Mortality_Task_Training.ipynb`](01_Mortality_Task_Training.ipynb) contains code for model training on the 24-hour ICU Mortality Task for 1000 variants.
+ [`02_Phenotyping_Task_Training.ipynb`](02_Phenotyping_Task_Training.ipynb) contains code for model training on the 24-hour Patient Phenotyping Task for 1000 variants.
+ [`03_Mortality_Task_analysis_and_visualization.ipynb`](03_Mortality_Task_analysis_and_visualization.ipynb) contains code for analysis of cumulative attention drop across model variants for the ICU Mortality Task.
+ [`04_Phenotyping_Task_analysis_and_visualization.ipynb`](04_Phenotyping_Task_analysis_and_visualization.ipynb) contains code for analysis of cumulative attention drop across model variants for the Patient Phenotyping Task.
+ [`05_Mortality_Task_Rank_Analysis.ipynb`](05_Mortality_Task_Rank_Analysis.ipynb) contains code for analysis of rank analysis across cumulative model variants for the ICU Mortality Task.4
+ [`05a_Mortality_Task_Rank_with_Stdev_analysis.ipynb`](05_Mortality_Task_Rank_with_Stdev_analysis.ipynb) contains code for analysis of mean rank and standard deviation analysis across cumulative model variants for the ICU Mortality Task.
+ [`06_Phenotyping_Task_Rank_Analysis.ipynb`](06_Phenotyping_Task_Rank_Analysis.ipynb) contains code for analysis of rank analysis across cumulative model variants for the Patient Phenotyping Task.
+ [`07_Model_Metrics_Analysis.ipynb`](07_Model_Metrics_Analysis.ipynb) contains a comparison of model performance across model variants.
+ [`08_ExtremalMask_analysis.ipynb`](08_ExtremalMask_analysis.ipynb) contains results for feature-time attribution maps for the top 3 model variants using the ExtremalMask(Enguehard 2023) algorithm.
## Data
We do not have the authorization to share the HiRID ICU Benchmark dataset. Please contact https://github.com/ratschlab/HIRID-ICU-Benchmark and https://physionet.org/content/hirid/1.1.1/

