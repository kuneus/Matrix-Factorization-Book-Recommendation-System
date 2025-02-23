# Matrix-Factorization-Book-Recommendation-System

This notebook is part of the submission for WGU's C964 - Computer Science Capstone. This project implements a book recommendation system using matrix factorization under the collaborative filtering model. Collaborative filtering is the most common model for recommendation systems, which uses data from a similar user to generate recommendations for the user of interest. This filtering method requires a dataset that includes user IDs, book titles, and user ratings.

Matrix factorization is an algorithm used in recommendation systems to reduce large user-item interaction matrices into smaller components that reveal hidden patterns. In this case, the user-item matrix has the users as rows, book titles as columns, and the table values as user ratings.

For this model, we will use a specific type of matrix factorization called singular value decompression (SVD). This technique decomposes the user-item matrix into smaller matrices, capturing the most essential relationships between users and items. By reducing the matrix's dimensionality, SVD can generate highly accurate recommendations.
