# 🎬 Netflix-Style Recommender System (ML Simulation)

I started this project to understand how **real-time recommendation systems like Netflix** work — how users transition through pages (Home, Search, Playback), and how machine learning can personalize their experience.

This end-to-end ML project simulates user behavior and builds recommendation engines using various techniques including Markov chains, Random Forests, collaborative filtering, and deep learning (autoencoders).

---

## 🔧 Tech Stack

- **Python 3.10**
- **Jupyter Notebook**
- **NumPy**, **Pandas**
- **Matplotlib**, **Seaborn**, **NetworkX**
- **scikit-learn**
- **TensorFlow / Keras**

---

## 📚 Key Concepts Covered

- Session tracking: how users navigate Netflix-style platforms
- Markov Chains: transition modeling across pages
- Random Forest Classifier: predicting next page
- Collaborative Filtering: user-user & item-item similarity
- Deep Learning: autoencoder-based recommendation engine
- Data visualization: page flow as a graph

---

## 🚀 Project Structure

- `Netflix_Recommender_Project.ipynb` → Full notebook with simulations, models & charts
- `Netflix_User_Sessions.csv` → Simulated session data with real movie names
- `README.md` → You are here

---

## 🖼️ Preview (Markov Model Example)

> Replace the link below with your own uploaded GitHub image or screenshot

```md
![User Page Flow](https://github.com/sudeepreddyyy/Netflix-ML/assets/preview-1.png)


# Clone the repo
git clone git@github.com:sudeepreddyyy/Netflix-ML.git
cd Netflix-ML

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook Netflix_Recommender_Project.ipynb
