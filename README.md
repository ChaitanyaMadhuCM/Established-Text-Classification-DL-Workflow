# Text-Classification-DL-Workflow
**Industry-Standard approach to: Multi-Class Text Classification using DL and NLP (end-to-end).**


## Table of Contents

1. **Hypothesis Generation**
   - Overview of the project.
   - Purpose and objectives.

2. **Import Libraries**
   - Import all essential libraries for data processing and model building. 

3. **Import Dataset**
   - Description of the dataset used for training and evaluation.

4. **Exploratory Data Analysis (EDA)**
   - Visualization of data distribution.
   - Label frequency analysis.
  
5. **Data Preprocessing**
   - Tokenization
   - Handle Errors/Noise
   - Remove Stopwords
   - Lemmatization 
  
6. **Dataset Splitting**
   - Split the data into training and validation sets.

7. **Data Transformation (for NLP)**
   - Embedding and Encoding 

8. **Model Selection and Fine-Tuning**
   - Define Network
   - Compile Network
   - Fit Network
   - Evaluate Network

9. **Model Dumping**
   - Save the model and supporting files to local.

10. **Load Dumped Model for Real-time Testing**
   - Code snippets for real-time testing of the model on new text samples.


## Pre-requisites

- Python 3.11.7
- Libraries
   - create a virtual environment using `python -m venv classifytext_dl_env`
   - activate the virtual environment using `classifytext_dl_env\Scripts\activate`
   - install the libraries using `pip install -r requirements.txt`


__Note: Neural networks are stochastic algorithms, meaning that the same algorithm on the same data can train a different model with different skill each time the code is run. This is a feature, not a bug.__
