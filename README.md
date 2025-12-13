# ESGAnalysis

Readme file for miniproject of data mining course -sbeer6

# Corporate ESG Performance Analysis

This project provides a comprehensive data-driven analysis of corporate Environmental, Social, and Governance (ESG) scores to benchmark industry performance, assess pillar interdependence, and identify market leaders and laggards.

## Project Purpose and Key Functionalities

The primary purpose of this project is to transform raw corporate ESG data into actionable strategic insights. It addresses critical questions for investors and stakeholders by focusing on three key functionalities: **Industry Benchmarking**, where the script calculates and visualizes the mean E, S, and G scores across the top ten industries to highlight sectoral strengths and weaknesses; **Pillar Correlation Analysis**, which quantifies the linear relationships between the Environment, Social, and Governance scores using the Pearson coefficient; and **Total Performance Deep Dive**, which analyzes the overall ESG grade distribution and identifies the top and bottom five companies by total score. The output includes detailed markdown tables and analytical visualizations.

## Setup and Dependencies

This analysis is implemented in Python and designed to be run in any standard Python environment, such as Jupyter Notebook, Google Colab, or a local IDE.

### Prerequisites

You must have the following libraries installed:


pip install pandas numpy matplotlib seaborn

Data Requirement
The project requires the following file:
	•	ESGdataset.csv: The core dataset containing corporate ESG scores and metadata (ticker, industry, grades, and scores).
Instructions for Reproduction
Follow these steps to set up the environment and reproduce the results of the analysis:
Step 1: Place Data File
Ensure the ESGdataset.csv file is placed in the same directory as the analysis script (analysis.py or the notebook where the code is executed).
Step 2: Run the Code
Execute the following python script. The script will perform all three experiments, print the analytical results to the console, and save three visualization files.
Step 3: Check Results
After running the script, your directory will contain:
	1	Console output matching the Results, Analysis, and Insights section of the report.
	2	Three image files used to support the analysis:
	◦	industry_benchmarking.png
	◦	correlation_matrix.png
	◦	grade_distribution.png
### References

1.  **ESG Data Source:** The proprietary dataset, identified as `ESGdataset.csv`, containing corporate environmental, social, and governance scores, was utilized for this analysis. (Source methodology is based on [Name the expected data vendor, e.g., MSCI, Refinitiv, or state 'A third-party ESG data provider']).
2.  **Statistical Method:** Pearson, K. (1895). Note on Regression and Inheritance in the Case of Two Parents. *Proceedings of the Royal Society of London*, 58, 240-242.
3.  **ESG Conceptual Framework:** Global Reporting Initiative (GRI). (2021). *GRI Standards*. Used to contextualize industry-specific materiality in ESG performance evaluation.
4.  **Software:** McKinney, W. (2010). Data Structures for Statistical Computing in Python. *Proceedings of the 9th Python in Science Conference*, 51–56. (For the use of the Pandas library).
