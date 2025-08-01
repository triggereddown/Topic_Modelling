# 🐜 ACO-LDA: Ant Colony Optimization Meets Topic Modeling

Welcome to the **ACO-LDA project** — where swarm intelligence meets natural language processing! This project integrates **Ant Colony Optimization (ACO)** with **Latent Dirichlet Allocation (LDA)** to optimize topic modeling performance by maximizing coherence scores. 🧠📚

---

## 🚀 Project Overview

Traditional LDA models often rely on fixed hyperparameters. In this project, we use **ACO** to optimize the following:
- Number of topics `k`
- `alpha`: Dirichlet prior for document-topic distribution
- `beta`: Dirichlet prior for topic-word distribution

### ✨ Highlights:
- 🐜 Adaptive hyperparameter tuning using ACO.
- 📊 Visual comparisons between fixed LDA and ACO-optimized LDA.
- 🔍 Analysis of word distribution and feature usage before and after modeling.

---

## 🧪 Methodology

1. **Text Preprocessing**  
   Clean and tokenize the text data.

2. **ACO Optimization Loop**  
   - Randomly initialize LDA parameters.
   - Run LDA with each parameter set.
   - Evaluate using **coherence score**.
   - Keep track of best-performing combinations.

3. **Model Evaluation**  
   - Top keywords
   - Feature richness
   - TF-IDF weight density before and after modeling

---

## 📈 Visual Results
###  Word Weight Density (After LDA)
<img width="790" height="590" alt="Word weight density after LDA" src="https://github.com/user-attachments/assets/6cdf6eb2-ab0c-4727-9975-5ac99adbc6ad" />



