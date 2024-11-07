# Task-1: Mountains Named Entity Recognition 

# Kaggle notebook links
- [Model training](https://www.kaggle.com/code/artemzysko/ner-mountains-roberta-train)
- [Model inference](https://www.kaggle.com/code/artemzysko/ner-mountains-roberta-inference)

# Dataset
- [Dataset generation notebook](https://www.kaggle.com/code/artemzysko/mountain-ner-create-dataset)
- [Dataset link](https://www.kaggle.com/datasets/artemzysko/generated-mountain-entity-recognition-dataset)

# Link to model weights
- [RoBERTa model weights for mountains NER](https://www.kaggle.com/models/artemzysko/roberta-ner-mountain)

# Requirements
pip install -r "task-1/requirements.txt"

# Brief description
All necessary links provided above.

- Dataset Creation:
Replaced "mountain"/"mountains" with real mountain names and added typos.
Annotated sentences with entity start and end indices.

- Data Augmentation:
Used p_typo for adding typos and n_repeats for sentence variations.
Used p_unchanged for keep sentence unchanged (no replacement)

- Model Training:
Fine-tuned Roberta on the dataset, tracking loss and saving model weights.

- Model Inference:
Built PipelineNER to process sentences and predict entity labels.
