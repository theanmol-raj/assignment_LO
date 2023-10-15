# English to Hinglish Translation with TensorFlow and Hugging Face Transformers

## Introduction

This repository contains a TensorFlow implementation of a machine translation model for converting English text to Hinglish. The model utilizes the "google/flan-t5-small" transformer architecture, and it has been fine-tuned on the "findnitai/english-to-hinglish" dataset. This README provides information on how to use the model for English to Hinglish translation.

Author : @theanmol-raj
## Model Details

- **Model Architecture**: "google/flan-t5-small" transformer
- **Task**: English to Hinglish Translation

## Usage

### Requirements

Before using the model, make sure you have the following dependencies installed:

- TensorFlow
- Transformers (Hugging Face Transformers)
- Hugging Face Datasets

You can install them using `pip`:

pip install tensorflow transformers datasets


### Load the Model
To load the pre-trained model for English to Hinglish translation, you can use the following code:

### Training Data
The model was fine-tuned on the "findnitai/english-to-hinglish" dataset. You can find the dataset and additional details on the findnitai/english-to-hinglish GitHub repository.

### Citation
If you use this model in your research or projects, please consider citing the original T5 paper and the Hugging Face model hub:

### "Text-to-Text Transfer Transformer" by Colin Raffel et al. (2019) Link to Paper
Hugging Face Transformers Model Hub: Link to Model

Acknowledgments
We acknowledge the authors and contributors to the Hugging Face Transformers library and the "findnitai/english-to-hinglish" dataset for making this work possible.

Issues and Contributions
If you encounter any issues or would like to contribute to the project, please open an issue or pull request on the GitHub repository.
