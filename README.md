# Analysis of Online Shopping Behaviours
![Analysis of](https://github.com/user-attachments/assets/d0f306ca-3652-4189-bcaf-5a15598846b5)

## 📚 Table of Contents 📚
| Section | Title                                        |
| ------- | -------------------------------------------- |
| 1       | [Introduction](#section0)                    |
| 2       | [Project Overview](#section1)                |
| 3       | [Data Overview](#section2)                   |
| 4       | [Approach to Analysis](#section3)            |
| 5       | [Tools and Technologies](#section4)          |
| 6       | [Exploratory Data Analysis (EDA)](#section5) |
| 7       | [Insights and Findings](#section6)           |
| 8       | [Conclusion](#section7)                      |
| 9       | [Future Work](#section8)                     |

You may view the completed Jupyter Notebook [HERE](https://github.com/charmieboo/analysis-of-online-shopping-behaviours/blob/main/Analysis%20of%20Online%20Shopping%20Behaviours.ipynb).

<a id=section0></a>
## 1. Introduction
This project focuses on analyzing online shopping behaviors to better understand the factors influencing whether a visitor generates revenue on an e-commerce website. The analysis utilizes Python and various data science techniques to extract actionable insights, which can help businesses optimize their marketing strategies and website performance.

<a id=section1></a>
## 2. Project Overview
Online shopping has become an integral part of modern retail, and understanding user behavior on e-commerce platforms is crucial for improving conversions. This project aims to:
- Analyze website visitor interactions such as product views, time spent, and page types visited.
- Identify correlations between user activity and the likelihood of a visitor making a purchase.
- Provide actionable insights to enhance online shopping experience and increase sales.

<a id=section2></a>
## 3. Data Overview
The dataset includes the following columns:
- **Numerical Columns**: These include visitor metrics such as `Administrative`, `ProductRelated`, and `BounceRates`.
- **Categorical Columns**: These include `Month`, `VisitorType`, and `Weekend` (boolean).
- **Target Variable**: `Revenue` (boolean), indicating whether a visitor generated revenue.

**Notes:**
Column `ProductRelated_Duration` has values greater than its 99th percentile, with maximum values exceeding 63,000 seconds (or 17.5 hours). These outliers were eliminated from the analysis to avoid skewed insights.

<a id=section3></a>
## 4. Approach to Analysis
- **Data Cleaning**: Removed extreme outliers and handled missing data to ensure data quality.
- **Exploratory Data Analysis (EDA)**: Conducted analysis to visualize and understand visitor patterns, behavior trends, and features contributing to conversion.
- **Feature Engineering**: Added new features such as total time spent on site and page interactions.
- **Modeling**: Developed machine learning models to predict if a visitor would generate revenue.

<a id=section4></a>
## 5. Tools and Technologies
The project utilized the following tools and technologies:
- **Python**: Primary programming language for data processing and analysis.
- **Pandas & NumPy**: Libraries used for data manipulation and numerical operations.
- **Matplotlib & Seaborn**: Libraries used for visualizing data to support exploratory analysis.
- **Scikit-Learn**: Used for building and evaluating predictive models.

<a id=section5></a>
## 6. Exploratory Data Analysis (EDA)
During EDA, the following key insights were explored:
- **Visitor Behavior**: How metrics such as `ProductRelated` visits, `BounceRates`, and time spent on `Administrative` pages impact conversion.
- **Weekend Impact**: Analyzed the difference between weekday and weekend visitors in terms of engagement and conversion.
- **Visitor Type**: Compared new vs. returning visitors to understand their likelihood of making a purchase.

<a id=section6></a>
## 7. Insights and Findings
- **ProductRelated Views and Duration**: A positive correlation was found between the number of product-related pages visited and the likelihood of revenue generation.
- **Bounce Rates**: Higher bounce rates were found to be negatively associated with conversion, emphasizing the importance of user engagement.
- **Returning Visitors**: Returning visitors were more likely to generate revenue compared to new visitors, suggesting the value of customer retention strategies.

<a id=section7></a>
## 8. Conclusion
The analysis provided valuable insights into online shopping behaviors that can help optimize e-commerce platforms for improved conversion. By understanding user interactions, businesses can implement strategies to reduce bounce rates, increase product views, and enhance overall engagement.

<a id=section8></a>
## 9. Future Work
Future iterations of this project could include:
- **A/B Testing**: Implement A/B testing strategies to evaluate changes made to the website based on findings from this analysis.
- **Advanced Modeling**: Develop more sophisticated predictive models to improve the accuracy of conversion predictions.
- **Segmentation Analysis**: Perform segmentation analysis to further identify key user groups and tailor personalized marketing campaigns.

---

If you have any questions or want to collaborate, feel free to reach out!
