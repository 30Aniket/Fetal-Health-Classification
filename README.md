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

The dataset columns:  

**FEATURES:-**
- *baseline value* - FHR baseline (beats per minute)
- *accelerations* - Number of accelerations per second
- *fetal_movement* - Number of fetal movements per second
- *uterine_contractions* - Number of uterine contractions per second
- *light_decelerations* - Number of light decelerations per second
- *severe_decelerations* - Number of severe decelerations per second
- *prolongued_decelerations* - Number of prolonged decelerations per second
- *abnormal_short_term_variability* - Percentage of time with abnormal short-term variability
- *mean_value_of_short_term_variability* - Mean value of short-term variability
- *percentage_of_time_with_abnormal_long_term_variability* - Percentage of time with abnormal long-term variability
- *mean_value_of_long_term_variability* - Mean value of long-term variability
- *histogram_width* - Width of FHR histogram
- *histogram_min* - Minimum (low frequency) of FHR histogram
- *histogram_max* - Maximum (high frequency) of FHR histogram
- *histogram_number_of_peaks* - Number of histogram peaks
- *histogram_number_of_zeroes* - Number of histogram zeros
- *histogram_mode* - Histogram mode
- *histogram_mean* - Histogram mean
- *histogram_median* - Histogram median
- *histogram_variance* - Histogram variance
- *histogram_tendency* - Histogram tendency  

**TARGET:-**  
- *fetal_health* - Tagged as 1 (Normal), 2 (Suspect) and 3 (Pathological)

This repository contains the following files:
1. **Code**
   - Fetal Health Classification.ipynb
2. **Dataset**
   - fetal_health.csv  
3. **README**  

 Here's the link to the dataset:  
 https://www.kaggle.com/andrewmvd/fetal-health-classification
