# Medical Transcription Classification Project

## Overview
This project focuses on classifying medical transcriptions into various medical specialties using advanced NLP techniques. By leveraging the RoBERTa model, we aim to accurately interpret the complex language of medical documents and categorize them based on their content.

## Installation
To set up the project environment, follow these steps:

1. Clone the repository: 
```git clone git@github.com:anush97/MedDiagnosis.git```
2. Navigate to the project directory:
```cd MedDiagnosis```
3. Install the required dependencies
```pip install -r requirements.txt```

## Data
The dataset comprises medical transcriptions with corresponding keywords and medical specialties. 

## Usage
To run the project - run diagnosis_using_roberta.ipynb

## Project Structure
- `requirements.txt`: Lists all the necessary Python packages.
- `diagnosis_using_roberta.ipynb`: Full code

## Model
The project utilizes the RoBERTa model, chosen for its advanced language understanding capabilities, especially suited for processing the nuanced language in medical transcriptions.

### Advantages of RoBERTa:
- Superior performance in text classification tasks.
- Enhanced contextual understanding for medical terminology.
- Efficiency in model training through transfer learning.

### Limitations:
- High computational resources required.
- Potential overfitting on specialized datasets.

## Results
The model's performance is evaluated using metrics such as Balanced Accuracy and F1 Score. Detailed results and analysis are provided in the Jupyter notebook included in this repository.

## Visualization
The project includes visualizations such as the distribution of medical specialties and a confusion matrix for model evaluation. These visualizations aid in understanding the model's performance and the dataset's characteristics.

## Keyword Analysis
Special attention is given to the analysis of specific keywords like "Rectocele" and "Cystocele". Visualizations and summary statistics are provided to illustrate the findings.
