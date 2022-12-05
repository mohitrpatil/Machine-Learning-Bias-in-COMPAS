# Exploring Machine Learning Bias in COMPAS
## CSE 598: Machine Learning Security and Fairness
<br>

### Introduction
The code is responsible for conducting experiments to explore biases in compas dataset and mitigate them using different pre-processing, in-processing and post-processing algorithms and compare the results before and after bias elimination.  Each approach or experiment conducted is a form of different ipynb file (Jupyter Notebook Python code). The dataset used in all the experiments is Compas which is available in the repository.

### How to Run
1. The repo contains the file named compas-scores-two-years.csv which contains the dataset <br>
2. The code makes use of google drive for getting the dataset. Kindly upload the above csv file in the content folder. <br>
3. The code runs end-to-end to find out results and the metrics.
<br>3.1 Bias Exploration - Bias_Exploration.ipynb
<br>3.2 Pre-processing Reweighing- PreProcessing_Reweighing.ipynb
<br>3.3 In-processing Adversarial Debiasing- Inprocessing_Adversarial_Debiasing.ipynb
<br>3.4 PostProcessing reject option classification- PostProcessing_reject_option_classification.ipynb
4. PreProcessing_Reweighing.ipynb & PostProcessing_reject_option_classification.ipynb has different model (Naive Bayes, Linear SVC) functions defined. You can use those functions to see how the algorithms perform on these models.
5. Once it has run, you can see the graphs which will help you to understand the results correctly.