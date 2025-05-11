# IFI Master's Project Proposal

## Title
**Early Detection of Depression through Analysis of Symptomatology and Conversational Contexts in Social Networks (eRISK Challenge 2025)**

## Supervisors
_To be decided_

## Intended Start
Beginning August 2025 



## Background

Depression is a major public health concern worldwide, affecting hundreds of millions of people. Early detection is critical for timely intervention and treatment. With the widespread use of social media, it has become possible to analyze users' online communications to infer mental health states.

This project focuses on leveraging Machine Learning techniques to detect early signs of depression by analyzing textual data from social networks, particularly aiming to identify sentences indicative of specific depressive symptoms as defined in the Beck Depression Inventory II (BDI-II).

The ultimate goal is to develop models capable of understanding full conversational contexts, not just isolated messages, for improved prediction accuracy and eventual deployment in conversational agents for real-time mental health assessment.



## Goals

- **Task 1:** Develop an intelligent system capable of ranking individual sentences according to their relevance to each of the 21 depressive symptoms outlined in the BDI-II questionnaire.
- **Task 2:** Design a sequential model that analyzes entire conversational contexts (streams of posts and comments) to predict the likelihood of depression for individual users.
- **Task 3 (Optional/TBD):** Develop an interactive chatbot capable of assessing users' mental health during natural dialogue and detecting early signs of depression.


## Research Objectives

- Compile and preprocess datasets containing social media posts, organized at the sentence and conversation level.
- Design and train ML models to:
  - Detect symptom-specific sentence relevance (Task 1).
  - Model user-level depression probability through temporal conversation analysis (Task 2).
- Rank sentences based on their alignment with the following 21 BDI-II symptoms:

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
  21. Physical disorders related to emotional state

---

## Data Sets

- **Task 1 Dataset:**
  - Individual `.ter` files consisting of segmented user sentences with unique identifiers.
  - Purpose: Rank sentence relevance for each BDI-II symptom.

- **Task 2 Dataset:**
  - Chronological streams of user posts and comments, including full conversational context, metadata (timestamps, user IDs), and user categorization (control vs. positive for depression).




## Output

- **Task 1:**
  - A ranked list of depressive symptoms most relevant to each sentence analyzed.
- **Task 2:**
  - A prediction score indicating the likelihood of depression for each user based on sequential conversation modeling.
- **Task 3 (TBD):**
  - A prototype of a conversational agent capable of real-time mental health state assessment through dialogue.

---

## Requirements

- Strong motivation and interest in mental health applications and social media analysis.
- Good programming skills, especially in Python (experience with PyTorch or TensorFlow is advantageous).
- Familiarity with Natural Language Processing (NLP).



## Contact

_To be added_
