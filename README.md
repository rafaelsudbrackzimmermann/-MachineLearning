# Machine learning Portfolio 

This is a repository of the projects I worked on or currently working on. It is updated regularly. I also have the Jupyter Notebook version of some of my Kaggle kernels here.

## Load Disaggregation Challenge: Energy Use in Buildings - 2024 - [Gold medal - 1st place - Top 1%] 🥇
- **Complete Project Repository**: [Link to the full project](https://github.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-Adrenalin-Load-Disaggregation-Challenge/tree/main)
- **1- Preprocess Data**: [link](https://github.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-Adrenalin-Load-Disaggregation-Challenge/blob/main/Submission%201/code/_1_pre_process.py)
- **2- Model**: [link](https://github.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-Adrenalin-Load-Disaggregation-Challenge/blob/main/Submission%201/code/_2_model.py)
- **3- Main Training**: [link](https://github.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-Adrenalin-Load-Disaggregation-Challenge/blob/main/Submission%201/code/_4_main_train.py)
- **Resources**: 
  - [Website](https://adrenalin.energy/Load-Disaggregation-Challenge-Energy-use-in-buildings)
  - [Paper](https://github.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-ADRENALIN/blob/main/Submission%201/Report.docx)
- **Keywords**: Unsupervised Learning, Time-Series, Disaggregation, Decomposition, Clustering 

#### Project Overview
<img src="https://raw.githubusercontent.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-Adrenalin-Load-Disaggregation-Challenge/main/Submission%201/Banner2.png" alt="Project Banner" width="600" height="150">

**The Problem:**
Energy management in buildings often lacks detailed insights due to the absence of extensive metering, making it challenging to identify how specific systems like heating and cooling contribute to overall energy consumption.

**The Solution:**
To address this, our team developed a solution using an unsupervised learning approach with the Adjusted STL (Seasonal-Trend Decomposition using LOESS) algorithm. This method improves upon traditional energy disaggregation techniques by adapting to complex and noisy data without needing predefined labels or extensive historical data inputs.

**Impact:**
This unsupervised and adaptable approach allows building managers to effectively monitor and control energy usage for various systems without the need for complex and expensive sub-metering infrastructure. By leveraging basic meter data, our model provides a scalable and economically viable solution for energy management across diverse building environments.

**Competition Results:**
- **nMAE**: 0.235 (Ranked 1st)

## 5G-Energy-Consumption-Modelling-Challenge - 2023 - [Gold medal - 3st place - Top 1%] 🥇
- **Complete Project Repository**: [Link to the full project](https://github.com/ITU-AI-ML-in-5G-Challenge/-3-Place-Solution-5G-Energy-Consumption-Modelling-Challenge)
- **Colab Presentation**: [link](https://github.com/ITU-AI-ML-in-5G-Challenge/-3-Place-Solution-5G-Energy-Consumption-Modelling-Challenge/blob/main/ITU_5G_Model_WMAPE-0.69.ipynb)
- **Resources**: 
  - [Website](https://aiforgood.itu.int/event/5g-energy-consumption-modelling-ai-ml-solutions-for-climate-change/)
  - [Report](https://github.com/ITU-AI-ML-in-5G-Challenge/-3-Place-Solution-5G-Energy-Consumption-Modelling-Challenge/blob/main/ITUJ-2024-0022.R2_APR_TSB_EDIT.pdf)
- **Keywords**: Supervised Learning, Ridge, XGBoost, Time-Series, Forecasting, Mixture of Experts

#### Project Overview
<img src="https://raw.githubusercontent.com/ITU-AI-ML-in-5G-Challenge/-3-Place-Solution-5G-Energy-Consumption-Modelling-Challenge/main/Banner.png" alt="Project Banner" width="600" height="150">

**The Problem:**
In the 5G energy consumption modeling challenge, participants were tasked with predicting the energy usage of 5G networks. This challenge highlights the difficulty in accurately forecasting energy consumption due to the dynamic nature and complex deployment scenarios of 5G technology.

**The Solution:**
Our team developed a predictive model tailored to the specific energy patterns of 5G networks. We segmented our approach into three key objectives to handle different scenarios: direct forecasting for known base stations, generalization for new stations with similar configurations, and broad generalization for entirely new configurations. We employed advanced data processing techniques, a Mixture of Experts approach, and an ensemble of Ridge Regression and XGBoost models to enhance prediction accuracy.

**Impact:**
Our findings and methodologies were compiled into a research paper that has been published, contributing to the broader understanding of energy management in 5G networks. [Paper](https://github.com/ITU-AI-ML-in-5G-Challenge/-3-Place-Solution-5G-Energy-Consumption-Modelling-Challenge/blob/main/ITUJ-2024-0022.R2_APR_TSB_EDIT.pdf)

**Competition Results:**
- **WMAPE**: 0.069 (Ranked 3st)

## Enefit - Predict Energy Behavior of Prosumers - 2024 - [Silver medal - 109th place - Top 4%] 🥈
- **Final Solution**: [link](https://github.com/rafaelsudbrackzimmermann/-MachineLearning/blob/main/portfolios/enefit/enefit-final-submission.ipynb)
- **Resources**: 
  - [Website](https://www.kaggle.com/competitions/predict-energy-behavior-of-prosumers/overview)
- **Keywords**: Supervised Learning, Advanced Feature Engineering, LightGBM, Time-Series, Forecasting.

#### Project Overview
<img src="https://raw.githubusercontent.com/rafaelsudbrackzimmermann/-MachineLearning/main/portfolios/enefit/Banner.png" alt="Project Banner" width="600" height="150">

**The Problem:**
Energy imbalance is a significant challenge in power grids, particularly with the rise of prosumers—consumers who both produce and consume energy. These prosumers can cause unpredictable fluctuations in energy demand and supply, leading to operational inefficiencies, higher costs, and potential grid instability.

**The Solution:**
The solution utilizes a comprehensive framework featuring data management, advanced feature engineering, and predictive modeling to accurately forecast energy behavior of prosumers. The core functionality centers around a LightGBM-based ensemble model, integrated with the competition's API, ensuring timely and rule-compliant predictions. Key libraries like pandas, polars, lightgbm, and sklearn facilitate sophisticated data operations and model execution, with the primary objective of minimizing energy imbalances by enhancing prediction accuracy.

**Impact:**
If successfully implemented, these models can significantly reduce energy imbalance costs, enhance grid reliability, and foster the integration of renewable energy sources by making the energy behavior of prosumers more predictable and manageable. This improvement could also encourage more consumers to become prosumers by ensuring their energy contributions are effectively utilized, promoting sustainability.

**Competition Results:**
- **MAE**: 59.726 (Ranked 109st)

## HMS - Harmful Brain Activity Classification - 2024 - [Silver medal - 78th place - Top 3%] 🥈
- **Final Solution**: [link](https://www.kaggle.com/code/rafaelzimmermann1/no-ensemble-new-spectrograms-label-refine)
- **Spectograms**: [link](https://www.kaggle.com/code/rafaelzimmermann1/hms-spectrogram-creation-using-gpu)
- **Resources**: 
  - [Website](https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification/overview)
- **Keywords**: Computer Vision, TensorFlow, Keras, EfficientNetB0, Data Augmentation, self-labeling refinement.

#### Project Overview
<img src="https://raw.githubusercontent.com/rafaelsudbrackzimmermann/-MachineLearning/main/portfolios/HMS/header.png" alt="Project Banner" width="600" height="150">

**The Problem:**
This project is part of a competition aiming to automate the analysis of EEG signals to detect seizures and other harmful brain activity. Advanced machine learning models were used to classify EEG patterns, potentially speeding up diagnosis and improving treatment accuracy in critical neurocare.
EEG analysis currently depends on manual review by specialized neurologists, a time-consuming and error-prone process due to fatigue and the subjective nature of the analysis. This creates bottlenecks in treatment and research.

**The Solution:**
We developed a solution using TensorFlow and Keras to automate EEG analysis. The architecture was based on EfficientNetB0, chosen for its effectiveness in handling image data, which is similar in complexity to spectrograms derived from EEG signals. Data enhancement techniques included generating custom spectrograms with libraries like cupy and cusignal, tailored to capture the nuances of EEG data. The training approach involved self-labeling refinement to improve label accuracy, and cross-validation to ensure the model's robustness and reliability.

**Impact:**
The automation of EEG signal analysis could significantly decrease the time required for diagnosis, reduce costs, and increase the reliability of EEG readings across different medical settings. This advancement could greatly aid in treating critical brain conditions more efficiently and with greater accuracy.

**Competition Results:**
- **Kullback Leibler Divergence**: 0.279 (Ranked 78st)




