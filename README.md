# **Credit Risk Modelling | Calculation of PD, LGD, EAD, and EL with Machine Learning in Python**

## **Table of Contents**
- [Background](#background)
- [Project](#project)
- [Key Documents](#key-documents)
- [Datasets](#datasets)
- [Model Performances](#model-performances)
- [Deliverables](#deliverables)
- [Getting Started](#getting-started)
- [Technologies](#technologies)
- [Top-Directory Layout](#top-directory-layout)
- [License](#license)
- [Author](#author)

---

## **Background**
Credit risk modeling is crucial for financial institutions. It represents the risk of a borrower not being able to pay back loans or credit card balances. Borrowers may only partially repay amounts, impacting both principal and interest. Machine learning and statistical modeling are essential for managing big data and conducting robust analyses.

---

## **Project**
This AI-powered project models credit risk in compliance with Basel accords.  

**Objectives:**  
- Build a credit risk model using loan data.  
- Provide a scorecard for daily evaluation and calculate exposure loss.

### **Steps:**
1. Preprocessing — Convert columns into dummy variables using fine and coarse classing  
2. Develop PD Model using Logistic Regression  
3. Deliver scorecard in CSV format based on PD model  
4. Construct LGD model with Beta Regression  
5. Build EAD model with Linear Regression  
6. Calculate Exposure Loss (EL) after obtaining all models  
7. Validate models using the Population Stability Index  

---

## **Key Documents**
- **L01:** Preprocessing and Feature Engineering  
- **L02:** PD Modeling and Scorecard Delivery  
- **L03:** LGD, EAD, and Expected Loss Modeling  
- **L04:** PSI Population Stability Check  

---

## **Datasets**  
Dataset sourced from Lending Club, a large US-based peer-to-peer lending platform, containing over 800,000 loans issued between 2007 and 2015.

---

## **Model Performances**

| Model | Algorithm | Metric | Performance |
|-------|-----------|--------|-------------|
| PD    | Logistic Regression | AUC | 0.684 |
| LGD (Stage 1) | Logistic Regression | AUC | 0.640 |
| LGD (Stage 2) | Linear Regression | Accuracy | 0.777 |
| EAD | Linear Regression | Accuracy | 0.658 |

---

## **Deliverables**
1. Easy-to-interpret scorecard  
2. Impact analysis of cutoff rates  
3. EL model integrating LGD and EAD predictions  
4. Stability checks using PSI  

---

## **Technologies**
- **Python:** 3.8  
- **Jupyter Notebook:** 6.4.12  
- **Version Control:** GitHub  
- **Visualization & Modeling:** Logistic Regression, Linear Regression  

---

## **Getting Started**
### Clone Repo:
```bash
git clone https://github.com/sasivirat/Credit_RiskModelling.git
