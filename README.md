# Machine Learning Internship — Elite Tech Intern

This repository contains my completed tasks for the **Machine Learning Internship** program at
Elite Tech Intern. Each task is in its own folder with a self-contained, executed Jupyter Notebook.

## 📁 Repository Structure

```
ML_Internship_Tasks/
├── Task1_Decision_Tree/
│   └── decision_tree_classification.ipynb
├── Task2_Sentiment_Analysis/
│   └── sentiment_analysis_nlp.ipynb
├── Task3_Image_Classification/
│   └── image_classification_cnn.ipynb
├── Task4_Recommendation_System/
│   └── recommendation_system.ipynb
├── requirements.txt
└── README.md
```

## 📝 Task Summaries

| Task | Description | Technique |
|------|-------------|-----------|
| **1. Decision Tree Implementation** | Classify Iris flower species and visualize the trained tree | Scikit-learn `DecisionTreeClassifier` |
| **2. Sentiment Analysis with NLP** | Classify customer reviews as positive/negative | TF-IDF Vectorization + Logistic Regression |
| **3. Image Classification Model** | Classify handwritten digit images | Convolutional Neural Network (TensorFlow/Keras) |
| **4. Recommendation System** | Recommend items to users from a ratings matrix | Matrix Factorization (Collaborative Filtering) |

Every notebook includes: data loading/exploration, preprocessing, model training, visualization,
evaluation metrics, and a conclusion with possible improvements — and every code cell is commented
for readability, per the internship's task instructions.

## ⚙️ Setup & Usage

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd ML_Internship_Tasks
   ```
2. (Recommended) create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter and open any task notebook:
   ```bash
   jupyter notebook
   ```

## 📌 Notes

- All datasets used are either built into scikit-learn (Iris, Digits) or generated synthetically
  in-notebook (reviews, ratings), so **every notebook runs end-to-end with no external downloads**.
- To use real-world datasets instead (e.g. Amazon reviews, MNIST/CIFAR-10, MovieLens), swap the
  data-loading cell in the relevant notebook — the rest of the pipeline works unchanged.
- Each notebook has already been executed, so you can view all outputs, plots, and metrics directly
  on GitHub without re-running anything.

## 🎓 About

Completed as part of the **Elite Tech Intern — Machine Learning Internship Program**
("Learn · Innovate · Thrive").
