# Data Science and Machine Learning Portfolio

This repository contains selected study and pet projects in classical machine learning, neural networks, NLP, clustering, and dimensionality reduction. The notebooks are organized as portfolio cases: each project starts with a short summary of the problem, data, approach, result, and stack.

## Recommended Reading Order

1. [NLP Pipeline for Course Description Generation and Evaluation](nlp-course-description-generation.ipynb)
2. [Neural Networks and CNNs with PyTorch](pytorch-neural-networks-cnn.ipynb)
3. [Churn Prediction with Decision Trees and Random Forest](churn-decision-trees-random-forest.ipynb)
4. [Neural Network Components from Scratch](neural-network-from-scratch.ipynb)
5. [Customer Segmentation with K-Means and DBSCAN](customer-clustering-kmeans-dbscan.ipynb)
6. [Dimensionality Reduction and Factor Analysis](factor-analysis-dimensionality-reduction.ipynb)

## Projects

| Project | Focus | Stack | Why it matters |
| --- | --- | --- | --- |
| [NLP Course Description Generation](nlp-course-description-generation.ipynb) | Text preprocessing, embeddings, LLM generation, evaluation | pandas, NLTK, pymystem3, Word2Vec, SentenceTransformers, Hugging Face API, seaborn, plotly | Strongest end-to-end project: combines NLP, prompting, quantitative evaluation, and visual analysis. |
| [PyTorch Neural Networks and CNNs](pytorch-neural-networks-cnn.ipynb) | Deep learning workflow in PyTorch | PyTorch, torchvision, Dataset/DataLoader, NumPy, pandas, sklearn | Shows practical model training beyond `sklearn`: tensors, training loops, optimizers, and CNNs. |
| [Churn Prediction with Decision Trees and Random Forest](churn-decision-trees-random-forest.ipynb) | Applied classification and interpretability | pandas, sklearn, SHAP, seaborn, matplotlib | A business-oriented ML case with model comparison and feature importance analysis. |
| [Neural Network Components from Scratch](neural-network-from-scratch.ipynb) | Core mechanics of neural networks | NumPy, sklearn, PyTorch, matplotlib | Demonstrates understanding of activation functions, loss functions, forward pass, and nonlinear models. |
| [Customer Segmentation with K-Means and DBSCAN](customer-clustering-kmeans-dbscan.ipynb) | Unsupervised learning | sklearn, pandas, NumPy, matplotlib | Compares centroid-based and density-based clustering on synthetic and customer data. |
| [Dimensionality Reduction and Factor Analysis](factor-analysis-dimensionality-reduction.ipynb) | Exploratory analysis of high-dimensional data | PCA, t-SNE, StandardScaler, seaborn | Shows basic techniques for finding structure and visualizing multidimensional data. |

## How to Run

Install dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Then open the notebooks in Jupyter:

```bash
jupyter notebook
```

Some notebooks download public datasets or call external APIs. API tokens and large datasets are intentionally not stored in the repository.
