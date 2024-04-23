# Trends in Mental Health: Analyzing the Prevalence of Anxiety Disorders and Depression in the United States (1990-2017)
The repository contains a catalog of carefully selected subsets of data extracted from [Global Trends in Mental Health Disorder](https://www.kaggle.com/datasets/thedevastator/uncover-global-trends-in-mental-health-disorder) datasets. The initial dataset includes information from a worldwide perspective, detailing the prevalence of various mental health disorders such as schizophrenia, bipolar disorder, eating disorders, drug use disorders, alcohol use disorders, anxiety disorders, and depression. In this repository, we will mainly focus on the trends in the prevalence of anxiety disorder and depression in the U.S. In addition, it contains a Python Jupyter Notebook that methodically documents the process of generating subsets and ensuring their reproducibility. 

### Overview
Getting started on this repository, carefully read through each section below. If you have any questions, please use the email address at the bottom of the page to contact.
1. Background information about mental health in the United States
2. Data provenance
3. Data visualization and analysis
4. Usage for future research
5. Instruction on reproducing the dataset
6. Author and contact information

### Background Information
Mental health has increasingly become a focus of public health efforts in the United States, acknowledging its significant impact on overall well-being and productivity. In terms of prevalence, conditions such as anxiety disorders and depression are among the most common mental health challenges, impacting millions of Americans. The data from 1990 to 2017 indicates that the prevalence of these conditions has been increasing, suggesting a need for continued investment in mental health services, research into causative factors, and public health strategies aimed at prevention and early intervention.

### Data Provenance
- The raw data is sourced from _Kaggle_ :
[Global Trends in Mental Health Disorder
](https://www.kaggle.com/datasets/thedevastator/uncover-global-trends-in-mental-health-disorder)
- The original data is generated from _Our World in Data_ : [Mental Health](https://ourworldindata.org/mental-health)

### Data Visualization and Analysis

In general, the multi-line chart presentation allows for a comparison between the two mental health disorders, which indicates that while both have shown increases, the pattern for anxiety disorders contains more variability within the period, whereas depression shows a steadier increase. The sharp peak in anxiety disorders suggests a year or years of significant growth, which might need further research to understand the underlying factors contributing to this change.

![data-viz](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/data_visual/Prevalence_of_Anxiety_Depression_U.S..png)

- __Anxiety Disorders__: The graph for anxiety disorders shows a dramatic spike in prevalence from 1995 to 2010, which could suggest an external event, such as the inflation and financial crisis in the early 21st century, or a change in diagnostic practices that resulted in a surge in anxiety disorder diagnoses. After the spike, the prevalence quickly reverts to levels similar to those before the peak.
- __Depression__: The prevalence of depression has increased more steadily over the years, suggesting a gradual rise in the number of reported cases or diagnoses. This consistent climb might reflect several factors, including improved condition recognition, reduced stigma, popularization of mental health, and more accurate reporting. However, it could also indicate a genuine rise in the incidence of depression due to societal factors.

The data visualization is created using [Datawrapper](https://www.datawrapper.de/). 

### Usage for Future Research

Each prospective study route listed below could significantly contribute to our understanding of mental health,  allowing us to develop more effective strategies for prevention, treatment, and support.
- **Healthcare Planning**: The data can help to predict future needs for mental health services, allocate resources effectively, and plan for healthcare infrastructure.
- **Cross-Cultural Comparisons**: When combined with similar datasets from other countries, it could help in conducting cross-cultural studies on the prevalence and treatment of mental health conditions.
- **Machine Learning Models**: The dataset can be used to build mathematical models for early intervention or to predict future trends in mental health within the population.

Here are some other useful subsets of Global Trends in Mental Health Disorders that are generated from the _Python Jupyter Notebook_:
- [Schizophrenia](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/csv/Schizophrenia.csv)
- [Bipolar Disorder](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/csv/Bipolar_Disorder.csv)
- [Eating Disorder](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/csv/Eating_Disorder.csv)
- [Anxiety Disorder](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/csv/Anxiety_Disorder.csv)
- [Drug Use Disorder](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/csv/Drug_Use_Disorder.csv)
- [Depression](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/csv/Depression.csv)
- [Alcohol Use Disorder](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/csv/Alcohol_Use_Disorder.csv)
- [Global Trends in Mental Health Disorder - Mean Data](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/csv/Mean_Data.csv)
- [Global Trends in Mental Health Disorder - Filtered](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/csv/filtered.csv)

  
### Instruction on Reproducing the datasets by Using _Python Jupyter Notebook_
Within this repository, you will find the three primary files:
- The CSV file containing the original dataset, [click to view ->](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/Mental%20health%20Depression%20disorder%20Data.csv)
- The _Python Jupyter Notebook_ containing the instructions for filtering data and creating new subsets, [click to view ->](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/Zhang_unit_project.ipynb)
- The CSV file containing the new subset of United States Depression and Anxiety Disorder, [click to view ->](https://github.com/zzhang2027/Anxiety_Depression_U.S./blob/main/US_Anxiety_Depression.csv)

To get started reproducing the dataset, redirect yourself to the _Python Jupyter Notebook_ file. Carefully read through the Overview section and follow the instructions. 

### Author and Contact Information
Zhaojiayi Zhang
Undergraduate, University of North Carolina at Chapel Hill
Email: zzhang27@unc.edu
