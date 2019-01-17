# HR-Activity

EMPLOYEE TURNOVER 

PROBLEM: One of the main challenges of work is employee turnover problem. Replacing a worker usually costs 20% - 30% of workers yearly income(on-boarding, off-boarding, hiring cost) and months to years of experience for employee to reach at their peak performance.

OBJECTIVE:To understand what factors contributed most to employee turnover.

 
          Perform clustering to find any meaningful patterns of employee traits.


          Create a model that predicts the likelihood if a certain employee will leave the company or not. 


          Implementing this model will allow management to create better decision-making actions.

DATASET: SATISFACTION_LEVEL - The satisfaction level of employee on a scale of 0-1
         LAST_EVALUATION - The time when employee last evaluated on a scale of 0-1
         NUMBER_PROJECT - Projects completed by the employee
         AVERAGE_MONTLY_HOURS - Average number of hours the employee had worked each month
         TIME_SPEND_COMPANY - Number of years the employee spent at the company
         WORK_ACCIDENT - If the employees had any work accident
         LEFT - If the employee left the company or not (Turnover)
         PROMOTION_LAST_5YEARS - If the empllyee had any promotion in last 5 years
         SALES - The department employee is working for
         SALARY - The salary level of the employee (Low, Medium and High)  

MODELS : Unsupervised Algorithm (K-Means clustering) to find the satisfaction level of the employees.
         Upsampling method to get rid of class imbalance
         Logistic regression, Random Forest  and Gradient boosting

RESULTS: Random Forest provides the best result with predicting the Employee turnover with a precision and recall result of 99%.

TOP 5 FEATURE IMPORTANCE: Satisfaction_level
                Time_spend_company
                Average_montly_hours
                last_evaluation
                number_project
