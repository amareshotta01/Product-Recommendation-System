The file for the Datasets used : https://drive.google.com/drive/folders/117B6-tl1l_7S2pzhxaeBlYKMBg48tb21?usp=sharing


                                              Product Recommendation System for E-Commerce Businesses
Overview: 

  A well-developed recommendation system can significantly enhance the shopper's experience on an e-commerce website, leading to improved customer acquisition and    retention. This project implements a comprehensive Product Recommendation System that helps businesses recommend products to their customers based on various       contexts.

  The system is designed to cater to different stages of the customer journey, from the first visit to repeat purchases. The recommendation system is divided into    three main parts, each addressing a specific business scenario:

  Part I: Popularity-Based Recommendation System targeted at new customers.
  
  Part II: Model-Based Collaborative Filtering System for customers with purchase history.
  
  Part III: Content-Based Recommendation System for businesses setting up their e-commerce platform without any user-item interaction history.


Project Structure


Recommendation System - Part I: Popularity-Based Recommendations

  Purpose: Recommend the most popular products to new customers who do not have any purchase history.
  Approach: Uses the number of ratings to identify and recommend the most popular products on the website.
  Dataset: "ratings_Beauty.csv"
  
Recommendation System - Part II: Model-Based Collaborative Filtering

  Purpose: Recommend products to users based on their purchase history and the ratings provided by other users who bought similar items.
  Approach: Utilizes collaborative filtering techniques by building a utility matrix from user-item interactions, applying matrix factorization, and generating                 recommendations based on product correlations.
  Dataset: Same as Part I.
  
Recommendation System - Part III: Content-Based Recommendations

  Purpose: Recommend products based on textual descriptions, suitable for businesses with no prior purchase history or ratings data.
  Approach: Uses text clustering and natural language processing (NLP) techniques to recommend similar products based on the description provided.
  Dataset: "product_descriptions.csv"

Setup and Usage
  Prerequisites
    Python 3.x
    Required Python libraries: NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow (if using deep learning models)
    Jupyter Notebook (for running and modifying the .ipynb files)
    Streamlit (optional, if you want to build a web interface)
  
  Installation
    Clone the repository: git clone https://github.com/amareshotta01/Product-Recommendation-System.git
                        cd Product-Recommendation-System
                      
  Install the required dependencies: pip install -r requirements.txt

Running the System

Part I: Popularity-Based Recommendations
To generate the most popular products:

  Open the Jupyter Notebook or run the corresponding Python script.
  Load the dataset and execute the cells to generate and visualize the most popular products.
  
Part II: Collaborative Filtering
To recommend products using collaborative filtering:

  Open the Jupyter Notebook or run the corresponding Python script.
  Ensure that the dataset is loaded correctly.
  Execute the cells to generate recommendations based on a specific product ID.
  
Part III: Content-Based Recommendations
To recommend products based on textual descriptions:

  Open the Jupyter Notebook or run the corresponding Python script.
  Load the product descriptions dataset.
  Execute the cells to generate clusters and recommend products based on user input.
