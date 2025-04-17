MedMap
======

**MedMap** is a smart Doctor's Assistant app that leverages collaborative filtering and geolocation to improve patient care decisions.

Features
--------

-   **Procedure Prediction**\
    Using collaborative filtering, MedMap analyzes patient history and similar cases to predict the likelihood of a patient requiring specific medical procedures. This helps doctors prioritize investigations and manage treatment plans efficiently.

-   **Diagnosis-Based Specialist Finder**\
    Upload a diagnosis, and MedMap instantly finds the nearest specialists who are experts in handling that condition. This ensures patients get timely referrals to the right experts.

-   **MCP powered Personal Healthcare Agent**\
    The doctor's apprentice....

How It Works
------------

-   **Collaborative Filtering Engine:**\
    MedMap compares patient profiles, past diagnoses, and treatment patterns to suggest procedures a patient is most likely to need, based on similarities with other patients.

-   **Location Services:**\
    After a diagnosis is uploaded, MedMap uses location data to list nearby specialists, sorted by proximity and relevance.

Technologies Used
----------------

- NLP (BERT, OCR)

- Collaborative Filtering (KNN/Matrix Factorization)

- Forecasting (XGBoost/Prophet)

- Location APIs (OpenStreetMap, Leaflet.js)

- Frontend: HTML/CSS/JS

- Backend: Python , Tensorflow , sciPy/sklearn , Flask, EasyOCR


- Deployment: Streamlit

Getting Started
---------------

1.  **Sign Up / Log In**\
    Create a secure account to access all features.

2.  **Patient Analysis**\
    Enter or upload patient details to predict procedure likelihood.

3.  **Find Specialists**\
    Upload or select a diagnosis to view a curated list of nearby specialists.


This project is licenced under the MIT Licence
