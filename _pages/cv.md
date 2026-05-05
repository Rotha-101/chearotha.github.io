---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Engineering Degree in Data Science**, Institute of Technology of Cambodia (ITC), 2020 – 2025
  * Major in Applied Mathematics and Statistics
  * Thesis: Analysis and Forecasting of Inflation in Cambodia
* **English & French (Basic)**, Aii Language Center, 2019 – 2022

Professional Experience
======
* **Battery Energy Storage System Engineer, Data Analysis**, Dec 2025 – Present
  * SchniecTech Group
  * Analyzed high-frequency time-series data from EMS / SCADA systems.
  * Built interactive dashboards for real-time monitoring of grid and plant performance.
  * Conducted anomaly detection for power fluctuations and system faults.

* **Data Scientist**, Feb 2025 – Oct 2025
  * Ministry of Planning, Cambodia
  * Developed a hybrid inflation forecasting model (XGBoost + LSTM + SARIMAX).
  * Built data pipelines for macroeconomic indicators.
  * Created interactive dashboards to support policy-making and economic planning.

* **Instructor – Data Science**, Jan 2024 – Feb 2025
  * Sunrise Institute
  * Taught ML, forecasting, and data visualization with practical Python and Power BI projects.
  * Mentored students on data storytelling and presentation.

Skills
======
* **Programming**: Python, SQL, React JS, Matlab, R, Java, C#
* **Machine Learning**: Scikit-learn, TensorFlow, Keras, XGBoost, LightGBM
* **Time Series**: ARIMA, SARIMA, LSTM, Prophet
* **Data Viz**: Matplotlib, Seaborn, Plotly, Tableau, Power BI
* **NLP**: Transformers, NLTK, SpaCy, LoRA Fine-Tuning
* **Databases**: MySQL, PostgreSQL, SQLite, MongoDB

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
References
======
* **PHAUK Sokkhey, Ph.D**
  * Deputy head of department of applied mathematics and statistics (AMS), ITC
  * Email: phauk.sokkhey@itc.edu.kh
* **Mr. Pakrina Long**
  * IT Lecturer in DATA Science, ITC
  * Email: long.pakrigna@itc.edu.kh
