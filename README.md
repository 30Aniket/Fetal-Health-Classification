# Fetal-Health-Classification
Reduction of child mortality is reflected in several of the United Nations' Sustainable Development Goals and is a key indicator of human progress.
The UN expects that by 2030, countries end preventable deaths of newborns and children under 5 years of age, with all countries aiming to reduce under‑5 mortality to at least as low as 25 per 1,000 live births.  

Parallel to notion of child mortality is of course maternal mortality, which accounts for 295 000 deaths during and following pregnancy and childbirth (as of 2017). The vast majority of these deaths (94%) occurred in low-resource settings, and most could have been prevented.  

In light of what was mentioned above, Cardiotocograms (CTGs) are a simple and cost accessible option to assess fetal health, allowing healthcare professionals to take action in order to prevent child and maternal mortality. The equipment itself works by sending ultrasound pulses and reading its response, thus shedding light on fetal heart rate (FHR), fetal movements, uterine contractions and more.  

Aim of this project was to classify the health of a fetus as Normal, Suspect or Pathological using Cardiotocogram (CTG) data in order to prevent child and maternal mortality. 4 ML algorithms used in the project were:  
- *Random Forest*  
- *Decsion Trees*
- *Logistic Regression*
- *K-Nearest Neighbours (KNN)*  

This dataset contains 2126 records of features extracted from Cardiotocogram exams, which were then classified by three expert obstetricians into 3 classes:
- *Normal* ***(1)***
- *Suspect* ***(2)***
- *Pathological* ***(3)***

The dataset shape: **(2126, 22)**

This repository contains the following files:
1. **Code**
   - Fetal Health Classification.ipynb
2. **Dataset**
   - fetal_health.csv  
3. **README**  

 Here's the link to the dataset:  
 https://www.kaggle.com/andrewmvd/fetal-health-classification
