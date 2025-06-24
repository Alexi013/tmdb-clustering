# tmdb-clustering
This project uses **unsupervised learning** to cluster movies based on metadata retrieved from the [TMDB (The Movie Database) API](https://www.themoviedb.org/documentation/api).

We applied **K-Means clustering** on features like genres, popularity, and vote averages to uncover natural groupings among 1000 recent movies. The project includes:

- Data collection using the TMDB API with Bearer Token authorization
- Exploratory Data Analysis (EDA) on genre distributions, popularity, and ratings
- Dimensionality reduction using PCA for visualization
- Clustering with K-Means and interpretation of thematic clusters
- Sample movie examples per cluster to support conclusions

---

### Technologies Used
- Python (Pandas, Scikit-learn, Seaborn, Matplotlib)
- TMDB API
- Jupyter Notebook

---

### Note on API Access

You must provide your own TMDB Bearer Token to run this notebook. You can request one by creating an account at [TMDB Developers](https://developer.themoviedb.org/).
