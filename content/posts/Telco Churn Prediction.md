---
title: "Telco Churn Prediction"
date: 2025-05-11
draft: false
categories: ["Technology"]
---

# **How I Built a Customer Churn Prediction App for Telecom Companies**

I recently completed a fascinating project for my AI and Decision Making course in my Master of Business Analytics program, and I wanted to share this journey with you all. Our team tackled a real-world business problem: customer churn in the telecommunications industry.

## **The Challenge: Predicting Who's About to Leave**

Telecom companies face a constant battle to retain customers in today's competitive market. Did you know that acquiring new customers costs significantly more than retaining existing ones? This makes identifying customers at risk of leaving (churning) incredibly valuable.

Our challenge was to build a predictive model that could accurately forecast which customers were likely to cancel their service, and then create a user-friendly application that would make these insights actionable.

## **Our Approach: Data Science Meets Business Strategy**

We started with a comprehensive dataset from a telecom company containing customer demographics, service usage, contract details, and payment information. After cleaning and preparing the data, we engineered some additional features to enhance our model's predictive power.

The most exciting part was testing various machine learning algorithms to see which would perform best. We evaluated several models including:

* Logistic Regression
* K-Nearest Neighbors
* Decision Trees
* Naive Bayes
* Support Vector Machines
* Gradient Boosting
* Random Forest
* Multi-Layer Perceptron

After careful comparison, we found that an ensemble approach combining LightGBM and Multi-Layer Perceptron delivered the strongest results, with an impressive ROC-AUC score of 0.829.

## **Key Insights: What Makes Customers Leave?**

One of the most valuable outcomes was identifying the factors that most strongly influence customer churn:

* **Total Charges** emerged as the most influential feature, accounting for 37.46% of the model's predictive power
* **Fiber Optic Internet Service** was the second most important factor (12.43%)
* **Two-Year Contracts** showed significant influence as a protective factor (9.89%)

Interestingly, demographic features like gender, partnership status, and age had much less impact on churn predictions than service-related features.

## **The Final Product: An Interactive Prediction Application**

The crown jewel of our project was the interactive application we built using Streamlit. The app has two main components:

1. **Churn Prediction Tool** - Users can input customer details (service type, contract length, payment method, etc.) and instantly receive a churn probability prediction with a detailed breakdown of risk factors.
2. **AI Customer Service Assistant** - We integrated a chatbot that can answer customer queries about services, packages, and trends, drawing on both historical data and AI-generated responses.

You can check out our application here: [https://ai-and-decision-making-73yuejae3nfvcdnbf8ygef.streamlit.app](#)

## **Business Impact: Why This Matters**

This isn't just a cool technical exercise - it has real business value. Telecom companies can use this kind of solution to:

* Proactively identify high-risk customers before they leave
* Launch targeted retention offers to the right customers at the right time
* Optimize customer service resources
* Make data-driven decisions about product development and pricing

By predicting churn with 78.6% accuracy and providing explainable results, our solution empowers decision-makers to take strategic action.

## **Reflections on the Project**

Working on this project was an incredible learning experience. Not only did I get to apply advanced machine learning techniques to a real business problem, but I also gained valuable insights into how AI can transform business operations and customer relationships.

The most challenging part was implementing the AI-assisted chatbot. While we initially wanted to use more powerful models from OpenAI, budget constraints led us to use Hugging Face instead. This taught me an important lesson about balancing technical aspirations with practical constraints.

I'm particularly proud of how our team combined technical rigor with business relevance to create something that's not just academically sound but also practically useful.

Have you worked on any predictive analytics projects or used AI for business problems?