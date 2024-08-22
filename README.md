# AWS-Deployment

## Employee Attrition Prediction on AWS SageMaker

### Overview
This project demonstrates how to deploy a machine learning model for predicting employee attrition using AWS SageMaker. The project includes source code, model files, and detailed documentation on deploying the solution using the synthetic Employee Attrition Dataset.
### Dataset
The Synthetic Employee Attrition Dataset is designed for the analysis and prediction of employee attrition. It contains 74,498 samples, divided into training and testing sets, and includes features such as employee demographics, job-related attributes, and personal circumstances. The goal is to identify factors that contribute to employee attrition and develop predictive models to mitigate it.
### Key Features:
+ Employee ID: Unique identifier for each employee.
+	Age: Employee's age (18-60 years).
+	Gender: Employee's gender.
+	Years at Company: Number of years the employee has worked at the company.
+	Monthly Income: Employee's monthly salary in dollars.
+	Job Role: Employee's role or department.
+	Work-Life Balance: Employee's perceived work-life balance (Poor, Below Average, Good, Excellent).
+	Job Satisfaction: Employee's job satisfaction level (Very Low, Low, Medium, High).
+	Performance Rating: Employee's performance rating (Low, Below Average, Average, High).
+	Number of Promotions: Number of promotions received by the employee.
+	Distance from Home: Distance between the employee's home and workplace, in miles.
+	Education Level: Highest education level attained (High School, Associate Degree, Bachelor’s Degree, Master’s Degree, PhD).
+	Marital Status: Employee's marital status (Divorced, Married, Single).
+	Job Level: Employee's job level (Entry, Mid, Senior).
+	Company Size: Size of the company (Small, Medium, Large).
+	Company Tenure: Number of years the employee has been in the industry.
+	Remote Work: Whether the employee works remotely (Yes, No).
+	Leadership Opportunities: Whether the employee has leadership opportunities (Yes, No).
+	Innovation Opportunities: Whether the employee has opportunities for innovation (Yes, No).
+	Company Reputation: Employee's perception of the company's reputation (Very Poor, Poor, Good, Excellent).
+	Employee Recognition: Level of recognition the employee receives (Very Low, Low, Medium, High).
+	Attrition: Whether the employee has left the company (0 = Stayed, 1 = Left).

 ### Project Structure
+	/source code: Contains the source code for data preprocessing, model training, and deployment scripts.
+	/model: Stores the trained model files.
+	/documentation: Includes documentation for setting up and deploying the model on AWS SageMaker.

### Getting Started

### Prerequisites
+	AWS Account
+	AWS CLI configured
+	Python 3.7+
+	SageMaker SDK

### Deployment
Follow the steps in /documentation/AWS-Deployment.md to set up your AWS environment and deploy the model using SageMaker.

### Usage
Once the model is deployed, you can use it to make predictions on new employee data to identify potential attrition risks.

### Contributing
Feel free to open issues or submit pull requests if you have any suggestions or improvements.



