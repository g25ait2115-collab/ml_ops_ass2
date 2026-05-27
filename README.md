# MLOps Assignment 2 - Hugging Face Fine-Tuning & Experiment Tracking

## Project Description
This project demonstrates a complete MLOps pipeline for text classification. A pre-trained DistilBERT model is fine-tuned on the UCSD Goodreads book reviews dataset to classify reviews into 8 genres. The workflow includes experiment tracking with Weights & Biases, model deployment to Hugging Face Hub, and training on Kaggle using free GPU resources.

## Setup Instructions
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set environment variables: `WANDB_API_KEY` and `HF_TOKEN`
4. Run the notebook on Kaggle with GPU enabled

## Training Platform
- Platform: Kaggle Notebook with GPU T4
- Model: DistilBERT (distilbert-base-cased)
- Dataset: UCSD Goodreads Reviews (8 genres, 1000 samples per genre)
- Epochs: 3, Batch Size: 16, Learning Rate: 3e-5

## Results

| Metric    | Score   |
|-----------|---------|
| Accuracy  | 0.5794  |
| F1 Score  | 0.5782  |
| Eval Loss | 2.3636  |

## Links
- Kaggle Notebook: https://www.kaggle.com/code/sumitg25ait2115/notebook3d6ddd2f59
- Hugging Face Model: https://huggingface.co/g25ait2115/distilbert-goodreads-genres
- W&B Dashboard: https://wandb.ai/g25ait2115-iit-jodhpur/mlops-assignment2
