# PlanckGBM
In this repo, I will share a part of my master's thesis codes with the title of:

**"Planck Limits on Cosmic String Tension Using Image Processing and Machine Learning."**

In this project, our purpose was to find cosmic strings footprints on Planck’s data. Cosmic strings are important because some theories predict that they could have been produced during phase transition in the early universe. The presence or absence of cosmic strings in the universe can accept or reject theories about phase transitions in the early universe. Using Planck’s data, we constrained the tension (the main parameter characterizing the string network) of cosmic string (Gµ). We did the following steps to get our results:

- Use several CMB and cosmic string network simulations to build and test classification models.
- Use image processing steps like Curvelet decomposition and Canny Filtering to increase the detectability of cosmic string signature.
- Quantify the possible imprints by applying statistical measures like standard deviation and probability density function.
- Use different machine learning algorithms such as Decision Tree, Random Forest, Gradient Boosting, k-Nearest Neighbors (KNN), Naive Bayes, LightGBM, XGBoost, etc., to detect cosmic string.
- Apply the model with the highest performance (LightGBM) on Planck’s data to find the bound on the tension of cosmic string on observational data.
- Result: found no observable trace and yielded upper limit of Gµ ≤ 8.6 × 10−7 with 3σ confidence level

In the following image you can see pipeline of my works during this project:

![alt text](https://github.com/halehhajizadeh/PlanckGBM/blob/main/LGBM_pipeline.jpg)



You can find the google colab file in the with the following link:

https://github.com/halehhajizadeh/PlanckGBM/blob/main/CosmicString.ipynb

**IMPORTANT POINT: 
The shared code is just part of my codes for this project because the ram and storage of the google colab and google drive are limited. Therefore, We ran our code in a cluster.**
