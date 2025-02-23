# Relationship Clustering Analysis

## Project Overview

This project, undertaken as a solo endeavor during the BeCode Data Science and AI Bootcamp 2024/2025, comprises an analysis of the "How Couples Meet and Stay Together" (HCMST) dataset, focusing on understanding the demographics and relationship characteristics of various clusters within the data. The primary objective is to interpret the clustering results to identify distinct groups based on factors such as age, income, relationship duration, meeting location, and more.

## Data Source

The analysis utilizes data from the HCMST study, which investigates how American adults meet their romantic partners and the dynamics of their relationships. Due to the volume of the datasets and time constraints, only the older dataset (Waves 1-3) was used for this analysis.

HCMST 2009 (Waves 1-3): This dataset includes responses from 4,002 adults, with 3,009 having a spouse or main romantic partner. The study oversampled self-identified gay, lesbian, and bisexual adults. 

The datasets are publicly availabe:

* **HCMST 2009**: [https://data.stanford.edu/hcmst](https://data.stanford.edu/hcmst)
* **HCMST 2017**: [https://data.stanford.edu/hcmst2017](https://data.stanford.edu/hcmst2017)

## Repository Structure

* `data/`: Contains the dataset used for analysis.
* `hcmst_clustering.ipynb`: Jupyter notebooks detailing the data exploration, preprocessing, clustering analysis, and interpretation.
* `README.md`: Overview of the project and instructions.

## Analysis Summary

The clustering analysis identified five distinct groups:

* **Cluster 0**: Middle-aged individuals with low income and medium relationship duration, predominantly meeting partners offline.
* **Cluster 1**: Young adults with middle-to-high income in early-stage relationships, often meeting partners at school or college.
* **Cluster 2**: Seniors with middle income and long relationship durations, primarily meeting partners offline.
* **Cluster 3**: Middle-aged individuals with middle-to-high income and medium-long relationship durations, with a significant number meeting partners online.
* **Cluster 4**: Early middle-aged, affluent individuals in long-term relationships, frequently meeting partners at private parties or abroad.

Each cluster's detailed interpretation is available in the `hcmst_clustering.ipynb` notebook.

## Usage

To replicate the analysis:

1. **Clone and navigate to the repository:**
   
    ```bash
    git clone https://github.com/Miriam-Stoehr/hcmst-clustering.git
    cd hcmst-clustering
    ```

2. **Install the necessary requirements:**
   
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Analysis:** Run the `hcmst_clustering` notebook sequentially.

## Future Work

Potential extensions of this project include:

1. **Incorporating Additional Waves:** Adding data from waves 4 through 6 to analyze the evolution of relationship clusters over time.

2. **Comparative Analysis:** Utilizing the HCMST 2017 dataset to examine how clusters may have changed over time.

3. **Algorithm Comparison:** Experimenting with different clustering algorithms to evaluate performance and robustness.


## Acknowledgements

The HCMST datasets were developed by Michael J. Rosenfeld and colleagues at Stanford University. The 2009 dataset was funded by the U.S. National Science Foundation (award SES-0751977), with supplementary funding from Stanford's Institute for Research in the Social Sciences and the UPS endowment at Stanford University. The 2017 dataset received funding from Stanford's United Parcel Service Endowment and the U.S. National Science Foundation. For more details, visit the dataset pages:

* HCMST 2009: https://data.stanford.edu/hcmst
* HCMST 2017: https://data.stanford.edu/hcmst2017
