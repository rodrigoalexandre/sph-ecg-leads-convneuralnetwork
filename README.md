## **DESCRIPTION**

Project developed for the study presented in the article *“A Comparative Study of ECG Leads in Predicting Cardiac Arrhythmias Using Deep Learning Models”* published by *European Journal of Engineering Science and Technology* (Volume 08, Issue 01, Jun. 2025).

**Cardiac arrhythmias** are a group of conditions that have a high incidence and prevalence worldwide. The **Electrocardiogram (ECG)** is the main tool for the diagnosis of cardiac arrhythmias. The so-called **12-lead system** is the most widely used ECG configuration in clinical practice and has been considered for several years as the gold standard for detecting cardiac arrhythmias. Although this configuration is widely popular, there are situations in which it may be more interesting to use simpler ECG configurations to expand the tool to scenarios other than traditional healthcare environments, such as using mobile devices for cardiac monitoring. Knowing the performance of each lead when considered individually is important for defining which leads are most suitable for use in each scenario.

This study presents a comparative analysis of the ECG leads for predicting cardiac arrhythmias employing a deep learning-based approach and a large dataset containing diagnoses of 32 types of arrhythmias. The results demonstrate the feasibility of using technologies based on Artificial Intelligence as tools to support the expansion of cardiac monitoring practices to environments outside clinics and hospitals.
<br><br>
## **PROJECT STRUCTURE**

|--- source<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- generate-csv-dataset.ipynb (Python code to convert the original HDF5 files to CSV)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- preprocess-sph-dataset.ipynb (Python code for analyzing and preprocessing the dataset)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- conv-neuralnetwork-model.ipynb (Python code to create and train the CNN model)<br>
|--- modelconfig<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- CNN model training configuration files.<br>
|--- dataset<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- The dataset location.
<br><br>
## **ARTICLE LINK**
https://doi.org/10.33422/ejest.v8i1.1472
<br><br>
## **RESOURCES**
The dataset used in this study is publicly available at: https://doi.org/10.6084/m9.figshare.c.5779802.v1
<br><br>
## **LICENSE**
This project is available under the MIT license. See the LICENSE file for more details. 
<br><br>
