# Matrix-Factorization-Book-Recommendation-System

## Introduction ##
This notebook is part of the submission for WGU's C964 - Computer Science Capstone. This project implements a book recommendation system using matrix factorization under the collaborative filtering model. Collaborative filtering is the most common model for recommendation systems, which uses data from a similar user to generate recommendations for the user of interest. This filtering method requires a dataset that includes user IDs, book titles, and user ratings.

Matrix factorization is an algorithm used in recommendation systems to reduce large user-item interaction matrices into smaller components that reveal hidden patterns. In this case, the user-item matrix has the users as rows, book titles as columns, and the table values as user ratings.

For this model, I used a specific type of matrix factorization called singular value decompression (SVD). This technique decomposes the user-item matrix into smaller matrices, capturing the most essential relationships between users and items. By reducing the matrix's dimensionality, SVD can generate highly accurate recommendations.

# User Guide
This recommendation system is a Python-based application running in Google Colab, a cloud-based Jupyter Notebook environment. This means no local installation is required to start executing the application. Follow the steps below to run the application and begin generating book recommendations.

1.	Open your preferred internet browser.
2.	Click the following link to open the notebook or paste it into your browser:  https://colab.research.google.com/drive/1w_u59ZLrNhSKKFYgIc7NlyHs2MGXXpPj?usp=sharing 
3.	If you are not already signed in to your Google account, sign in at the top right.
4.	At the top menu bar, click the dropdown option ‘Runtime,’ then click ‘Run all.’ 
<img width="500" alt="image" src="https://github.com/user-attachments/assets/a3243fb4-6080-4c48-be2e-b256ba00f5b8" />

6.	A warning message will appear indicating that Google did not author this notebook. Click ‘Run anyway’. 
<img width="500" alt="image" src="https://github.com/user-attachments/assets/c4262c58-8c6d-486c-a5e7-ea92b662de2e" />

8.	This may take a few minutes; wait until all cells have run. 
9.	After all the cells have run, the user interface will be loaded at the bottom of the page. Go to the bottom.
10.	Enter an integer from 1 to 400,000 (without commas) in the input field. This will search a user by ID number.
11.	Once a valid ID has been entered, enter another integer for the desired number of recommendations. Try inputting 10 to get a top 10 book recommendation.
12.	Once the book recommendations have been returned, it will return to the initial input screen for user ID—input ‘q’ to exit the program.  

![](https://github.com/kuneus/gif-repo/blob/main/c964-book-recommendation-system/c964-project-demo.gif)
