# ML-7641-Project-Group-50
## BERT Integration in Question-Answering (QA) Systems

#### Introduction
In the ever-evolving landscape of Natural Language Processing (NLP), the quest for models capable of understanding and generating human-like responses is crucial. BERT (Bidirectional Encoder Representations from Transformers) has emerged as a groundbreaking architecture, redefining benchmarks in NLP tasks. Our project is centered around integrating BERT into QA tasks, aiming to significantly enhance performance and emulate human-like conversational abilities more closely.

#### Problem Definition

The challenge lies in effectively integrating BERT into QA systems, focusing on improving accuracy, adapting to diverse question types and domains, maintaining scalability and efficiency, and enhancing robustness against ambiguous questions.
- Utilizing BERT’s bidirectional context understanding to enhance QA systems' accuracy.
- Adapting and fine-tuning BERT for diverse QA tasks, understanding the required modifications.
- Balancing scalability and efficiency in QA systems while integrating the computationally intensive BERT model.
- Making QA systems more robust against ambiguous and poorly framed questions using BERT’s capabilities.

#### Data Collection

We utilized the Stanford Question Answering Dataset (SQuAD 2.0), comprising questions and answers based on Wikipedia articles. The dataset was meticulously preprocessed for training our model.

#### Methods and Results
To optimize QA systems with BERT, we have:

- Employed QA dataset SQuAD to cover a broad range of questions.
- Integrated and fine-tuned the pre-trained BERT model to meet specific QA requirements.
- Monitored performance through metrics such as prediction accuracy, F1 score, and latency/responsiveness.
- Explored optimization techniques and hyperparameter tuning to refine the model and prevent overfitting.
- The fine-tuned BERT model demonstrated substantial accuracy in predicting answer spans, with significant F1 scores. 
- Focused on ensuring the model's deployment remains scalable, efficient, and accessible.

Our initial results have shown promising improvements in prediction accuracy and response efficiency. However, we are also observing the complexities involved in balancing model performance with computational demands.

#### Midterm Discussion
Our midterm phase has brought forward insightful findings and challenges. We are exploring BERT's intricate decision-making process to better understand and interpret its capabilities. As we advance, we aim to address the trade-offs between model complexity and responsiveness, given BERT's computational requirements. Our ongoing efforts also include assessing BERT's adaptability for broader, large-scale deployment in diverse QA scenarios.

## Team Contributions

| Student Name           | Contributed Aspects                                 |
|------------------------|-----------------------------------------------------|
| Ayushi Chakrabarty     | Problem Definition, Documentation, Report Writing   |
| Cameron George Potter  | Ideation, Methods, Model Training                   |
| Kshitij Pathania       | Model Evaluation, Results Compilation, Data Visualization |
| Prateek                | Problem Definition, Ideation, Documentation         |
| Sneha Maheshwari       | Problem Definition, Report Writing, Documentation   |
