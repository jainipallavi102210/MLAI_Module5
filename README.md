# MLAI_Module5

### Coupon Acceptance Prediction

Welcome to the Coupon Acceptance Prediction project! This repository serves as a practical application for the MLAI (Machine Learning and Artificial Intelligence) course, where we apply our learnings in exploratory data analysis, plotting, statistical summarization, and data visualization techniques to a machine learning problem.

### Dataset Overview

The dataset used in this project is sourced from the UCI Machine Learning Repository and was collected through a survey conducted on Amazon Mechanical Turk. The survey presents various driving scenarios, capturing information such as the destination, current time, weather conditions, passenger details, and more. Participants were asked to indicate whether they would accept a coupon if they were the driver in each scenario. 

### Project Goals

The primary goal of this project is to predict whether a driver will accept a coupon based on the provided information. By leveraging the dataset's features, we aim to gain insights into the factors influencing coupon acceptance and explore the potential for personalized coupon recommendations.

### Repository Structure

This repository consists of the following files:

README.md: Provides an overview of the project and repository.
data/coupons.csv: The raw dataset file containing the survey responses.
couponacceptance.ipynb: A Jupyter Notebook that focuses on data preprocessing, cleaning and explores the dataset through descriptive statistics, visualizations, and correlation analysis. [Jupyter Notebook](https://github.com/jainipallavi102210/MLAI_Module5/blob/main/couponacceptance.ipynb)


### Getting Started

To get started with this project, you can clone the repository and access the Jupyter Notebooks for each stage of the project. 

### Summary of findings

#### Bar coupons Acceptance

1. Drivers who frequently visit cheap restaurants may be more open to accepting bar coupons because they are already budget-conscious and seek value in their dining experiences.They may see the bar coupons as an opportunity to explore new places or enjoy discounted drinks.
    
2. Individuals who frequently visit bars, regardless of other conditions, might have a higher tendency to accept bar coupons. This group likely enjoys the bar scene and is interested in exploring new venues or saving on their preferred social activities.

3. These hypotheses suggest that drivers who accepted the bar coupons may have specific characteristics such as being cost-conscious, socially active, or interested in exploring new experiences. However, it's important to note that these are just hypotheses based on the provided observations, and further analysis and experimentation would be needed to confirm or validate these hypotheses.


#### CarryAway coupouns Acceptance

1. Drivers who are single or in a married partnership and have a higher frequency of takeaways may be more likely to accept carryaway coupons due to their convenience and preference for dining out.  

2. The inverse relationship between income and coupon acceptance suggests that drivers with higher incomes may be less motivated to use coupons as they have more financial resources available for dining options.  

3. The prevalence of accepted coupons among individuals in categories such as Unemployed, Students, and those working in the Computer & Mathematical field indicates that these groups may be more open to utilizing coupons to save on their dining expenses.  

4. The finding that coupon acceptance is not influenced by drivers traveling in the same direction suggests that the decision to accept coupons is independent of the specific route or destination of the driver.  
    
5. In summary, drivers who accepted carryaway coupons may exhibit a higher frequency of takeaways, belong to certain occupational categories, and have lower income levels. However, further research and analysis are required to validate these hypotheses and gain a deeper understanding of the drivers' behaviors and motivations in accepting carryaway coupons.  
    

More details on the approach of analysis can be found in the [Jupyter Notebook](https://github.com/jainipallavi102210/MLAI_Module5/blob/main/couponacceptance.ipynb)