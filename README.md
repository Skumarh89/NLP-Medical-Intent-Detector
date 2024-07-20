# NLP-Medical-Intent-Detector
NLP Transformer model for Medical Intenet Detection
This project aims to build a tool that classifies a person's description of their medical symptoms into the correct category (intent). This tool can be used in applications such as medical chatbots.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)


## Overview

The goal of this project is to build a medical intent detection tool using BERT, a state-of-the-art natural language processing model. This tool can classify text descriptions of medical symptoms into specific categories, aiding in applications like medical chatbots.

## Setup

### GPU Setup in Colab

This notebook is designed to run on Google Colab for easy access to GPU resources. To enable GPU in Colab:

1. Go to the menu: `Runtime` > `Change runtime type`
2. Select `GPU` from the `Hardware accelerator` drop-down menu.
3. Click `Save`.

## Installation

Ensure you have the following libraries installed. If using Colab, many of these come pre-installed, but you can install any missing ones using:

```bash
pip install transformers
pip install torch
pip install pandas
pip install scikit-learn
pip install seaborn
```
## Usage
1. Clone the Repository: Clone this repository to your local machine using:
  ```bash
  git clone https://github.com/Skumarh89/medical-intent-detector.git
  cd medical-intent-detector
  ```
2. Open the Notebook: Open the Intent_detect_BERT.ipynb notebook in Google Colab.
3. Run the Cells: Execute the cells sequentially. The notebook will guide you through setting up the environment, preprocessing data, training the model, and evaluating its performance.
4. Inference: Use the trained model to classify new medical symptom descriptions.


### Project Structure
* Data Preprocessing: Steps to preprocess the medical symptom data, including tokenization and formatting for BERT.
* Model Training: Code to train a BERT model on the preprocessed data.
* Evaluation: Evaluate the model's performance using accuracy, precision, recall, and F1-score.
* Inference: Using the trained model to classify new inputs.

### Dependencies
* Python 3.x
* `transformers` library by Hugging Face
* `torch` (PyTorch)
* `pandas`
* `scikit-learn`
* `seaborn`
