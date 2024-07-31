## Quora Question Answering Model Analysis

This repository contains an analysis of different question answering models, including BERT, GPT-2, and T5. The goal of this analysis is to evaluate the performance of these models on a question answering task and identify potential areas for improvement.

### Dataset

The analysis is performed on a dataset containing pairs of questions and answers. The dataset is preprocessed to prepare it for the models.

### Models

Three different models are used for the analysis:

* **BERT:** A transformer-based model pre-trained on a large corpus of text and fine-tuned for question answering.
* **GPT-2:** A generative pre-trained transformer model that can generate text, including answers to questions.
* **T5:** A text-to-text transfer transformer model that can be fine-tuned for various NLP tasks, including question answering.

### Preprocessing

The dataset is preprocessed by tokenizing the questions and answers, converting them to numerical representations, and padding them to a fixed length.

### Training

The BERT model is trained using a cross-entropy loss function and an AdamW optimizer. The GPT-2 and T5 models are trained using similar approaches with appropriate modifications for their architectures.

### Evaluation

The models are evaluated using various metrics:

* **Accuracy:** The percentage of correctly answered questions.
* **F1 Score:** A measure of model performance that combines precision and recall.
* **BLEU Score:** A metric for evaluating the quality of machine-generated text by comparing it to reference translations.
* **ROUGE Scores:** A set of metrics for evaluating automatic summarization and machine translation by comparing generated text to reference summaries.

### Methadology



### Model Comparison

| Model | Accuracy | F1 Score | BLEU Score | ROUGE-1 | ROUGE-2 | ROUGE-L |
|---|---|---|---|---|---|---|
| BERT | 0.85 | 0.82 | - | - | - | - |
| GPT-2 | 0.78 | 0.75 | 0.51 (avg) | - | - | - |
| T5 | - | - | - | 0.60 | 0.45 | 0.55 |

**Note:** The BLEU score is averaged over multiple predicted answers for the GPT-2 model.

### Novel Improvements

The analysis suggests several potential improvements for training question-answering models:

* **Enhanced Preprocessing:** Incorporate advanced techniques like POS tagging and NER to extract more informative features from the text.
* **Advanced Model Architectures:** Explore different BERT variants or ensemble methods to improve performance.
* **Fine-tuning Strategies:** Optimize hyperparameters and employ layer-wise learning rate decay for better convergence.
* **Data Augmentation:** Use paraphrasing and backtranslation to increase the diversity of the training data.
* **Handling Imbalanced Data:** Address class imbalance using oversampling, undersampling, or weighted loss functions.
* **Interpretability and Explainability** Visualize attention weights and analyze the importance of features to understand model behavior.
* **Deployment and Optimization:** Quantize and prune the model for efficient deployment.
* **Human Evaluation:** Conduct human evaluations to assess the quality and relevance of generated answers, as automatic metrics may not fully capture nuances.


### Literature Survey

For further information, refer to the following resources:

* [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course/en/chapter7/7?fw=pt)
* [Data Augmentation in NLP](https://towardsdatascience.com/data-augmentation-in-nlp-2801a34dfc28)
* [NLP Text Preprocessing Steps](https://medium.com/@awaldeep/understanding-the-essentials-nlp-text-preprocessing-steps-b5d1fd58c11a)

* ### Visualization

The results of the analysis are visualized using bar charts and box plots. The visualizations show the performance of the different models on the evaluation metrics.
![Screenshot 2024-07-31 133822](https://github.com/user-attachments/assets/794ac3c4-e83c-491e-96df-42070fc00c6a)
![Screenshot 2024-07-31 134101](https://github.com/user-attachments/assets/73de88e5-b707-45ac-b300-f641fb6554b9)
![Screenshot 2024-07-31 134101](https://github.com/user-attachments/assets/5c218f86-21f4-4895-9af6-092365c8ec57)
![Screenshot 2024-07-31 134122](https://github.com/user-attachments/assets/3a579a8e-9a20-41c5-b8e6-a3fbd515dd44)

* ### Result 
![Screenshot 2024-07-31 135110](https://github.com/user-attachments/assets/bdbbe918-f8d1-4b14-b550-4cb89a2fc17f)





