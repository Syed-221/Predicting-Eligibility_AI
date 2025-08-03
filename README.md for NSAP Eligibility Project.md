# **Predicting NSAP Eligibility**

## **Project Description**

The National Social Assistance Program (NSAP) is a crucial social security program in India, providing financial aid to vulnerable populations. The manual process of verifying applications and assigning the correct sub-scheme to applicants can be slow and prone to errors.

This project aims to address this challenge by developing a machine learning-based multi-class classification model. The model will accurately predict the most appropriate NSAP scheme for an applicant based on their demographic and socio-economic data. The goal is to create a reliable and efficient tool to assist government agencies in streamlining the application process, ensuring that deserving individuals receive timely financial support.

## **Dataset**

The dataset used in this project is sourced from the DistrictwisePensiondataundertheNationalSocialAssistanceProgrammeNSAP.csv file. It contains information on various applicants, including their demographic details and the NSAP scheme they were ultimately assigned.

## **Methodology**

The project will follow a standard data science workflow, including:

1. **Data Exploration and Preprocessing**: Initial analysis of the dataset to understand its structure, identify missing values, and prepare the data for modeling.  
2. **Model Training**: The primary algorithm used is a Random Forest Classifier, with the model being built and trained using IBM Watson Studio's AutoAI feature.  
3. **Model Evaluation**: Evaluating the model's performance using key classification metrics to ensure it is robust and reliable.  
4. **Deployment (Conceptual)**: Creating a final, easy-to-use tool that could take new applicant data and predict the correct NSAP scheme.

## **Project Structure**

The repository is organized as follows:

* DistrictwisePensiondataundertheNationalSocialAssistanceProgrammeNSAP.csv: The primary dataset for this project.  
* \_P18 \- Random Forest Classifier\_ Predicting Eli....ipynb: The Jupyter notebook containing the code for the Random Forest Classifier model, likely generated with IBM Watson Studio's AutoAI.  
* README.md: This file, providing an overview of the project.

## **Getting Started**

To get a local copy of this project up and running, follow these steps:

1. Clone the repository:  
   git clone https://github.com/Syed-221/Predicting-Eligibility_AI.git

2. Navigate to the project directory:  
   cd Predicting-Eligibility\_AI

3. Install the required dependencies (if any). It is recommended to use a virtual environment.  
4. Open and run the Jupyter notebook to reproduce the analysis and model.

## **Contributing**

Contributions are welcome\! If you find a bug or have a suggestion, please open an issue. For major changes, please open a pull request.

## **License**

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## **Author**

Syed-221
