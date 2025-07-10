# DL-Assignments

Notebooks from the *Human-Centered Deep Learning* course at **TU Dublin** (2024)

This repository contains selected assignments and projects developed during a 13-week module on Deep Learning, with a focus on human-centered AI applications.

## 🧠 Topics Covered

* Feedforward Neural Networks & Backpropagation
* Hyperparameter Tuning, Loss Functions, and Regularization
* Convolutional Neural Networks (CNNs) for Image Classification
* Word Embeddings and 1D CNNs for NLP
* Recurrent Neural Networks (RNNs) and LSTMs for Time Series
* Explainability and Transparency in Deep Learning (XAI)
* Deployment on Cloud & GPU (Azure, Docker)
* AI Ethics, Bias, and Responsible AI Design

---

## 🧪 Tools & Frameworks

* Python, Jupyter Notebooks, Google Colab
* TensorFlow
* Docker, Azure
* Matplotlib, Seaborn, Scikit-learn
* LIME, Surrogate Models

---

## 📁 Notebooks

### `binary_classification_diabetes.ipynb`

Binary classification on a non-normalized health dataset to predict diabetes.
*Dataset not included (provided by lecturer). Features include:*
`HighBP	HighChol	CholCheck	BMI	Smoker	Stroke	HeartDiseaseorAttack	PhysActivity	Fruits	Veggies	HvyAlcoholConsump	AnyHealthcare	NoDocbcCost	GenHlth	MentHlth	PhysHlth	DiffWalk	Sex	Age	Education	Income	Diabetes_binary`

---

### `CNN_classification_images.ipynb`

Image classification using CNNs on the [UTKFace dataset](https://susanqq.github.io/UTKFace/).
Focus: age prediction via classification across 10-year intervals.

---

### `DT-NN_classification_SalaryDataScience.ipynb`

Tabular data classification on data science salaries, involving preprocessing, deep neural network comparison, and interpretability analysis.
**Final project**, done in collaboration with **Michalis Thomas**.
*Dataset not included. Feature examples:*
`work_year	experience_level	employment_type	job_title	salary	salary_currency	salary_in_usd	employee_residence	remote_ratio	company_location	company_size.`

See `DT-NN_report.pdf` for project objectives, methodology, and conclusions.

---

## ⚙️ Requirements

To run the notebooks, use:

```bash
!pip install --upgrade tensorflow==2.12.0
!pip install --upgrade tf_keras_vis==0.8.5
```

---



