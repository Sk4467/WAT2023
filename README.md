# WAT2023
Participation in WAT2023 (Workshop on Asian Translation-2023)
# Multilingual Translation System

This repository contains the code and datasets for a Multilingual Translation System which translates English to Hindi, Bengali, and Malayalam. This project was completed as part of my internship at OdiaGen AI.

## System Overview

The system includes a fine-tuned pre-trained NLLB-200 model for Machine Translation. The model was fine-tuned using the Hindi Visual Genome dataset, along with the corresponding Bengali and Malayalam datasets. The system uses PyTorch to train the transformer model and makes inferences on the evaluation and challenge sets.

## Results

The system achieved the following BLEU scores on the evaluation and challenge sets:

- English to Hindi: Evaluation Set - 44.60, Challenge Set - 53.60
- English to Bengali: Evaluation Set - 49.20, Challenge Set - 47.80
- English to Malayalam: Evaluation Set - 46.60, Challenge Set - 39.70

## Requirements

To run this system, you will need:

- Python 3.7+
- PyTorch 1.7+

## Usage

To use this system, run the following command:

