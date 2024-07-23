# neural-network-challenge-1

A data analysis assignment for Columbia University's AI bootcamp.

I worked with ChatGPt4o to complete this assignment.

## Project Overview
As a business intelligence data analysts, I’m working with a company that specializes in student loan refinancing. The company wants me to provide a solution that will predict whether a borrower will repay their loan, allowing them to provide a more accurate interest rate for the borrower. The company has asked me to create a model to predict student loan repayment based on CSV file also located in repository which contains information about previous student loan recipients, such as their credit ranking.

## Methods
Given my task, available data, and tools, I decided to use a neural network model to predict student loan repayment. The solution/code is written in Python and uses the TensorFlow library to build and train the neural network model. The model is trained on the data provided in the CSV file, and the model's performance is evaluated using the test data.

## Recommendations
**1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.**

To build a recommendation system for student loan options, we would need to collect specific data on the student and the different loan options available in order to personalize loan recommendations to each student's unique circumstances and characteristics. A student's age, gender, educational level, field of study, the institution they are attending, their current loan debt, and loan history would be relevant data to collect to match them with the appropriate lender, loam amount, interest rates, and repayment terms.

**2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.**

Content-based filtering would be the most appropriate method based on the goal of providing recommendations that take into account the content or unique features/circumstances of each student and the different loan options available, ensuring the recommendations are personalized. Collaborative filtering wouldn't be appropriate given its reliance on data from other students' loan choices, which may not be appropriate and conflicts with the intent of personalization. Although context-based filtering can provide personal data about a student's behavior and why or when certain loan options are available, it is based on situational relevance and may not be as effective in making long-term loan recommendations.

**3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.**

Real-world challenges for this recommendations system would be navigating the terms and conditions of students loans, and how to integrate those terms and conditions into the environment or platform used by the financial institution or loan provider. Along with collecting detailed information that outlines   interest rates, repayment plans, grace periods, and other terms, that data would also have to be maintained and updated regularly to ensure accuracy. Regarding the recommendation system's integration into the loan application, process would be challenging given the variety of platforms and APIs used by different institutions along with the responsibility of complying with privacy and security regulations which protect sensitive student data.
