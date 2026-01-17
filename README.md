# CLIP (ViT-B/32) Based Fashion Outfit Recommendation System

A transformer-powered visual similarity search system that recommends fashion outfits based on semantic image embeddings extracted using OpenAI CLIP with a Vision Transformer (ViT-B/32) backbone.

This project was developed as part of a hackathon to explore deep learning-based fashion recommendation and vector similarity search.

---

## 🚀 Features
- Vision Transformer-based image embeddings using CLIP (ViT-B/32)
- CSV-indexed fashion dataset pipeline
- Image-to-image similarity search using cosine similarity
- Unsupervised style clustering using KMeans
- End-to-end Jupyter Notebook workflow

---

## 🧠 Tech Stack
- Python
- PyTorch
- OpenAI CLIP
- Scikit-learn
- Pandas, NumPy
- OpenCV, Pillow
- Jupyter Notebook

---

## 📂 Project Structure
clip-vit-fashion-recommender/
│
├── notebook/
│   └── train.ipynb          
│
├── data/
│   └── README.md           
│
├── images/                
│
├── images.csv           
├── images_compressed.zip 
│
├── README.md             
├── requirements.txt     
└── .gitignore           

---

## ⚙️ Setup
```bash
git clone https://github.com/YOUR_USERNAME/clip-vit-fashion-recommender.git
cd clip-vit-fashion-recommender
pip install -r requirements.txt

---

##📊Dataset
This project is based on the Kaggle dataset:  
**Fashion Product Images Dataset (clothing-dataset-full)**

Due to licensing and file size, the dataset is not included in this repository.

### Required files (place in root directory):
- images.csv
- images_compressed.zip

Setup instructions are provided in:
data/README.md

---

## ▶️ Usage
Run the notebook:
jupyter notebook notebook/train.ipynb

Follow the cells to extract image embeddings and generate outfit recommendations.

---

## 🔮 Future Scope
- Text-based search using CLIP text encoder
- FAISS-powered fast vector retrieval
- Streamlit web demo for real-time recommendations
- Personalized fashion filtering using metadata
