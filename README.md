# eRISK_Challenge_2025 (Draft Version)
Early Detection of Depression through Analysis of Symptomatology and Conversational Contexts in Social Networks

## Goals:
1. Developing an intelligent system capable of detecting and ranking sentences according to their relevance to each of the 21 depressive symptoms defined in the BDI-II questionnaire.

    The 21 items of the BDI questionnaire are the following: 
    
    1. Sadness
    2. Pessimism
    3. Feelings of failure
    4. Loss of pleasure
    5. Feelings of guilt
    6. Feelings of punishment
    7. Dissatisfaction with oneself
    8. Severe self-criticism
    9. Suicidal thoughts or desires
    10. Crying
    11. Agitation
    12. Loss of interest
    13. Indecisiveness
    14. Loss of energy
    15. Changes in sleeping habits
    16. Irritability
    17. Changes in appetite
    18. Difficulty concentrating
    19. Tiredness or fatigue
    20. Loss of interest in sex
    21. Physical disorders (pain or discomfort related to emotional state)
    
    These 21 feelings correspond to the symptoms evaluated in the Beck Depression Inventory (BDI-II), a widely used self-report questionnaire designed to assess the severity of depressive symptoms in individuals. Each of these symptoms represents a distinct psychological or physical manifestation commonly associated with depression.
    The BDI-II includes a scoring scale for each symptom, ranging from 0 to 3, where higher scores indicate greater severity or frequency of that particular symptom. 

2. Design a sequential model capable of detecting depression through the analysis of full conversational contexts (more than just individual messages). 

# Data sets 

## Task 1: 

The dataset for the first task or goal consists of .ter files, composed of texts written by different people. Each file groups a user's segmented sentences, individually tagged with unique identifiers.
Example: 

![image](https://github.com/user-attachments/assets/7d5d1cfc-8af3-4344-97f9-6a0c7c92e5d2)

This phrases will be the ones used to evaluate the importance with respect to the 21 symptoms from BDI-II

## Task 2: 

* A chronological stream of posts and comments, including the target user's writings and their conversational context.

* Metadata such as timestamps and user identifiers

  Example:

  ![image](https://github.com/user-attachments/assets/be823189-7e47-4dd6-af93-60ac1288a385)

The dataset is divided in control users and positive users divided diferent folders. 

Since the task was new for this year, non test-dataset exist. 

# Output 

## Task 1:

* A list of BDI symptoms that show the highest relevance in the analyzed text, ranked according to their degree of presence or correspondence with the content of the sentence.

## Task 2:

* A prediction for each user indicating the likelihood of depression.
## Task 3 -- TBD  
Ideally, if the results are promising, our goal would be to develop an interactive chatbot or conversational agent capable of engaging in natural dialogue while continuously assessing the user's mental state, with the ability to detect early signs of depression.


