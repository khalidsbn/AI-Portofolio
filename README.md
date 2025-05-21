# AI Portfolio  #

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khalidsabban/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@khalidsabban)
[![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/khalidsabban)

## Paper Implementation ##
### [Implementing AlexNet in PyTorch](https://github.com/khalidsbn/Implementing-AlexNet-in-PyTorch)
- Re-creates the 2012 ImageNet-winning AlexNet architecture (5 conv + 3 FC layers) entirely in PyTorch, staying faithful to kernel sizes, strides and LRN/dropout details. 
- Single, well-commented `alexnet.py` and an explanatory README break the model down layer-by-layer with spatial-dimension math — great for pedagogy or quick experiments.
- Lightweight repo (one script + docs) that compiles and trains out-of-the-box, making it an easy reference for CNN fundamentals in your portfolio.

### [ImageNet Insights](https://github.com/khalidsbn/ImageNet-Insights)
- Deep-dive summary of the 2009 ImageNet paper, plus the original PDF for reference. Covers scale (3.2 M images / 5,247 synsets) and WordNet-based hierarchy. 
- Walks through the two-stage data-collection pipeline (web scraping → Mechanical Turk vetting) that achieved ~99.7 % label precision. 
- Compares ImageNet to Caltech-256, TinyImages, etc., highlighting why its density and hierarchy changed computer-vision benchmarks. 
- Outlines key applications—object recognition, tree-based classification, localization—and how ImageNet sparked architectures from AlexNet to ResNet. 
- Includes a ready-to-run PyTorch snippet for loading ImageNet and notes on using pre-trained models for transfer learning. 

## End to End Projects ##
### [Spotify Pipeline](https://github.com/khalidsbn/AudioFamePipeline)
- End-to-end ML workflow that **pulls raw track metadata from the Spotify Web API, cleans it, engineers audio-feature columns (danceability, energy, tempo, etc.), and trains a regression model to score “popularity.”** 
- **Fully automated pipeline**: config files + `src/` modules + PyTest suite make the data→model path reproducible from a single CLI command. 
- **Feature-importance analysis** surfaces the attributes that matter most for hit potential—insightful for A&R or playlist-curation use cases.  
- Delivered with notebooks for EDA, a `requirements/environment.yml` for quick spin-up, and plans for a short research paper summarising findings. 

### [Salary App](https://github.com/khalidsbn/salary-app)
- **Streamlit web app** that predicts a full-time software engineer’s annual salary using Stack Overflow 2023 survey data. 
- Two-tab UI: **“Predict”** collects user inputs and returns an instant estimate; **“Explore”** visualises the dataset with interactive charts.  
- Pipeline built in Jupyter notebooks → XGBoost model persisted as `model_steps.pkl`, then served by lightweight Python scripts (`app.py`, `predict_page.py`). 
- **Prod-ready extras**: Procfile + `setup.sh` for easy deployment on Heroku/Render and a clean `requirements.txt`.   

### [Laptop Price Predictor](https://github.com/khalidsbn/Laptop-Price-Predictor)
- **Flask application** that estimates laptop prices (in €) from 11 spec fields—brand, CPU, RAM, GPU, OS, screen size, etc.—using an XGBoost regressor.
- Clear repo split: `notebooks/` for data cleaning & feature engineering, `app/` for production code (`app.py`, `model.py`, HTML/CSS assets).  
- Walk-through notebooks document EDA, preprocessing and model tuning; users can reproduce results or plug in updated datasets with minimal code edits.
- Local run in five commands (`git clone` → `venv` → `pip install` → `cd app` → `python app.py`); instructions and UI screenshots included.
----

# Skill-Based Projects #

## Generative AI ##

### Fine-Tuning LLMs ###


### Reterival Augmented Generation (RAG) Application ###

### Prompt Engineering ###

  
## Machine Learning
### Regression
* [Spotify Pipeline](https://github.com/khalidsbn/AudioFamePipeline): Automates Spotify API data extraction and trains regression to rank track popularity, revealing which audio features drive hits.  
* [Salary App](https://github.com/khalidsbn/salary-app): Streamlit app predicting software-engineer salaries from the Stack Overflow survey with XGBoost and interactive exploratory dashboards. 
* [Laptop Price Predictor](https://github.com/khalidsbn/Laptop-Price-Predictor): Flask web app estimates laptop prices in euros using XGBoost on 11 hardware specs, with clean notebooks and UI.   

### Classification
* [Home Credit Default Risk](https://github.com/khalidsbn/Home-Credit-Default-Risk): Processes multi-table loan data and builds a classifier to predict applicant default risk, boosting financial inclusion.  
* [Airbnb User's Destination](https://github.com/khalidsbn/Users-destination): Models Airbnb user behavior to predict first destination country and booking likelihood, enabling personalized marketing. 
* [Surviver Prediction](https://github.com/khalidsbn/Survived-prediction): Classic Titanic Kaggle pipeline using random forest to predict passenger survival with exploratory visualizations. 

### Clustering
* [Customer Segmentation](https://github.com/khalidsbn/Customer-Segmentation): Clusters mall customers via K-Means on income and spending to guide targeted promotions. 

---

## Deep Learning
### Classification
* [Binary Classification PyTorch](https://github.com/khalidsbn/cats-dogs-classifcation-pytorch): PyTorch CNN distinguishes cat versus dog images, showcasing modular training scripts and pretrained model.  

---

### Reinforcement Learning
* [Solving Grid Environments with Q Learning](https://github.com/khalidsbn/PyGridNavigator-Solving-Grid-Environments-with-Q-Learning): Implements Q-learning agent navigating custom 5×5 grid world with obstacles, demonstrating core RL concepts.
* [Taxi Q Learning](https://github.com/khalidsbn/taxi-q-learning): Trains a Q-learning taxi agent in OpenAI Gym to efficiently pick up and drop passengers, with hyperparameter tuning.

---

### Natural Language Processing 

---

### Time-series Analysis

---

### Data Visulization:

---

### Spark 

---

### Data Modeling 

---



### Certificates 
* [Python](https://www.kaggle.com/learn/certification/khalidsabban/python) 
* [Intro To Machine Learning](https://www.kaggle.com/learn/certification/khalidsabban/intro-to-machine-learning)  
* [Pandas](https://www.kaggle.com/learn/certification/khalidsabban/pandas)
* [Intermediate Machine Learning](https://www.kaggle.com/learn/certification/khalidsabban/intermediate-machine-learning)
* [Neural Networks and Deep Learning](https://www.coursera.org/account/accomplishments/verify/EB84C5VBPU3T)
* [Natural Language Processing with Classification and Vector Spaces](https://www.coursera.org/account/accomplishments/specialization/C870VYWK4RN0) 
* [Natural Language Processing with Probabilistic Models](https://www.coursera.org/account/accomplishments/specialization/C870VYWK4RN0)
* [Natural Language Processing with Sequence Models](https://www.coursera.org/account/accomplishments/specialization/C870VYWK4RN0)
* [Natural Language Processing with Attention Models](https://www.coursera.org/account/accomplishments/specialization/C870VYWK4RN0)
---

### Course Work

