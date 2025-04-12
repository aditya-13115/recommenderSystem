#  Recommendation Systems

This repository contains four different approaches to building a  recommendation system using Python and Jupyter Notebooks. Each notebook explores a unique algorithm or strategy for suggesting movies and books to users.

---

## 📁 Contents

| Notebook | Description |
|----------|-------------|
| `pearsonCorrelation.ipynb` | User-based collaborative filtering using **Pearson Correlation** to find users with similar tastes. |
| `contentBased.ipynb` | A **Content-Based Filtering** model that recommends movies similar to the ones a user has liked, based on features like genre or keywords. |
| `KNNrecommender.ipynb` | An **Item-based Collaborative Filtering** approach using **K-Nearest Neighbors** to suggest similar movies. |
| `WeightedAvg.ipynb` | A **Weighted Average** scoring system to rank movies by balancing rating averages and vote counts (like IMDB's scoring system). |

---

## 📦 Requirements

Install dependencies using pip:

```bash
pip install numpy pandas scikit-learn scipy
```

You also need **Jupyter Notebook** or **Jupyter Lab** to run the `.ipynb` files:

```bash
pip install notebook
```

---

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/recommender-systems.git
cd recommender-systems
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open any of the notebooks and run the cells to see the model in action.

---

## 📊 Dataset

These notebooks assume usage of movie rating datasets like **MovieLens** or similar.  
Make sure to place the dataset in the correct path or modify the paths in the code if needed.

---

## 🤝 Contributions

Feel free to fork this repository and submit pull requests to improve or add new models!

---

## 🤛️ Author

<p> Made with ❤️ by aditya.<br>
Took help from Krish Naik Sir's videos.</p>