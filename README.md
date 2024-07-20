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
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [License](#license)

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
