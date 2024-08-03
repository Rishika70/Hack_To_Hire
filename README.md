# NLP Project: Question Answering and Text Generation

This project explores the application of Natural Language Processing (NLP) techniques for question answering and text generation using pre-trained Transformer models like BERT, GPT-2, and T5.

## Project Overview

The project involves the following steps:

1. **Data Loading and Preprocessing:** Load a dataset suitable for question answering and text generation tasks. Preprocess the data by cleaning, tokenizing, and formatting it appropriately for each model.

2. **Model Selection and Fine-tuning:** Utilize pre-trained Transformer models (BERT, GPT-2, T5) and fine-tune them on the prepared dataset to optimize their performance for specific tasks.

3. **Question Answering:** Implement question answering functionality using the fine-tuned BERT model to extract relevant answers from given contexts.

4. **Text Generation:** Leverage the fine-tuned GPT-2 and T5 models to generate text based on given prompts, including generating answers for existing questions and creating questions from answers.

5. **Model Evaluation and Metrics:** Evaluate the performance of each model using appropriate metrics such as accuracy, F1 score, BLEU score, and ROUGE scores. Analyze the results to understand the strengths and weaknesses of each model.

6. **Data Visualization:** Create visualizations to compare the performance of different models across various metrics. Use bar plots, line plots, scatter plots, and other suitable visualizations to gain insights into model behavior.

7. **Model Improvement:** Explore strategies to improve model performance, including data augmentation, hyperparameter tuning, and advanced fine-tuning techniques.

## Results

### BERT Model Metrics:
- Accuracy: 1.0
- F1 Score: 1.0

### GPT-2 Model Metrics:
- Average BLEU Score: 0.4902
- Average ROUGE-1 F1 Score: 0.4429
- Average ROUGE-2 F1 Score: 0.1250
- Average ROUGE-L F1 Score: 0.4429

### T5 Model Metrics:
- Average BLEU Score: 0.5142
- Average ROUGE-1 F1 Score: 0.4663
- Average ROUGE-2 F1 Score: 0.1250
- Average ROUGE-L F1 Score: 0.4429

## Data Visualization

### Model Performance Comparison

![Model Performance Comparison](model_comparison.png)

### Model Performance Trends

![Model Performance Trends](model_trends.png)

### ROUGE-1 vs ROUGE-2 Scores

![ROUGE-1 vs ROUGE-2 Scores](rouge_scatter.png)

## Summary and Discussion

- The BERT model achieved perfect accuracy and F1 score on the given dataset, indicating potential overfitting. Further validation on an unseen dataset is recommended.
- GPT-2 and T5 models showed moderate performance in text generation, capturing key elements but needing improvement in generating nuanced and contextually rich text.
- Data augmentation, hyperparameter tuning, and advanced fine-tuning techniques can be explored to enhance model performance.

## Literature Survey

- [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course/en/chapter7/7?fw=pt)
- [Data Augmentation in NLP](https://towardsdatascience.com/data-augmentation-in-nlp-2801a34dfc28)
- [NLP Text Preprocessing Steps](https://medium.com/@awaldeep/understanding-the-essentials-nlp-text-preprocessing-steps-b5d1fd58c11a)

## How to Run

1. Install required libraries:





