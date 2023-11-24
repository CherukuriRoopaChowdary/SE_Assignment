This repository contains code and datasets for two research questions

Research Question 1: RC23M
Objective: Identify common quality issues in the code generated by ChatGPT, focusing on issues identified by linters.
Code File: Assignment_SE.ipynb
Dataset: 20231012_235320_discussion_sharings.json
For inquiries related to Research Question 1 (RC23M),
Email: rc23m@fsu.edu
### Dataset Information
The analysis utilizes the `20231012_235320_discussion_sharings.json` dataset, which contains conversation data between developers and ChatGPT.
**###Code Overview**
**Defined the Quality Metrics:** This includes defining rules for indentation, variable naming conventions, syntax rules, and other relevant metrics.
**Selection of Linter:** The selected linter will be instrumental in identifying issues, enforcing coding standards, and enhancing code consistency.
**Automated Analysis:** The chosen linter is systematically applied to each code file in the dataset using a script or program. This automated process efficiently identifies issues and deviations from the defined quality metrics. This step enables a thorough examination of the code generated by ChatGPT for common quality issues.


**Research Question 2 (KB23U)**
Objective: Investigate the possibility of forecasting whether a developer will incorporate ChatGPT-generated code into a production environment based on their interactions with ChatGPT during a conversation.
Code File: RESEARCH_QUE-2_KB23U.ipynb
Dataset: discussion_sharings.json
### Execution 
Open the Jupyter Notebook or any compatible environment.
Install the required packages.
Run the cells and execute the code
### Dataset Information
The analysis utilizes the `discussion_sharings.json` dataset, which contains conversation data between developers and ChatGPT.
### Code Overview
**Data Processing:** The code extracts prompts and answers from the JSON dataset and writes them to a CSV file (`prompts_answers.csv`).
**Sentiment Analysis:** Utilizes the NLTK Sentiment Intensity Analyzer to assign sentiment scores to answers.
**Feature Extraction:** TF-IDF vectorization is applied to both prompts and answers, and additional features such as sentiment, conversation length, and user experience are computed.
**Model Training:** A dummy classifier is trained on sentiment features to explore the baseline performance of sentiment prediction.

For inquiries related to Research Question 2 (KB23U),
Email: kb23u@fsu.edu
