# Hotel Cancellation Prediction

## Context
---
The hotel industry has been consistently growing, with the global hotel industry revenue on the rise. According to the Hospitality Global Market Report 2024, it will grow from $4673.63 billion in 2023 to $4993.71 billion in 2024 at a compound annual growth rate (CAGR) of 6.8%. Effective management of hotel bookings is crucial for maximizing revenue and optimizing operational resources. One of the most significant challenges currently facing the hospitality industry is the number of canceled reservations, leading to revenue loss and inefficient resource allocation. Predicting hotel booking cancellations can offer a competitive advantage by allowing proactive measures to mitigate negative impacts. 

This repository contains the code and data files for building a classification model to predict booking cancellations in a Portuguese hotel. The goal of this model is to assist hotel managers in identifying reservations that are to be canceled (labeled as 1) or those that will not be canceled (labeled as 0).

Given the significant cost associated with false negatives (missed cancellations), this project emphasizes minimizing these errors. To achieve this, I use the $F_2$ score as our primary evaluation metric, which places greater importance on recall, ensuring that potential cancellations are accurately identified.

## Dataset 
---
This project utilizes a dataset containing booking information from a Portuguese hotel. The dataset can be accessed [here](data_hotel_booking_demand.csv)

## Getting Started
---

To replicate my analysis or explore the data further, kindly follow the following steps:
1. Clone this repository to your local machine.
2. Ensure that all necessary dependencies are installed, especially Python and Jupyter Notebook. All libraries are specified on file requirements.txt.
3. Run Jupyter Notebook file (`*.ipynb`) to reproduce the analysis. This notebook contains the detailed implementation of data preprocessing, model training, and evaluation.

## Feedback
If there are any questions or suggestions for improvements, feel free to contact me here:

<a href="https://www.linkedin.com/in/friskahermalia/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:friskahermalia1@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>
