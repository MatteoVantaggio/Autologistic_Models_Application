# Autologistic Modelling of Oribatid Mite Species

This project was developed as part of coursework for a graduate-level class in Spatial Statistics and Statistical Tools for Environmental Data. It explores the spatial distribution and modeling of two Oribatid mite species using autologistic regression models.


## Objective

To analyze and model the spatial presence/absence patterns of two species of mites—**Oppiella nova (ONOV)** and **Lepidozetes ciliatus (LCIL)**—using logistic and autologistic regression models, and to assess the effect of spatial autocorrelation and environmental variables on species distribution.


## Methodology

### 1. **Data Preparation**
- Created binary presence/absence variables for species ONOV and LCIL.
- Scaled and inspected environmental variables for multicollinearity and distributional properties.

### 2. **Model Specification**
- Built **logistic regression models** as baseline (no spatial structure).
- Fitted **autologistic regression models** for both species:
  - Included environmental covariates
  - Explored different neighborhood structures:  
    First-order (rook), second-order (queen)
  - Used **pseudo-likelihood estimation** for parameter fitting.

### 3. **Model Comparison**
- Compared models based on **AIC**, **log-likelihood**, and **predictive performance**.
- Selected best neighborhood structure for each species based on out-of-sample predictive accuracy and parsimony.

### 4. **Prediction & Mapping**
- Computed predicted probabilities of presence over the spatial grid.
- Generated maps for:
  - Baseline logistic models
  - Final autologistic models for each species
- Used color gradients to represent probability of occurrence.

### 5. **Model Validation**
- Assessed predictive performance using:
  - Cross-validation
  - Confusion matrix and other threshold-dependent metrics
  - Visual comparison between predicted and observed presence


## 🔗 Report Access

👉 [**Click here to view the full HTML report**](https://tuo-username.github.io/nome-repo/HOMEWORK_8.html)
