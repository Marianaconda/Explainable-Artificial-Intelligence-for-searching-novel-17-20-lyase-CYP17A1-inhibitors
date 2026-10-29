# Explainable-Artificial-Intelligence-for-searching-novel-17-20-lyase-CYP17A1-inhibitors-



Explainable AI-Guided Discovery of Selective Human CYP17A1 17,20-Lyase Inhibitors


Overview
Human CYP17A1 (17α-hydroxylase/17,20-lyase) is a key enzyme involved in steroid hormone biosynthesis and represents an important therapeutic target in castration-resistant prostate cancer (CRPC).

Although abiraterone is widely used clinically, its limited selectivity and associated side effects motivate the search for next-generation nonsteroidal inhibitors with improved biological profiles.

This project integrates machine learning, explainable artificial intelligence (XAI), and virtual screening techniques to identify structural determinants of selective CYP17A1 17,20-lyase inhibition and discover novel candidate compounds.

Objectives

To build multiclass predictive models capable of identifying selective 17,20-lyase inhibitors.
Compare molecular descriptors and fingerprint representations.
Interpret structure-activity relationships using SHAP.
Define applicability domains for reliable predictions.
Perform virtual screening to identify novel hit compounds.
Workflow
Data collection
      ↓
Data preprocessing
      ↓
Descriptor/Fingerprint generation
      ↓
Chemical space analysis and SHAP interpretation
      ↓
Model training
      ↓
Hyperparameter optimization
      ↓
Model evaluation
      ↓
Applicability Domain
      ↓
Virtual Screening
      ↓
Hit Identification


The optimized CatBoost classifier demonstrated the strongest performance:

Metric	Value
Balanced Accuracy	0.84
OvR ROC-AUC	0.97
These results support the suitability of gradient boosting approaches for identifying selective CYP17A1 17,20-lyase inhibitors.

Explainable AI
SHAP (SHapley Additive exPlanations) was employed to:

Identify structural features contributing to selectivity.
Quantify descriptor importance.
Improve model interpretability.
Support rational inhibitor design.


Outcome
Five nonsteroidal hit compounds were identified as promising candidates for further investigation as CYP17A1-targeting agents for prostate cancer treatment.


Scientific Impact
This work demonstrates how explainable artificial intelligence can accelerate the discovery of selective CYP17A1 inhibitors while providing mechanistic insights into molecular determinants of enzyme selectivity.
