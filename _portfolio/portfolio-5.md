---
title: "Capstone Project: AI Emotional Support Service for the Socially Vulnerable"
excerpt: "Developed an AI-powered diary service that performs emotion classification and summarization on daily journals to support socially vulnerable groups. Integrated KoBERT and KoBART models for sentiment analysis and summarization, deployed via a mobile app prototype.<br/><img src='/images/portfolio/capstone.png'>"
collection: portfolio
---

## 💙 AI Emotional Support Service for the Socially Vulnerable
*Team Project | Sep 2024 – Dec 2024*  
<br/>

- Proposed and built **“DailyMood”**, an AI-based emotional diary analysis service designed to support **socially vulnerable groups (youth, elderly, and isolated individuals)**.  
- Implemented a **KoBERT-based emotion classification model** with SentencePiece tokenizer, AdamW optimizer, and CrossEntropyLoss, fine-tuned on AI Hub dialogue datasets (6-class emotion taxonomy: Happiness, Sadness, Anger, Fear, Surprise, Disgust).  
- Integrated a **KoBART-based summarization model**, fine-tuned on Korean summarization datasets, to generate concise summaries of user diaries.  
- Applied **hyperparameter optimization** (batch size 64, learning rate 3e-5, gradient clipping, linear scheduler) and experimented with **Mixed Precision Training** for efficient GPU utilization.  
- Designed the **system pipeline**: diary input → backend transfer → NLP-based summarization & sentiment classification → frontend visualization.  
- Developed a **Flutter + Spring Boot prototype app**, displaying diary entries, emotion statistics (weekly/monthly), and personalized summaries.  
- Built **data pipelines** for preprocessing (tokenization, dataset augmentation, and JSON → CSV conversion) to handle over **180K+ Korean text samples**.  
- Conducted **performance comparison** between different training setups, analyzing model accuracy vs. real classification quality, and selected the best performing configuration.  
- Final prototype showcased via **interactive demo video** and **team presentation**, highlighting both technical contributions and societal impact.
<br/>

![capstone](https://github.com/user-attachments/assets/a630c9b0-b0a9-4c3d-92c3-f886bfa10b71)
![캡스톤디자인_hello world 발표자료_page-0003](https://github.com/user-attachments/assets/c76da402-9c12-404d-9aff-11b5e6bd20eb)
![캡스톤디자인_hello world 발표자료_page-0006](https://github.com/user-attachments/assets/71ed56fb-946a-4415-9c47-b6eda61e02e9)
![캡스톤디자인_hello world 발표자료_page-0009](https://github.com/user-attachments/assets/df361f7c-fdc8-4ec8-894c-b22722fc42d4)
![캡스톤디자인_hello world 발표자료_page-0013](https://github.com/user-attachments/assets/58374106-bb1e-43b4-9894-7a886c855011)
![캡스톤디자인_hello world 발표자료_page-0014](https://github.com/user-attachments/assets/34ade22b-18e8-4f98-b667-6e0b00daec77)
![캡스톤디자인_hello world 발표자료_page-0016](https://github.com/user-attachments/assets/bdc3e0f1-fa3e-4490-bcdb-159f9100c718)
![캡스톤디자인_hello world 발표자료_page-0017](https://github.com/user-attachments/assets/5c71a5a6-4087-4486-8a9f-2de2f3152a04)
![캡스톤디자인_hello world 발표자료_page-0018](https://github.com/user-attachments/assets/13042a61-49ed-4a88-92c5-f6fe7611c380)
![캡스톤디자인_hello world 발표자료_page-0019](https://github.com/user-attachments/assets/1c592a87-58c4-45db-aa77-02fcd9bbb43a)
![캡스톤디자인_hello world 발표자료_page-0020](https://github.com/user-attachments/assets/77248bb0-378c-4221-93c8-6a7ed786ecb4)
![캡스톤디자인_hello world 발표자료_page-0021](https://github.com/user-attachments/assets/21f70671-0060-448c-b788-a4f1ae7891d3)
![캡스톤디자인_hello world 발표자료_page-0022](https://github.com/user-attachments/assets/9113789b-03fc-4fd7-b792-ede2862d527b)
<br/>
