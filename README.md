# EduPlus Customer Churn Analysis

## 🎯 Overview
Analysis of customer data for **EduPlus** — an online education platform — to identify the causes of service abandonment (churn) and propose customer retention strategies.

## 🚀 Objectives
* **Identify** behavioral factors affecting the churn rate.
* **Segment** customers by their risk of churning.
* **Propose** specific intervention strategies for each group.
* **Visualize** all results via an interactive **Power BI Dashboard**.

## 📊 Data Description
The dataset includes **10,000 customers** with **18 variables**.

| # | Field Name | Description | Data Type |
| :--- | :--- | :--- | :--- |
| 1 | **CustomerID** | Unique customer identifier | Integer |
| 2 | **Age** | Customer's age (18-60) | Integer |
| 3 | **Gender** | Customer's gender (Male, Female, Other) | Categorical |
| 4 | **Marital Status** | Single, Married, Divorced, Widowed | Categorical |
| 5 | **Occupation** | Student, Professional, Self-Employed, Other | Categorical |
| 6 | **GeographicLocation** | Customer's city (Hanoi, HCM, Da Nang, etc.) | Categorical |
| 7 | **Login Frequency** | Login times per week (0-7) | Integer |
| 8 | **ContentType** | Main content viewed (Courses, Webinars, etc.) | Categorical |
| 9 | **AvgWatch Time** | Average weekly watch time (hours) | Float |
| 10 | **SubscriptionStartDate**| Service subscription start date | Date |
| 11 | **Payment Method** | Credit Card, PayPal, Bank Transfer, etc. | Categorical |
| 12 | **Payment Frequency** | Monthly, Quarterly, Yearly | Categorical |
| 13 | **LatePaymentCount** | Number of late payments (0-5) | Integer |
| 14 | **ServiceRating** | Service quality rating (1-5) | Integer |
| 15 | **SupportRequests** | Number of customer support requests | Integer |
| 16 | **SupportSatisfaction**| Satisfaction level after support (1-5) | Integer |
| 17 | **SurveyFeedback** | Feedback via survey (Positive, Neutral, Negative) | Categorical |
| 18 | **Churned** | Customer churn status (Yes/No) | Binary |

## 📈 Key Analysis Results
* **Overall churn rate:** 28.97%
* **Average service rating:** 3.54/5
* **Average tenure before churning:** 12 months

### Main Behavioral Factors:
1. **Engagement Level:** Churning group logs in only **2.83 times/week** vs **3.74** for non-churners.
2. **Payment Behavior:** **Credit Card** users have a churn rate of **42.39%**, nearly double other methods.
3. **Support Quality:** Satisfaction level 1/5 leads to a **42.39%** churn rate.

## 👥 Customer Segmentation
| Segment | Customer Count | Churn Rate |
| :--- | :--- | :--- |
| **High Risk** | 1,145 (11.45%) | **57.21%** |
| **Potential** | 8,415 (84.15%) | 26.29% |
| **Loyal** | 440 (4.4%) | 6.82% |

## 💻 Power BI Dashboard
The dashboard consists of 4 main pages:
* **Overview:** Overall KPIs and churn trends.
* **Demographics:** Analysis by age, gender, and location.
* **Behavior:** Platform interaction and payment behavior.
* **Action Plan:** Risk segmentation and priority matrix.

## 🛠 Tools Used
* **Power BI Desktop:** Dashboard construction and visualization.
* **DAX:** Creating measures (Churn Rate, RiskSegment, etc.).
* **Excel & CSV:** Data cleaning and initial processing.
