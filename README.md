# AI-Based Threat Detection in Cybersecurity  

## Introduction  

This project, titled "AI-Based Threat Detection in Cybersecurity," is designed to develop a system that leverages machine learning for identifying cyber threats. The process involves multiple stages, each contributing to enhancing the system's ability to detect and mitigate risks effectively. Here's a breakdown of the key steps:  

### Step 1: Preparing the Data (PreProcessing.ipynb)  

- The initial stage focuses on preprocessing the dataset to make it suitable for machine learning tasks.  
- The CIC-IDS2017 dataset is utilized and should be placed in the "CSVs" folder within the project directory.  
- You can download the dataset from the official source [here](https://www.unb.ca/cic/datasets/ids-2017.html).  

### Step 2: Filtering Attack Data (AttackDivision.ipynb)  

- This step processes the "all_data.csv" file to create individual files for each type of attack.  
- These filtered files are stored in the "./attacks/" folder for further analysis.  
- The dataset comprises 12 distinct attack types, which are separated for detailed study.  

### Step 3: Selecting Features and Applying Machine Learning (FeatureSelection.ipynb)  

- During this phase, the program identifies the top four features from each attack file based on their importance.  
- These selected features are used to train machine learning models, improving detection accuracy.  

### Step 4: Evaluating Machine Learning Models (MachineLearningSep.ipynb)  

- This step involves testing seven different machine learning algorithms on each attack file.  
- The outcomes are displayed on the screen and saved in the file "./attacks/results_1.csv".  
- Visual results, including box-and-whisker plots, are generated and stored in the "./attacks/result_graph_1/" directory.  

## Dataset Reference  

The CIC-IDS2017 dataset can be accessed [here](https://www.unb.ca/cic/datasets/ids-2017.html).  
