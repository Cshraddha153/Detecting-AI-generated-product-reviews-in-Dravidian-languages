# Evaluating the Effectiveness of Large Language Models in Detecting AI-Generated Dravidian Language Content

This project focuses on detecting AI-generated product reviews in Tamil and Malayalam using transformer-based models. We applied text preprocessing techniques such as stop-word removal and tokenization before fine-tuning XLM-RoBERTa, MuRIL, ALBERT, and mBERT using the ktrain library. The goal is to classify reviews as either AI-generated or human-written with high accuracy.

# Methodology
To detect AI-generated product reviews in Tamil and Malayalam, we employed a transformer-based classification approach, integrating text preprocessing techniques and fine-tuning multiple pre-trained language models. The methodology consists of the following key stages:

## 1. Data Collection and Preprocessing
The dataset consists of product reviews in Tamil and Malayalam, with an equal distribution of AI-generated and human-written reviews. To prepare the textual data for model training, we applied the following preprocessing techniques:

**Stop-word removal**: Eliminating common words that do not contribute significantly to meaning.
**Tokenization**: Splitting text into meaningful units for efficient processing.
**Normalization**: Standardizing text by converting characters to lowercase and handling special characters.

## 2. Feature Extraction and Model Selection
We experimented with several transformer-based models known for their effectiveness in multilingual NLP tasks. The selected models include:

### Models Used  
- **XLM-RoBERTa**: A cross-lingual language model designed for multilingual understanding.  
- **MuRIL**: A model specifically fine-tuned for Indian languages, enhancing contextual understanding.  
- **ALBERT**: A lightweight transformer model designed to improve efficiency while retaining performance.  
- **mBERT**: A multilingual variant of BERT that supports various languages, including Tamil and Malayalam.  


## 3. Model Training and Fine-Tuning
We utilized the ktrain library to fine-tune the pre-trained transformer models on the given dataset. The training process included:

**Text vectorization**: Converting textual input into numerical representations using transformer tokenizers.
**Model adaptation**: Fine-tuning each model on the dataset to optimize performance.
**Hyperparameter tuning**: Adjusting learning rates, batch sizes, and training epochs to improve generalization.

## 4. Evaluation and Performance Analysis
The models were evaluated based on accuracy and F1-score to assess their effectiveness in classifying AI-generated and human-written text. Comparative analysis across different models was conducted to determine the best-performing approach.

# Rank List
### Team Name - MNLP
1. Rank List of AI-HUMAN generated product review detection in Tamil - [Rank List of AI-HUMAN product review detection in Tamil.pdf](https://github.com/user-attachments/files/19090275/Rank.List.of.AI-HUMAN.product.review.detection.in.Tamil.pdf)
2. Rank List of AI-HUMAN generated product review detection in Malayalam - [Rank List of AI-HUMAN product review detection in Malayalam.pdf](https://github.com/user-attachments/files/19090291/Rank.List.of.AI-HUMAN.product.review.detection.in.Malayalam.pdf)

# Research Paper
paper - [AI_Content_Detection.pdf](https://github.com/user-attachments/files/19090398/AI_Content_Detection.pdf)



