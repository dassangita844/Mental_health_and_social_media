# **Social Media and Its Adverse Effects on the Psychological Health of Students**

## **Introduction**

This research project investigates the relationship between social media usage and its adverse effects on the psychological health of students. Using a dataset sourced from Kaggle, the study analyzes behavioral and emotional patterns among school and university students, focusing on the impact of social media on mental health indicators such as sleep, depression, and emotional well-being. The project employs statistical methods and machine learning models to extract insights and highlight patterns in social media's psychological effects.

## **Research Objectives**

1. Analyze the influence of demographic factors (age, gender, relationship status) on students' average daily time spent on social media.  
2. Construct a composite Negative Impact Score derived from mental health indicators.  
3. Apply machine learning models to assess the relationship between social media usage and its negative effects on mental health.  
4. Investigate how social media contributes to sleeping issues using classification techniques.


## **Dataset Information**

### **Source**
The dataset was sourced from Kaggle: [Social Media and Mental Health Dataset](https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health/data).  

### **Overview**
The dataset consists of 481 rows and 21 columns. Each row represents a unique participant's data, capturing various aspects of social media behavior, demographic characteristics, and emotional well-being.  

### **Variables**
Below are the key variables in the dataset:  

| **Variable Name**          | **Description**                                                                                 | **Type**             |  
|-----------------------------|-----------------------------------------------------------------------------------------------|----------------------|  
| `timestamp`                | Time when the data was recorded.                                                              | Datetime            |  
| `age`                      | Participant's age.                                                                            | Numeric             |  
| `gender`                   | Participant's gender (e.g., Male, Female, Nonbinary, etc.).                                   | Categorical         |  
| `relationship`             | Relationship status (e.g., Single, Married, In a relationship).                              | Categorical         |  
| `occupation`               | Participant's occupation (e.g., Student, Salaried Worker).                                   | Categorical         |  
| `organization`             | Type of organization affiliated (e.g., University, Company).                                 | Categorical         |  
| `social_media_use`         | Whether the participant uses social media (Yes/No).                                          | Binary              |  
| `platforms`                | Commonly used social media platforms (e.g., YouTube, Facebook).                              | Categorical         |  
| `avg_time_per_day`         | Average daily time spent on social media (in hours).                                         | Numeric             |  
| `without_purpose`          | Frequency of purposeless use of social media (Likert scale: 1-5).                            | Ordinal             |  
| `distraction`              | Frequency of distraction caused by social media (Likert scale: 1-5).                         | Ordinal             |  
| `feel_restless`            | Feeling of restlessness due to lack of social media (Likert scale: 1-5).                     | Ordinal             |  
| `distracted`               | Degree of distraction experienced by the participant (Likert scale: 1-5).                    | Ordinal             |  
| `worries`                  | Degree of worries experienced by the participant (Likert scale: 1-5).                        | Ordinal             |  
| `concentration`            | Difficulty in concentrating (Likert scale: 1-5).                                             | Ordinal             |  
| `compare_to_others`        | Frequency of comparisons to others on social media (Likert scale: 1-5).                      | Ordinal             |  
| `compare_feelings`         | Feelings resulting from comparisons (Likert scale: 1-5).                                     | Ordinal             |  
| `validation`               | Frequency of seeking validation through social media (Likert scale: 1-5).                    | Ordinal             |  
| `depressed`                | Frequency of depressive feelings (Likert scale: 1-5).                                        | Ordinal             |  
| `daily_activity_fluctuate` | Fluctuation in interest in daily activities (Likert scale: 1-5).                             | Ordinal             |  
| `sleeping_issues`          | Frequency of sleeping issues experienced by the participant (Likert scale: 1-5).             | Ordinal             |  

### **Likert Scale Details**
Variables from `without_purpose` to `sleeping_issues` are measured on a Likert scale (1 to 5):  

| **Scale Value** | **Meaning**              |  
|------------------|--------------------------|  
| 1                | Very Low (Rarely/Never) |  
| 2                | Low                     |  
| 3                | Moderate                |  
| 4                | High                    |  
| 5                | Very High (Very Often)  |  


## **Methods**

1. **Data Preparation**:  
   - Cleaning and preprocessing the data (e.g., handling missing values, renaming variables).  
   - Encoding categorical variables for analysis.  

2. **Composite Index Creation**:  
   - Constructing a composite Negative Impact Score using 12 variables such as `distraction`, `worries`, `validation`, and `depressed` etc.  

3. **Machine Learning Models**:  
   - Regression and classification models to analyze the relationships between social media usage patterns and mental health indicators.  

4. **Classification Analysis**:  
   - Investigating how social media contributes to `sleeping_issues` using classification techniques like decision trees or logistic regression.  


## **Contact**  
For any questions or feedback, contact **Sangita Das** at:  
📧 **dassangita844@gmail.com**  

## **License**  
This project is licensed under the MIT License. See the LICENSE file for details.  

## **Acknowledgments**  
Special thanks to Kaggle for providing the dataset and to Python, the programming language used in Google Colab, for facilitating the tools and frameworks that made this project possible.
