# Restaurant-Recommendation-System
 (Cognifyz ML Internship)
 
1)Task Objective
The goal of this task is to build a Restaurant Recommendation System that suggests restaurants to users based on their preferences. This helps users discover restaurants that match their taste, cuisine, and location preferences.

2)Types of Recommendation Used
Content-Based Filtering using Cuisines and Location

(Optional future upgrade: Collaborative Filtering)

3)Technologies Used
Python
Pandas
Scikit-learn
TF-IDF Vectorizer
Cosine Similarity
Jupyter Notebook / Google Colab

4)Project Structure
Copy
Edit
├── recommendation_dataset.csv
├── task2_recommendation_system.ipynb
├── README.md

5)Steps Performed

1)Import Dataset
Load the dataset containing restaurant info (e.g., Name, Cuisines, City, Rating).

2)Data Cleaning
Remove missing values, duplicates, and standardize text.

3)Feature Engineering
Combine features like Cuisines and City into a single text column for comparison.

4)Text Vectorization
Use TfidfVectorizer to convert text features into numerical vectors.

5)Similarity Calculation
Use cosine_similarity to measure how similar each restaurant is to others.

6)User Input
Take user preferences (e.g., "Italian" + "Chennai") and find similar restaurants.

7)Return Top Recommendations
Display the top N restaurants most similar to the input.

8)Example Output
User Input: Italian Restaurant in Chennai

Top 3 Recommended Restaurants:
1. Pasta Point – Rating: 4.5 – Price: ₹600
2. Olive Italiano – Rating: 4.3 – Price: ₹700
3. Roma Dine – Rating: 4.1 – Price: ₹550
   
6)Outcome:
*Created a working recommendation system using real-world restaurant data.
*Learned how to process text data using TF-IDF and calculate similarity using Cosine Similarity.
*Improved skills in natural language processing and feature engineering.

7)Output:
<img width="1360" height="768" alt="Image" src="https://github.com/user-attachments/assets/bd64f0ac-b511-44e7-9c2e-2c934e3750fb" />

<img width="1360" height="768" alt="Image" src="https://github.com/user-attachments/assets/e828b391-59e7-4d68-bae6-ae5b5ddf2201" />

