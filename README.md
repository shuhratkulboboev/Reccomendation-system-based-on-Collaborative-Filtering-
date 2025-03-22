# Reccomendation-system-based-on-Collaborative-Filtering-
A recommendation system that suggests movies based on user ratings using Singular Value Decomposition (SVD) and Cosine Similarity.


# 🎬 Movie Recommendation System  

A recommendation system that suggests movies based on user ratings using **Singular Value Decomposition (SVD)** and **Cosine Similarity**.  

## 📌 Features  
✅ Preprocesses the **MovieLens dataset**  
✅ Constructs a **User-Item Interaction Matrix**  
✅ Learns **latent factors** using **Truncated SVD**  
✅ Uses **t-SNE** to visualize movies in 2D  
✅ Computes **Cosine Similarity** for recommendations  
✅ Implements **K-Means Clustering** for genre analysis  
✅ **Finds similar movies** using **Nearest Neighbors (k-NN)**  

---

## 📂 Dataset  
The dataset used is **MovieLens (ml-1m)**, containing:  
- `ratings.dat` → User ratings (`UserID`, `MovieID`, `Rating`, `Timestamp`)  
- `movies.dat` → Movie metadata (`MovieID`, `Title`, `Genres`)  

---

## 🛠 Installation  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/movie-recommendation.git
cd movie-recommendation
