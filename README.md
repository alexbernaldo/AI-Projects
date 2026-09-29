# 🎓 AI Projects

A curated collection of **university machine-learning coursework** in statistical learning,
data mining and deep learning. Every repo is an independent snapshot of a graded practical
(no datasets, trained weights, or reports are committed — each README explains how to get
the data and reproduce the results).

---

## Classical Machine Learning

| Project | Description | Stack |
|---|---|---|
| [ML_Wine_Quality_Classification](https://github.com/alexbernaldo/ML_Wine_Quality_Classification) | Spanish wine **quality** (multi-class) & **type** (red/white) from physicochemical features — Decision Tree, kNN, SVM, Gaussian NB, Random Forest. | scikit-learn, pandas |
| [SLDM_Air_Quality_Benzene_Regression](https://github.com/alexbernaldo/SLDM_Air_Quality_Benzene_Regression) | Regression of **benzene (C6H6)** in Madrid air (UCI Air Quality) — OLS vs. Gradient Descent vs. Random Forest (R² 0.9997). | scikit-learn, statsmodels |

## Unsupervised Learning & Data Mining

| Project | Description | Stack |
|---|---|---|
| [SLDM_Country_Segmentation_SOM_KMeans](https://github.com/alexbernaldo/SLDM_Country_Segmentation_SOM_KMeans) | **Self-Organizing Map + K-Means** segmentation of 195 countries, validated with U-Matrix and a world choropleth. | MiniSOM-style, scikit-learn |
| [Data_Mining_Pokemon_Clustering](https://github.com/alexbernaldo/Data_Mining_Pokemon_Clustering) | Clustering of **734 Pokémon** (KMeans, DBSCAN, hierarchical) — functional profiles beat elemental types. | scikit-learn |

## Deep Learning & Computer Vision

| Project | Description | Stack |
|---|---|---|
| [DL_Computer_Vision_Emotion_Classification](https://github.com/alexbernaldo/DL_Computer_Vision_Emotion_Classification) | **Facial emotion** recognition (59k images, 5 classes): CNN from scratch vs. **MobileNetV2** fine-tuning (0.894 test acc). | TensorFlow / Keras, Keras Tuner |

## Natural Language Processing

| Project | Description | Stack |
|---|---|---|
| [NLP_News_Classification_SkipGram_Embeddings](https://github.com/alexbernaldo/NLP_News_Classification_SkipGram_Embeddings) | **AG News** classification (120k, 4 classes) with Skip-Gram embeddings trained from scratch, frozen into **GRU/BiLSTM/Transformer** (0.884 test acc). | PyTorch, TensorFlow / Keras |

---

## Reproduce

Each project reads a public dataset (linked in its README) and runs end to end in
Google Colab / Jupyter.
