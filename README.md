# Phishing Email Classification with Llama 2 and LM Studio

This project demonstrates how to classify phishing emails using a **local LLM** (Llama 2) through **LM Studio**. The Python script processes a CSV file of emails, predicts whether each email is phishing (`1`) or not (`0`), and generates a brief justification for each verdict.

---

## **Table of Contents**

- [Overview](#overview)  
- [Features](#features)  
- [Requirements](#requirements)  
- [Installation](#installation)  
- [Usage](#usage)  
- [License](#license)  

---

## **Overview**

Phishing attacks are a major cybersecurity threat. Using Llama 2 via LM Studio, this project allows you to:

- Automatically classify emails as phishing or not.  
- Generate a short justification for the classification.  
- Easily integrate LLM predictions into Python workflows.

---

## **Features**

- Uses **Llama 2** (chat model) for natural language classification.  
- Processes **CSV files** with `pandas`.  
- Returns both **binary verdict** and **justification**.  
- Handles API errors and non-standard model outputs.  
- Suitable for educational labs and small-scale experiments.

---

## **Requirements**

- Python 3.10 or higher  
- LM Studio installed and running locally  
- Llama 2 model downloaded in LM Studio (e.g., `llama-2-7b-chat`)  

---

## **Installation**

Install Python 3.10+ if not already installed: https://www.python.org/downloads/
Install LM Studio: https://lmstudio.ai
Download and load Llama 2 model in LM Studio
Install required Python packages:

```bash
pip install pandas requests jupyter

Clone this repository:

```bash
git clone https://github.com/your-username/phishing-classifier.git
cd phishing-classifier

## **Usage**

Start LM Studio and ensure your model is running.

Prepare a CSV file emails.csv with a column named text containing the emails to classify.

Open Jupyter Notebook or run the Python script directly:

```bash
python classify_phishing_emails.py


The script will generate a new CSV file emails_with_verdict.csv with the following columns:

text: Original email text

Llama verdict: 1 for phishing, 0 for not phishing

Llama justification: Brief explanation from the model

## **License**

This project is free licensed. Feel free to use it!
