# Evaluation-of-LLMs-on-STS-Data
This repo contains a study on performance of LLMs on STS(Semantic Textual Similarity) Data.
For further read please refer to   : Evaluation of General and Domain-Specifc STS Data by LLMs and beyond.pdf

Semantic Text Similarity (STS) is a concept in natural language processing (NLP) that involves evaluating the degree to which two text segments are semantically similar to each other. This can be important for various applications such as information retrieval, text summarization, question answering, and more. Large Language Models (LLMs) like BERT, GPT-2, ROBERTA, and others play a significant role in assessing semantic text similarity.

Here's how LLMs are used to measure Semantic Text Similarity:

Understanding Semantic Meaning:
LLMs are trained on a vast amount of text data, which enables them to understand the contextual meaning of words and phrases. Unlike earlier models that relied heavily on syntactic analysis, LLMs can grasp subtle semantic nuances, allowing them to evaluate the similarity based on meaning rather than just word overlap.
Vector Representations:
LLMs convert text into high-dimensional vector spaces. Each sentence or phrase is represented as a vector. The semantic similarity between texts can then be assessed by comparing these vectors using metrics such as cosine similarity, Euclidean distance, or Manhattan distance.
Fine-tuning on STS Benchmarks:
Although pre-trained on general text, LLMs can be fine-tuned on specific STS datasets to enhance their performance for similarity tasks. During fine-tuning, the model learns to adjust its parameters to minimize the error in predicting the similarity scores provided by human annotators in the training data.
Layer-wise Feature Extraction:
In models like BERT and ROBERTA, each layer of the network captures different types of information. For STS tasks, certain intermediate layers often provide the most useful features for assessing semantic similarity. Researchers can experiment with features from different layers to determine which combinations yield the best results.
End-to-end Learning:
For some tasks, LLMs are used in an end-to-end manner where they directly predict a similarity score. This involves training a model on a labeled dataset where pairs of texts are associated with similarity scores. The model learns to predict these scores as accurately as possible.
Zero-shot and Few-shot Learning:
LLMs like GPT-3 can perform tasks like semantic text similarity in a zero-shot or few-shot setting. This means they can predict similarity without any specific fine-tuning or with minimal examples during inference. This capability is particularly useful when labeled data is scarce.
Overall, LLMs bring a deep understanding of language nuances, making them highly effective for tasks that require an understanding of semantic content, such as Semantic Text Similarity. Your experience with these models on the STS dataset would have given you firsthand insight into how effective they can be for such complex tasks.
