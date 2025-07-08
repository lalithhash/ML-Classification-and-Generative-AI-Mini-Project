# Mini Report: AI/ML Intern Assessment

**Name:** *Lalith Kumar G B*  
**Graduation Year:** *2026*  
**Major:** *Information Science and Engineering*  
**Date:** *July 08, 2025*

---

## Part 1: ML Classification on the Iris Dataset

### 📌 Objective
To train a machine learning classifier on the Iris dataset and evaluate its performance using accuracy metrics.

### 📊 Approach
- Loaded the Iris dataset using `scikit-learn`
- Preprocessed data using `StandardScaler`
- Split the dataset into training and testing sets (80/20 split)
- Trained and evaluated multiple classifiers:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine
- Compared test accuracies of each model

### ✅ Results
The best test accuracy achieved was approximately **80%** using the **Support Vector Classifier**. The model performs well in classifying all 3 Iris flower types.

---

## Part 2: Introduction to Generative AI using GPT-2

### 📌 Objective
To use a pre-trained GPT-2 model for text generation tasks and observe its generative behavior.

### ⚙️ Tools Used
- `transformers` and `torch` libraries from Hugging Face
- Pre-trained `gpt2` model

### 📊 Approach
- Tokenized the input prompt: `"Artificial Intelligence is transforming the world..."`
- Generated text continuation using GPT-2
- Controlled output using generation parameters like `max_length`, `temperature`, etc.

### ✨ Sample Output
> *"Artificial Intelligence is transforming the world by making it more and more productive..."*

The model demonstrated a strong ability to generate contextually relevant and grammatically sound sentences.

---

## 📈 Key Learnings
- Understood how to train and compare classification models
- Learned about model evaluation and accuracy checking
- Gained exposure to transformer models and language generation
- Worked with `Hugging Face` ecosystem and explored `transformers` pipeline

---

## 📌 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/iris-ml-gpt2-assessment.git
   cd iris-ml-gpt2-assessment
   ```

2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```

3. Run notebooks:
   - `01_iris_classification.ipynb`
   - `02_gpt2_text_generation.ipynb`

---

## 📂 Files in the Repository

- `01_iris_classification.ipynb`: ML Classification on Iris dataset
- `02_gpt2_text_generation.ipynb`: Generative AI using GPT-2
- `requirements.txt`: Required packages
- `README.md`: Project overview
- `mini_report.md`: This report

---

## 🙏 Thank You

This project gave me valuable hands-on experience with real-world AI/ML tools and workflows.

