# Diet Recommendation System

This repository contains the implementation of a **Diet Recommendation System** that helps users achieve their dietary goals, such as increasing or decreasing weight, by providing personalized food recommendations based on user inputs like age, height, and goals.

## Features
- **User Input-Based Recommendations**: The system allows users to enter information such as age, height, weight and preferences like Veg/Non-Veg in addition to that it also takes users dietary goals (e.g., Healthy , Weight gain, Weight loss), to receive personalized diet suggestions.
- **New and Refined Dataset**: A custom dataset was created and refined specifically for this project, incorporating detailed nutritional information such as calories, fats, protein, carbohydrates, cholesterol, sodium, fiber, and sugar content.
- **Random Forest for Classification**: A Random Forest classifier is used to predict food items that align with the user's dietary needs.
- **Cosine Similarity for Nutritional Matching**: To enhance the accuracy of the recommendations, the system employs cosine similarity to find food items with similar nutritional profiles based on the user's preferences.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/prakash2670/DietRecommendation_ML_Project.git

