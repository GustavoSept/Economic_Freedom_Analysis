# 📁 What's Inside This Repository?
This project is about answering a single (yet quite big and complex) question: how important is Economic Freedom in predicting prosperity?

Along the way, we'll answer other questions, like:
- What's a good proxy for the vague term 'Prosperity'?
- how does each aspect of Economic Freedom correlate with prosperity?
- Does Economic Freedom (or prosperity) increase inequality?
- Is it possible to (partially) explain future growth with current Economic Freedom metrics?

## 🌟 **What's done:**
- Initial Data Acquisition & Cleaning
- Basic Exploratory Data Analysis (EDA)
- Time Slider Analysis (to poke at causality explanation)

## 📌 **What needs to be done:**
- More data collection (via APIs and Web Scraping) on dozens of Socio-Cultural-Economic-Geo-Political metrics
- Data Cleaning on new data
- Model building on all of the collected features
	- I plan to do the usual iterative pipeline for ML modeling:
		- I'll account for multicollinearity between all features
		- Evaluate multiple regression algorithms, and fine tune hyperparameters
		- Since the data isn't that big, use Cross Validation for evaluation 
- Write a Report detailing the process for easier access