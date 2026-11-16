# 🧑‍💻 Face Age Estimation | Computer Vision

### 🧠 Deep Learning | Computer Vision | Exploratory Data Analysis

A Computer Vision project focused on exploring facial image data and understanding how age distribution and dataset characteristics can influence the development of age estimation models.

---

## 📌 Project Overview

This project uses a facial image dataset from the **ChaLearn Looking at People** collection.

The objective is to perform an exploratory data analysis (EDA) to understand the dataset before developing a deep learning model capable of estimating a person's age from facial images.

Understanding the characteristics of the dataset is an essential step in building reliable Computer Vision models.

---

## 🎯 Project Objectives

The main challenge is to investigate the facial image dataset and identify characteristics that may affect model training.

The exploratory analysis must:

- 📊 Determine the size of the dataset.
- 📈 Explore the age distribution of the individuals.
- 🖼️ Display 10–15 facial images representing different ages.
- 🔍 Identify relevant patterns and characteristics in the data.
- 🧠 Discuss how these findings may influence the training of an age estimation model.

---

## 📊 Dataset

The project uses facial images and corresponding age labels from the **ChaLearn Looking at People** dataset.

### 📂 Dataset Structure

| File / Directory | Description |
|---|---|
| `labels.csv` | Contains image filenames and their corresponding ages |
| `final_files/` | Directory containing the facial images |
| `file_name` | Image filename |
| `real_age` | Actual age associated with each image |

### 📥 Download Dataset

The dataset is hosted externally because of its size.

**[📥 Download Face Age Dataset — Google Drive](https://drive.google.com/file/d/1mWy7x5o9-jTZbZC9Cy0RvEGN2cgxD7xC/view?usp=drive_link)**

The archive contains the files required for the exploratory analysis.

**Original source:** [ChaLearn Looking at People](http://chalearnlap.cvc.uab.es/dataset/26/description/)

---

## 🔍 Exploratory Data Analysis

The project focuses on three main areas of investigation.

### 1. 📏 Dataset Size

Examine the number of available images and labeled observations to understand the scale of the dataset.

### 2. 📈 Age Distribution

Analyze the distribution of ages to identify:

- Frequently represented age groups.
- Underrepresented age ranges.
- Potential age imbalance.
- Patterns that may influence model generalization.

### 3. 🖼️ Facial Image Visualization

Display a sample of 10–15 facial images across different ages.

This visual inspection helps assess the diversity and characteristics of the image dataset.

---

## ⚙️ Data Processing Approach

Because the dataset contains a large number of images, loading all images into memory simultaneously may be inefficient.

The project considers the use of **Keras image data generators** to load images progressively during model development.

This approach can help:

- Reduce memory consumption.
- Process images in batches.
- Support scalable image preprocessing.
- Prepare data for convolutional neural network training.

---

## 🧠 Machine Learning Context

Age estimation from facial images is a Computer Vision regression problem.

A potential modeling approach involves convolutional neural networks (CNNs), which can learn visual representations from facial images.

The exploratory analysis provides important information for decisions about data preprocessing, model training and evaluation.

**Project scope:** This challenge focuses on exploratory analysis and its implications for model training. No predictive performance results are claimed at this stage.

---

## 💡 Expected Insights

The exploratory analysis aims to provide insights into:

- 📊 Dataset composition and age representation.
- ⚖️ Potential imbalance across age groups.
- 🖼️ Visual diversity among facial images.
- 🔄 Data preparation requirements.
- 🎯 Potential challenges for model generalization.

These findings can guide future age estimation experiments.

---

## 🛠️ Technologies & Tools

**Programming and Data Analysis**

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib

**Computer Vision and Deep Learning**

- 🖼️ Image preprocessing
- 🧠 Keras image data generators
- 🔬 Convolutional Neural Networks (CNNs) — modeling context

**Development Environment**

- Google Colab
- Jupyter Notebook
- GitHub

---

## 📁 Repository Structure

```text
face-age-estimation/
│
├── 📄 README.md
│
├── 📂 data/
│   └── README.md
│
└── 📂 notebook/
    ├── README.md
    └── face_age_estimation.ipynb
```

The facial image dataset is stored externally on Google Drive rather than directly in this repository.

---

## ▶️ How to Run

1. Download the dataset using the Google Drive link above.
2. Extract the `faces.zip` archive.
3. Make sure `labels.csv` and `final_files/` are available.
4. Open the project notebook in Jupyter Notebook or Google Colab.
5. Configure the dataset paths according to your environment.
6. Run the exploratory analysis.

---

## ⚠️ Challenges & Considerations

Several dataset characteristics may affect future model training:

- **Age imbalance:** Uneven representation of age groups may influence prediction quality.
- **Image variability:** Differences in facial appearance and image characteristics may affect learning.
- **Memory requirements:** Large image collections require efficient data loading.
- **Generalization:** The model should perform reliably across different ages.

These are considerations to investigate rather than confirmed findings from the dataset.

---

## 📚 Data Source

ChaLearn Looking at People — Facial Age Estimation Dataset.

Dataset documentation: http://chalearnlap.cvc.uab.es/dataset/26/description/

---

## 👨‍💻 Author

**Brunno Almeida**

Data Science | Data Analytics | Python | SQL | Machine Learning

*Building practical, data-driven solutions through analytics and machine learning.*
