# Book_Recomender_System

<img width="822" height="489" alt="image" src="https://github.com/user-attachments/assets/00bb93ea-507b-454a-8cec-bfcb8fb8e327" />

# 📚 Book Recommender System

A machine learning-based system to recommend books using popularity metrics, collaborative filtering, and clustering analysis.

# 🚀 Project Overview

Built a recommendation engine using a dataset of:

271,360+ books

1.1M+ user ratings

Applied multiple techniques to provide personalized book suggestions.

# 🔧 Technologies Used
Python

Pandas

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

# 🧠 Recommendation Techniques Used
🔹 1. Popularity-Based Recommendation
Recommended top-rated books with high rating counts.

Focused on trending books irrespective of user preferences.

🔹 2. Collaborative Filtering (Item-Based)
Used cosine similarity to measure similarity between books.

Recommended books based on a user’s previous preferences.

🔹 3. K-Means Clustering (Genre/User Segmentation)
Clustered users or books based on:

Average ratings

Genre preferences

Rating behavior patterns

Helped identify similar user groups or content niches.

📊 Data Preprocessing Steps
Merged Books, Ratings, and Users datasets.

Handled missing data and removed duplicates.

Normalized rating distributions for fair comparison.

Filtered books with sufficient rating volume for meaningful analysis.

# 📌 Key Features
📈 Popular books based on total ratings & average score.

🤝 Personalized recommendations using collaborative filtering.

🧩 Unsupervised clustering to explore hidden patterns in reading habits.

📁 Dataset Source
Book-Crossing Dataset (GroupLens)

# 🎯 Future Enhancements
Add NLP-based content filtering using book titles & descriptions.

Include user-based collaborative filtering.

Build a Streamlit UI for user-friendly access.
