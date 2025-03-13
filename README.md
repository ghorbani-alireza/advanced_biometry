# Advanced Biometry – Exercises & Solutions  

This repository contains exercises and solutions for the **Advanced Biometry** course by Prof. Anne-Laure Boulesteix at LMU Munich (IBE). The course is designed for epidemiology students looking to renew or strengthen their statistical background. The exercises aim to help students become familiar with key statistical concepts and apply them to real-world cases.  

## 📌 Topics Covered & Suggested Readings  
- **W1: Statistical Methods for Clinical Trials**  
- **W2: Statistical Methods for Diagnostic Studies**  
  - **Dataset:** *lplaudio_subset.csv* (Simulated audiology test data for neonates)  
  - *Description:* This dataset contains simulated data on hearing tests for neonates, where one of two hearing tests (A or B) was performed. Key variables include the actual hearing loss status (gold standard), test result, severity of hearing loss, testing location (soundproof booth vs. hospital room), and age.  
- **W3: Survival Analysis**  
  - **Dataset:** *ACTG320 (AIDS Clinical Trials Group 320 study)*  
  - *Description:* A randomized, double-blind, placebo-controlled study examining the effectiveness of a three-drug HIV treatment regimen. The outcome of interest is time to AIDS diagnosis or death. The dataset includes treatment type, intravenous drug use history, Karnofsky Performance Scale, age, and CD4 count.  
  - *Suggested Reading:* [Survival Analysis: A Self-Learning Text](https://link.springer.com/book/10.1007/978-1-4419-6646-9) – David G. Kleinbaum & Mitchel Klein  
- **W4: Statistical Learning**  
  - *Suggested Reading:* [An Introduction to Statistical Learning](https://www.statlearning.com/) – Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani  
- **W5: Longitudinal Data Analysis**  
  - **Dataset:** *TLC trial dataset (Lead exposure in US children)*  
  - *Description:* This dataset includes N=100 children aged 12-33 months with high blood lead levels, randomized to either placebo or treatment ("succimer"). Blood lead levels were measured at baseline, week 1, week 4, and week 6. The dataset is useful for analyzing repeated measures and time-dependent effects.
- **W6: Sample Size Calculation for Clinical Trials**  
  - *Description:* This week focuses on sample size calculation and recalculation methods for clinical trials. A presentation file provides an overview of the topic "cluster randomized trials", and five more topics of sample size calculation were summarized through practical examples.  
  - *Suggested Reading:* [Methods and Applications of Sample Size Calculation and Recalculation in Clinical Trials](https://link.springer.com/book/10.1007/978-3-030-49528-2) – Gernot Wassmer & Werner Brannath 

## 📂 Repository Structure  
The repository is organized into **weekly folders (`W1` to `W5`)**, each containing:  

```
📁 W1_Clinical_Trials/
├── exercises.pdf # PDF with exercises
├── solutions.Rmd # R script with solutions
├── solutions.pdf # PDF with detailed solutions

📁 W2_Diagnostic_Studies/
├── exercises.pdf
├── solutions.Rmd
├── solutions.pdf
├── data/
│ ├── lplaudio_subset.csv # Simulated audiology test dataset

📁 W3_Survival_Analysis/
├── exercises.pdf
├── solutions.Rmd
├── solutions.pdf
├── data/
│ ├── actg320.txt # AIDS Clinical Trials Group 320 dataset

📁 W4_Statistical_Learning/
├── exercises.pdf
├── solutions.Rmd
├── solutions.pdf

📁 W5_Longitudinal_Data/
├── exercises.pdf
├── solutions.Rmd
├── solutions.pdf
├── data/
│ ├── tlc_trial.csv # Lead exposure dataset

📁 W6_Sample_Size_Calculation/
├── cluster_randomized.pdf # Presentation on cluster randomized trials
├── summary.pdf # Summary of five key topics in sample size calculation
├── summary.Rmd # R markdown for Summary of five key topics in sample size calculation

```

Each folder contains:  
✅ **Exercises (`.pdf`)** – Problems related to the topic.  
✅ **Solutions (`.Rmd`, `.pdf`)** – Detailed answers and explanations.  
✅ **Datasets (if applicable)** – Used for hands-on analysis.  

## 🛠 Tools & Requirements  
- All exercises are implemented in **R**.  
- Files are provided in `.R`, `.Rmd`, and `.pdf` formats.  
- You will need **R and RStudio** to run the scripts.  

## 🎯 Who Can Benefit?  
- Epidemiology students reviewing statistical methods.  
- Researchers needing practical examples of statistical applications.  
- Anyone looking for structured exercises on clinical trials, survival analysis, and statistical learning.  

## 📜 License  
Feel free to use or modify the materials in this repository. If you find them helpful, consider citing or giving credit!  

---

📬 **Contributions & Feedback**  
If you find errors or have suggestions, feel free to open an issue or submit a pull request!  
