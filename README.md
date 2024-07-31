# Question Answering Model Analysis

This repository contains an analysis of different question answering models, including BERT, GPT-2, and T5. The goal is to evaluate their performance and explore techniques for improving their accuracy and efficiency.

## Models and Techniques

### BERT

* **Model:** AutoModelForSequenceClassification from the Transformers library.
* **Evaluation Metrics:** Accuracy and F1 score.
* **Improvements:**
    * Explore advanced cleaning techniques for text preprocessing.
    * Incorporate Part-of-Speech tagging and Named Entity Recognition.
    * Experiment with different BERT variants like RoBERTa or DistilBERT.

### GPT-2

* **Model:** Custom GPT2ForSequenceClassification class.
* **Evaluation Metrics:** Accuracy, F1 score, and BLEU score.
* **Improvements:**
    * Utilize ensemble methods by combining predictions from multiple models.
    * Conduct hyperparameter optimization using techniques like grid search or Bayesian optimization.

### T5

* **Model:** T5ForConditionalGeneration from the Transformers library.
* **Evaluation Metrics:** ROUGE scores (ROUGE-1, ROUGE-2, ROUGE-L).
* **Improvements:**
    * Employ layer-wise learning rate decay for fine-tuning.
    * Conduct human evaluations to assess the quality of generated answers.

## Data Augmentation and Visualization

* **Data Augmentation Techniques:**
    * Synonym Replacement
    * Random Insertion
    * Random Deletion
    * Random Swap
    * Back Translation
    * Paraphrasing
* **Visualization:**
    * Bar charts for Accuracy, F1 score, and ROUGE scores.
    * Box plot for BLEU scores distribution.

## Further Improvements

* **Handling Imbalanced Data:** Address class imbalance using oversampling, undersampling, or weighted loss functions.
* **Interpretability and Explainability:** Visualize attention weights and analyze feature importance.
* **Deployment and Optimization:** Quantize and prune the model for efficiency.

## Literature Survey

* [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course/en/chapter7/7?fw=pt)
* [Data Augmentation in NLP](https://towardsdatascience.com/data-augmentation-in-nlp-2801a34dfc28)
* [Text Preprocessing Steps](https://medium.com/@awaldeep/understanding-the-essentials-nlp-text-preprocessing-steps-b5d1fd58c11a)
