# Machine learning Portfolio 

This is a repository of the projects I worked on or currently working on. It is updated regularly. I also have the Jupyter Notebook version of some of my Kaggle kernels here.

## Load Disaggregation Challenge: Energy Use in Buildings - 2024 - [Gold medal - 1st place - Top 1%] 🥇
- **Complete Project Repository**: [Link to the full project](https://github.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-Adrenalin-Load-Disaggregation-Challenge/tree/main)
- **1- Preprocess Data**: [link](https://github.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-Adrenalin-Load-Disaggregation-Challenge/blob/main/Submission%201/code/_1_pre_process.py)
- **2- Model**: [link](https://github.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-Adrenalin-Load-Disaggregation-Challenge/blob/main/Submission%201/code/_2_model.py)
- **3- Main Training**: [link](https://github.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-Adrenalin-Load-Disaggregation-Challenge/blob/main/Submission%201/code/_4_main_train.py)
- **Resources**: 
  - [Website](https://adrenalin.energy/Load-Disaggregation-Challenge-Energy-use-in-buildings)
  - [Report](https://github.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-ADRENALIN/blob/main/Submission%201/Report.docx)
- **Keywords**: Unsupervised Learning, Time-Series, Disaggregation, Decomposition, Clustering 

#### Project Overview
<img src="https://raw.githubusercontent.com/rafaelsudbrackzimmermann/1-PLACE-SOLUTION-Adrenalin-Load-Disaggregation-Challenge/main/Submission%201/Banner2.png" alt="Project Banner" width="600" height="150">

**The Problem:**
Energy management in buildings often lacks detailed insights due to the absence of extensive metering, making it challenging to identify how specific systems like heating and cooling contribute to overall energy consumption.

**The Solution:**
To address this, our team developed a solution using an unsupervised learning approach with the Adjusted STL (Seasonal-Trend Decomposition using LOESS) algorithm. This method improves upon traditional energy disaggregation techniques by adapting to complex and noisy data without needing predefined labels or extensive historical data inputs.

**Competition Results:**
- **nMAE**: 0.235 (Ranked 1st)

## 5G-Energy-Consumption-Modelling-Challenge - 2023 - [Gold medal - 3st place - Top 1%] 🥇
- **Complete Project Repository**: [Link to the full project](https://github.com/ITU-AI-ML-in-5G-Challenge/-3-Place-Solution-5G-Energy-Consumption-Modelling-Challenge)
- **Colab Presentation**: [link](https://github.com/ITU-AI-ML-in-5G-Challenge/-3-Place-Solution-5G-Energy-Consumption-Modelling-Challenge/blob/main/ITU_5G_Model_WMAPE-0.69.ipynb)
- **Resources**: 
  - [Website](https://aiforgood.itu.int/event/5g-energy-consumption-modelling-ai-ml-solutions-for-climate-change/)
  - [Paper](https://github.com/ITU-AI-ML-in-5G-Challenge/-3-Place-Solution-5G-Energy-Consumption-Modelling-Challenge/blob/main/ITUJ-2024-0022.R2_APR_TSB_EDIT.pdf)
- **Keywords**: Supervised Learning, Ridge, XGBoost, Time-Series, Forecasting, Mixture of Experts

#### Project Overview
<img src="https://raw.githubusercontent.com/ITU-AI-ML-in-5G-Challenge/-3-Place-Solution-5G-Energy-Consumption-Modelling-Challenge/main/Banner.png" alt="Project Banner" width="600" height="150">

**The Problem:**
In the 5G energy consumption modeling challenge, participants were tasked with predicting the energy usage of 5G networks. This challenge highlights the difficulty in accurately forecasting energy consumption due to the dynamic nature and complex deployment scenarios of 5G technology.

**The Solution:**
Our team developed a predictive model tailored to the specific energy patterns of 5G networks. We segmented our approach into three key objectives to handle different scenarios: direct forecasting for known base stations, generalization for new stations with similar configurations, and broad generalization for entirely new configurations. We employed advanced data processing techniques, a Mixture of Experts approach, and an ensemble of Ridge Regression and XGBoost models to enhance prediction accuracy.

**Competition Results:**
- **WMAPE**: 0.069 (Ranked 3st)

## HMS - Harmful Brain Activity Classification - 2024 - [Silver medal - 78st place - Top 3%] 🥈
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

**Competition Results:**
- **Kullback Leibler Divergence**: 0.279 (Ranked 78st)
  
## Enefit - Predict Energy Behavior of Prosumers - 2024 - [Silver medal - 109st place - Top 4%] 🥈
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

**Competition Results:**
- **MAE**: 59.726 (Ranked 109st)

## CAFA 5 Protein Function Prediction - 2023 - [186st place - Top 12%] 🥈
- **Final Solution**: [link](https://github.com/rafaelsudbrackzimmermann/-MachineLearning/blob/main/portfolios/CAFA5/model-t5-embeds-cafa5.ipynb)
- **Embeds**: [link](https://github.com/rafaelsudbrackzimmermann/-MachineLearning/blob/main/portfolios/CAFA5/embed_ProtT5.ipynb)
- **Resources**: 
  - [Website](https://www.kaggle.com/competitions/cafa-5-protein-function-prediction)
- **Keywords**: NLP, Protein Function Prediction, Deep Learning, Neural Networks, PyTorch.

#### Project Overview
<img src="https://raw.githubusercontent.com/rafaelsudbrackzimmermann/-MachineLearning/main/portfolios/CAFA5/Banner.png" alt="Project Banner" width="600" height="150">

**The Problem:**
Manually annotating protein functions is time-consuming and labor-intensive. This challenge focuses on automating the process using computational techniques, which can help in rapidly identifying potential biological roles of proteins based on their sequences.

**The Solution:**
The proposed solution involves using advanced machine learning models to predict protein functions from their amino acid sequences. The process starts by converting these sequences into numerical data that can be processed by neural networks. We use different types of embeddings (T5, ProtBERT, EMS2) which capture various aspects of protein structure and function from the sequence data. These embeddings are then input into neural network models (like MultiLayer Perceptron and Convolutional Neural Networks) to predict the functions associated with each protein. 

**Competition Results:**
- **Weighted F-measures**: 0.532 (Ranked 186st)


## ADIA Lab Causal Discovery Challenge - 2024 - [13st place - Top 2%] 🥈
- **Final Solution**: [link](https://github.com/rafaelsudbrackzimmermann/-MachineLearning/blob/main/portfolios/ADIA/Adia-Final-Model.ipynb)
- **Resources**: 
  - [Website](https://hub.crunchdao.com/competitions/causality-discovery/)
- **Keywords**: Causal Discovery, Directed Acyclic Graph (DAG), Deep Learning, Neural Networks, PyTorch.

#### Project Overview
<img src="https://raw.githubusercontent.com/rafaelsudbrackzimmermann/-MachineLearning/main/portfolios/ADIA/Banner.png" alt="Project Banner" width="600" height="150">

**The Problem:**
This competition seeks to automate the identification of causal relationships using computational methods, which can significantly speed up the process and increase accuracy in fields like healthcare and economics.

**The Solution:**
The proposed solution utilizes a sophisticated neural network model to predict causal directed acyclic graphs (DAGs) from observational data. The model begins by converting datasets into a structured format that neural networks can interpret. It employs advanced data processing techniques, including convolutional neural layers that analyze the relationships and interactions between variables. The network outputs predictions on the causal relationships, specifying how each variable affects or is affected by others, thereby automating the complex task of causal discovery.

**Competition Results:**
- **Multiclass balanced accuracy**: 58.596 (Ranked 13st)

## ISIC - Skin Cancer Detection with 3D-TBP - 2024
- **Final Solution**: [link](https://github.com/rafaelsudbrackzimmermann/-MachineLearning/blob/main/portfolios/ISIC/submissao-final-isic.ipynb)
- **Resources**: 
  - [Website](https://www.kaggle.com/competitions/isic-2024-challenge)
- **Keywords**: Image, Binary Classification, Deep Learning, Neural Networks, Keras, Tensorflow.

#### Project Overview
<img src="https://raw.githubusercontent.com/rafaelsudbrackzimmermann/-MachineLearning/main/portfolios/ISIC/Banner.png" alt="Project Banner" width="600" height="150">

**The Problem:**
This competition addresses the need to improve skin cancer triage using lower-quality images from 3D total body photos (TBP) that resemble smartphone pictures, making early detection more accessible.

**The Solution:**
The proposed solution employs advanced machine learning models to develop algorithms that can accurately differentiate between malignant and benign skin lesions from lower-quality 3D total body photos. These models use neural networks to process and analyze the images, aiming to provide reliable early skin cancer detection in non-clinical settings. The effectiveness of these algorithms is measured using a specific performance metric, the partial area under the ROC curve (pAUC), focusing on achieving high sensitivity in detecting malignant cases.

## ISIC - Learning Agency Lab - Automated Essay Scoring - 2024
- **Final Solution**: [link](https://github.com/rafaelsudbrackzimmermann/-MachineLearning/blob/main/portfolios/AES/versao-final-ensamble-final-aes.ipynb)
- **Resources**: 
  - [Website](https://www.kaggle.com/competitions/learning-agency-lab-automated-essay-scoring-2)
- **Keywords**: NLP, Cohen Kappa Score, Deep Learning, Neural Networks, Keras, Tensorflow.

#### Project Overview
<img src="https://raw.githubusercontent.com/rafaelsudbrackzimmermann/-MachineLearning/main/portfolios/AES/Banner.png" alt="Project Banner" width="600" height="150">

**The Problem:**
Manual essay grading is not only time-intensive but also restricts the use of writing assessments on a larger scale, particularly in under-resourced educational environments. In such settings, the delay in feedback from teachers can hinder student learning and development. Moreover, the diversity in student backgrounds requires that automated grading systems be unbiased and adept at evaluating a broad spectrum of writing styles and cultural nuances to ensure fairness and accuracy in assessment.

**The Solution:**
The proposed solution leverages advanced Natural Language Processing (NLP) technologies to develop an open-source automated essay scoring (AES) system. By incorporating neural network models such as BERT and DeBERTa, along with Transformer architectures, the system can understand and evaluate the complexities of student writing effectively. 


