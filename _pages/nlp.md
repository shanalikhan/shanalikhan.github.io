---
layout: page-custom
title: NLP and Gen. AI Contributions
permalink: /nlp
subtitle: .
img: assets/img/12.jpg
social: true
---

Here are selected projects showcasing the application of NLP and Generative AI technologies:


#### Call Center AI Agent (Chatbot)
1. Designed and developed a chatbot to assist call center advisors in retrieving quick, accurate answers during calls, significantly reducing hold times and improving overall customer satisfaction.
2. Built a Retrieval-Augmented Generation (RAG) knowledge base by extracting data from websites, Word documents, PDFs, and embedded images using the Unstructured library. Applied data cleansing techniques and transformed unstructured data into semi-structured formats through rule-based approaches.
3. Implemented Personally Identifiable Information (PII) detection and masking in documents using AWS Comprehend, integrated with an SQL database.
4. Conducted efficient data chunking using LangChain, generating multilingual vector embeddings with OpenAI and image embeddings with OpenAI CLIP, and stored these in Pinecone alongside metadata for effective retrieval.
5. Applied prompt engineering techniques and developed LangChain agent chains leveraging LLM function calls to enhance chatbot functionality.
6. Evaluated the RAG model using conventional retriever benchmarks such as Precision (P), Recall@k (R@k), and prompt-based assessments using frameworks like RAGAS. Deployed the solution as a Flask application within Dockerized containers, hosted on Azure App Service

<hr>

#### IT & HR Support Automation
1. Designed and implemented an extractive Question Answering (QA) system for IT and HR support, enabling employees to retrieve answers without contacting support teams.
2. Processed Word documents and PDFs using advanced NLP techniques to convert unstructured data into structured formats.
3. Leveraged the Haystack framework to build a document store with ElasticSearch and generated embeddings using BM25 variants, ELMo, and S-BERT. Evaluated retrieval performance using Recall@k (R@k) and Precision@k (P@k) metrics.
4. Fine-tuned and evaluated transformer models like BERT, RoBERTa, and LongFormer on SQuAD-based datasets for optimal extractive QA performance.
5. Developed an embedding-based retrieval model to identify relevant documents and integrated it with an extractive LongFormer model for answer generation.Deployed the end-to-end QA pipeline as an Azure Machine Learning API for seamless scalability and accessibility.
6. Enabled business to save cost for hiring HR & AI support guys and lead to employee satisfaction by generating prompt resolution.


#### Call Center Quality Audit Automation
1. Enabled proactive agent evaluation in call centers, improving customer satisfaction and reducing manual evaluation effort by up to 70%.
2. Preprocess the long audio by performing voice activity detection and and fine-tuned the Wav2Vec2 model for Singlish, achieving a 15% Word Error Rate (WER) using an incremental learning approach for Automatic Speech Recognition (ASR).
3. Designed a machine learning pipeline to extract user sentiments, behaviors, and rule-based criteria for agent evaluation, leveraging metric learning for in-depth analysis and alignment with historical data.
4. Deployed the solution on-premises using Docker containers for secure and efficient execution.


<hr>


#### Medical Transportation Price Optimization using Demand Forecasting
1. Developed a solution for Non-Emergency Medical Providers to deliver optimized price quotes to transportation providers by analyzing regional demand patterns.
2. Conducted Exploratory Data Analysis (EDA) and feature selection using AWS Data Wrangler and AWS Redshift for efficient data preprocessing.
3. Built demand forecasting models with AWS Forecast, optimizing pricing strategies based on demand trends and generating quarterly ROI insights.
4. Enabled 6-month trip forecasting and profitability margin analysis for providers, supporting contract restructuring to reduce overall operational costs.

<hr>

#### Information Retrieval System 
1. Trained models for Document Classification.
2. Applied Information Retrieval techniques (NER, etc.) to extract relevant entities and fields from documents. Automated model maintenance using Azure ML pipelines to evaluate new data and deploy new models after evaluation based on new data.
3. Fine-tuned Tesseract OCR for certain documents and utilized Google OCR.
