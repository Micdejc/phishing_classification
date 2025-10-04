# Phishing Email Classification with Llama 2 and LM Studio

This project demonstrates how to classify phishing emails using a **local LLM** (Llama 2) through **LM Studio**. The Python script processes a CSV file of emails, predicts whether each email is phishing (`1`) or not (`0`), and generates a brief justification for each verdict.

---

## **Table of Contents**

- [Overview](#overview)  
- [Features](#features)  
- [Requirements](#requirements)  
- [Installation](#installation)  
- [Usage](#usage)  
- [CSV Format](#csv-format)  
- [Output](#output)  
- [Tips & Notes](#tips--notes)  
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
- Python packages:

```bash
pip install pandas requests
