# TopsisPretrainedModels
# Assignment: Applying TOPSIS for Selecting the Best Pre-Trained Model

## Objective
The goal of this assignment is to apply the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method to determine the best pre-trained model for a given NLP task.

## Task Distribution Based on Roll Number
- **Text Summarization**: Roll numbers ending with **0 or 5**
- **Text Generation**: Roll numbers ending with **1 or 6**
- **Text Classification**: Roll numbers ending with **2 or 7**
- **Text Sentence Similarity**: Roll numbers ending with **3 or 8**
- **Text Conversational**: Roll numbers ending with **4 or 9**

## Steps to Follow

### 1. Select Pre-Trained Models
Choose at least 3-5 pre-trained models for your assigned NLP task. Some popular models include:
- **Text Summarization**: BART, T5, Pegasus
- **Text Generation**: GPT-3, GPT-2, XLNet
- **Text Classification**: BERT, RoBERTa, DistilBERT
- **Text Sentence Similarity**: SBERT, USE, BERTScore
- **Text Conversational**: DialoGPT, BlenderBot, ChatGPT

### 2. Define Evaluation Criteria
Determine the performance metrics to compare models. Example criteria:
- Accuracy / BLEU Score / ROUGE Score
- F1 Score / Precision / Recall
- Latency (Inference Time)
- Model Size
- Computational Cost (GPU/Memory Usage)

### 3. Data Collection & Model Evaluation
Run experiments using a dataset relevant to your assigned NLP task and collect metric values for all selected models.

### 4. Apply TOPSIS Method
TOPSIS ranks alternatives based on their similarity to an ideal solution. Follow these steps:
- Normalize the decision matrix
- Calculate weighted normalized matrix
- Identify the ideal best and worst solutions
- Compute Euclidean distances to ideal best and worst solutions
- Calculate TOPSIS score and rank models accordingly

### 5. Results & Visualization
- Present results using tables and graphs.
- Provide explanations of ranking and final selection.
- Include all calculations in a structured format.

## References
- [TOPSIS Method Explanation](https://en.wikipedia.org/wiki/TOPSIS)
- [Hugging Face Models](https://huggingface.co/models)
