# CS 4375 Machine Learning – Project Guidelines & Checklist

## Instructor: Rishabh Iyer  
**University of Texas at Dallas**  
**Project Due: May 12th 2025**

---

## 📌 General Expectations

- The project accounts for **25% of your final grade**.
- You are expected to invest significant time and effort.
- Submit the following:
  - ✅ **Detailed and Comprehensive Report (5–10 pages, No Upper Limit)**
  - ✅ **Project Slides**
  - ✅ **Detailed and Commented Code**
  - ✅ **Short Video (< 3 mins)** explaining the project
- Your report must describe:
  - What you attempted
  - What worked and what didn’t
  - What you learned
- Please try to make your project **stand out**. The projects that get the highest score are the ones that have taken extra effort in their report, code, slides, and the overall project.

---

## 🔍 Project Type 1: ML Problem & Solution

**Goal:** Pose a real-world problem as an ML task (classification, regression, clustering), train models, and evaluate.

### ✅ Checklist

- [ ] Choose a **high-quality dataset** (from sources like Kaggle, UCI, OpenML, etc.)
- [ ] Perform **Exploratory Data Analysis (EDA)**:
  - Correlations between features and target
  - Feature distributions and label histograms
  - Missing values and imputation strategy
  - Feature variance and standardization
  - Class imbalance analysis
  - Add TSNE or PCA visualization to visualize features and data to understand aspects like separability and so on.
- [ ] If applicable, please perform comprehensive feature engineering and feature selection to identify the best features for your task. Look into different feature transformations (e.g., polynomial, categorical, count based, and so on).
- [ ] Apply and compare **multiple ML models**:
  - Linear models (SVMs/Logistic/Linear Regression)
  - Tree-based models (Decision Trees, Random Forests, XGBoost)
  - Neural Networks (MLPs or CNNs if relevant)
- [ ] Conduct **extensive hyperparameter tuning**:
  - Grid search / Random search / Bayesian optimization
  - Use of validation set or cross-validation
- [ ] Provide **reasoning for hyperparameter choices**
- [ ] Use **appropriate evaluation metrics**:
  - Accuracy, Precision, Recall, F1, AUC, RMSE, etc.
- [ ] Include **visualizations** of results (confusion matrices, ROC curves, etc.)
- [ ] Analyze and explain **what works and what doesn't**
- [ ] Discuss **limitations** and future directions
- [ ] Summarize **lessons learned and key takeaways**

---

## 📚 Project Type 2: Deep Dive into an ML Topic

**Goal:** Explore a specific ML concept deeper than class material.

### ✅ Checklist

- [ ] Select a **focused topic** (e.g., SVMs, Clustering, Regularization, Kernel Methods)
- [ ] Perform a **thorough literature review**
- [ ] Go **beyond class coverage**, e.g.:
  - For SVMs:
    - Support Vector Regression (SVR)
    - Various kernel methods (RBF, polynomial, string kernels)
    - Outlier detection using SVMs
- [ ] Include **mathematical derivations or conceptual illustrations**
- [ ] Implement **case studies or experiments** to support your findings
- [ ] Present **comparisons of variants/approaches**
- [ ] Include **visualizations** to explain concepts
- [ ] Highlight **novel insights or surprises** from your exploration
- [ ] Clearly summarize:
  - What’s new
  - What you learned
  - How it connects to the course

---

## 🛠️ Project Type 3: ML Implementation from Scratch

**Goal:** Implement a **family of algorithms** from scratch, showcasing deep understanding and design.

### ✅ Checklist

- [ ] Choose a **non-trivial ML family**:
  - Decision Trees & Ensembles
  - Linear Models with Regularization
  - Neural Networks (basic or CNNs)
  - Clustering (K-Means, Hierarchical, DBSCAN)
- [ ] Implement:
  - **Multiple variants** within the family
  - **Different objective functions**, heuristics, or loss functions
  - **Key design choices** (e.g., split criteria, regularizers)
- [ ] Add **regression + classification versions**, where applicable
- [ ] (Optional) Build a **mini library or framework**
- [ ] Validate implementation on **multiple datasets**
- [ ] Include **tests and correctness checks** (compare with sklearn, etc.)
- [ ] Use **clear visualizations** (e.g., tree diagrams, decision boundaries)
- [ ] Discuss:
  - Computational cost
  - Strengths and weaknesses
  - Comparisons with existing libraries
- [ ] Document **code extensively**

---

## ❌ What NOT to Do

- ❌ Avoid **complex research topics** outside course scope (e.g., Transformers, GANs)
- ❌ Don’t submit **simple assignments** disguised as a project (e.g., plain linear regression)
- ❌ Avoid **last-minute work** – effort will reflect in your results
- ❌ Don’t rely solely on **ChatGPT or prebuilt code** – be original and hands-on

---

## 📥 Submission Requirements

1. **project_report.pdf**
2. **project_slides.pptx/pdf**
3. **code/** folder (modular and documented)
4. **project_video.mp4** (max 3 mins)

---

## 📬 Questions?

Reach out via email or during office hours for feedback or project guidance.

---

