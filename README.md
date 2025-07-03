# DistilBERT-fine-tuning-on-FEVER-Dataset
This document presents methodology for adversarial NLI using FEVER dataset. We employed DistilBERT, a pre-trained transformer from Hugging Face, finetuned on NLI. To enhance accuracy, data augmentation techniques including Word Sense Disambiguation (WSD) and Semantic Role Labelling (SRL) were applied. Performance was compared across datasets.

----------------------------------------------------------------------------------------------------------------------------------------------------------
Instructions to Run the Code -----------------------------------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------------------------------------------------------------
Dataset Augmentation
The code is divided into two Jupyter notebooks:

Dataset Augmentation: This notebook augments the dataset using two semantic approaches: Word Sense Disambiguation (WSD) and Semantic Role Labelling (SRL).

Requirements:
Ensure the data directory path is accessible, containing the original FEVER dataset.

Output:
The notebook generates six datasets:
Three pairs of training and validation sets:
WSD approach
SRL approach
WSD + SRL combined approach

----------------------------------------------------------------------------------------------------------------------------------------------------------
Model Training and Evaluation
Model Training and Evaluation: This notebook is set to evaluate models by default. To initiate model training:
Uncomment the trainer.train() cell for the desired model.
Ensure the associated model cell is uncommented as well.

Precaution:
This setup prevents accidental training runs.

Pretrained Models:
Pretrained model weights are included in the notebook's directory for efficient execution.
----------------------------------------------------------------------------------------------------------------------------------------------------------
