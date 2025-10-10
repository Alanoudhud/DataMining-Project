# IT326 Project — Lung Cancer Risk Prediction

## Project Information
This project applies data mining techniques to the Lung Cancer Risk dataset from Kaggle.  
The dataset contains demographic, lifestyle, and health-related attributes (such as age, smoking habits, alcohol use, family history, stress, and anxiety).  
Our work focuses on two major tasks:

- *Classification (Prediction):* Building models to predict whether a person is at risk of lung cancer (Yes/No).  
- *Clustering:* Grouping individuals with similar risk profiles to identify hidden patterns, such as clusters of high-risk smokers versus low-risk non-smokers.

## Motivation
Lung cancer is one of the most critical diseases worldwide and a leading cause of cancer-related deaths.  
Early prediction of risk can help in prevention, awareness, and better treatment planning.  
By applying machine learning, we aim to explore which factors (e.g., smoking, alcohol, age) contribute most to risk, and how predictive models can assist in health decision-making.

## Dataset Source
- *Platform:* Kaggle  
- *URL:* [Lung Cancer Risk Dataset](https://www.kaggle.com/datasets/mikeytracegod/lung-cancer-risk-dataset)  
- *Format:* CSV file with more than 500 rows and at least 10 columns, meeting the project requirements.  
- *Target Attribute:* LUNG_CANCER (Yes/No).

## Dataset Description
- Number of rows: 50,000  
- Number of columns: 11  

### Dataset Description

- **Number of rows:** 50,000  
- **Number of columns:** 11  

### Attributes Information:

- **patient_id:** Unique identifier for each patient.  
- **age:** Age of the patient (in years).  
- **gender:** Gender of the patient (Male/Female).  
- **pack_years:** Numerical measure of smoking exposure (ranges approximately from 0 to 100).  
- **radon_exposure:** Exposure level to radon gas (Low / Medium / High).  
- **asbestos_exposure:** Whether the patient was exposed to asbestos (Yes / No).  
- **secondhand_smoke_exposure:** Exposure to secondhand smoke (Yes / No).  
- **copd_diagnosis:** Whether the patient has Chronic Obstructive Pulmonary Disease (Yes / No).  
- **alcohol_consumption:** Alcohol consumption level (None / Moderate / Heavy).  
- **family_history:** Family history of lung cancer (Yes / No).  
- **lung_cancer:** Target variable indicating if the patient has lung cancer (Yes / No).  

### Target Attribute (Class Label):
- *lung_cancer* (Yes/No)  

### Class Distribution:
- Yes = 34,364  
- No = 15,636

## Team Members
- Alanoud Alhudhaif 445200325 
- Maraheb Alrashedi 445200056
- Aleen Aldosari 445200450
- Shatha Alsheddey 445203021

## Phase 1 Deliverables
- Dataset uploaded in Dataset/Raw_dataset.csv  
- Related research paper uploaded in Dataset/ResearchPaper.pdf  
