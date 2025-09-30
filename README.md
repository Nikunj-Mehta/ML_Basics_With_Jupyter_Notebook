# 🎯 ML Basics with Jupyter Notebook

Welcome! This repository is a hands-on guide to **Machine Learning fundamentals** using Jupyter Notebook.  
It covers data exploration, model building, and visualization, with a focus on a **Music Recommendation System**.

---

## 📂 Project Overview

- **Notebooks:** Step-by-step Jupyter Notebooks for each concept and project
- **Dataset:** Sample CSV file (`music.csv`) for training and testing
- **Model:** Decision Tree Classifier to predict music preferences
- **Visualization:** Decision tree exported as a Graphviz `.dot` file for visual inspection

---

## ⚙️ Tech Stack

- Python 🐍
- Jupyter Notebook 📓
- pandas
- scikit-learn
- Graphviz (for tree visualization)

---

## 🚀 Getting Started

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Nikunj-Mehta/ML_Basics_With_Jupyter_Notebook.git
   cd ML_Basics_With_Jupyter_Notebook
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   Or manually install:
   ```bash
   pip install pandas scikit-learn jupyter graphviz
   ```

3. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Open the notebook in your browser and follow the steps.

---

## 📊 Features

- **Data Loading & Exploration:** Using pandas to load and analyze CSV data
- **Model Training:** Building and evaluating ML models with scikit-learn
- **Music Recommendation:** Predicting music genres based on user features
- **Decision Tree Visualization:** Exporting and visualizing the tree using Graphviz

---

## 🖼️ Visualizing the Decision Tree

- The trained decision tree is exported to `music-recommender.dot`.
- To visualize:
  - **VS Code:** Install a Graphviz extension (e.g., "Graphviz Interactive Preview") and open the `.dot` file.
  - **Command Line:** Generate an image:
    ```bash
    dot -Tpng MusicRecommendation/music-recommender.dot -o music-recommender.png
    ```
    Open `music-recommender.png` to view the tree.

---

## 📁 File Structure

```
ML_Basics_With_Jupyter_Notebook/
├── MusicRecommendation/
│   ├── music.csv
│   ├── music-recommender.dot
│   └── Music_Recommendation.ipynb
├── requirements.txt
└── README.md
```

---

## 📝 Notebooks Included

- **Music_Recommendation.ipynb:** End-to-end workflow for building and visualizing a music recommender

---

## 🤝 Contributing

Pull requests and suggestions are welcome!  
Feel free to fork and enhance the project.

---

## 📧 Contact

For questions or feedback, open an issue or reach out via GitHub or LinkedIn.

**Nikunj Mehta**  
[GitHub](https://github.com/Nikunj-Mehta)  
[LinkedIn](https://www.linkedin.com/in/nikunj-mehta-016a2a2b0/)

---