## CS5265 Foundations of Machine Learning
### Week 6 Assignment: Feature Engineering
**Deadline: Sunday 6/19 11:59PM (CDT)**

### I. Purpose:
1. Learn how to prepare categorical data for machine learning
2. Learn how to prepare numerical data for machine learning
3. Learn how to prepare text data for machine learning
4. Practice selecting relevant features

### II. Grading and Submission 
1. The assignment will be evaluated in a total of 50 points
2. Use this template to create a new private repository named [section_no]-assign06-[GH_username] in the vanderbilt-ml repo
3. Work must be completed by the deadline stated in the repository readme. 

### III. Tasks: 

Read chapters 5 and 6 of  Max Kuhn’s http://www.feat.engineering/

#### Task 1 [30 points]: Feature engineering for the employee-churn dataset
- For this task, you will discuss your plan to create or engineer **two features** (variables) for the employee-churn project  
- Include the following template in each issue:
  - Description of the variable you plan to perform feature engineering on
  - Description of the plan of your feature engineering process
  - Rationale of your choice of feature
  - Plan for unit testing after introducing this feature (no implementation needed; just a description will suffice)
- Implement your feature engineering step for the two chosen variables using Python in your notebook (this can be your notebook from assign-05). **NOTE**: If you already engineered two features from assign-05, feel free skip the implementation in this step
- Close each issue with a commit 
- Update your pipeline to include the two new features 
- Discuss in a **text cell** in your notebook how your model's performance increased or decreased with feature1, feature2, both feature1 and 2


#### Task 2 [30 points]: Feature engineering for your project
- Repeat Task 1 for your personal project

#### Extra credit 1: [20 points]
- Explore how to incorporate feature engineering in a pipeline

#### Extra credit 2: [40 points]
- Explore how to produce embeddings for a categorical variable (using [HuggingFace](https://huggingface.co/docs/api-inference/index))




