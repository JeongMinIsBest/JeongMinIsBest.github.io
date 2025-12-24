---
layout: single
title: "Research Projects"
permalink: /research/
author_profile: true
---

## 🔬 Research Projects

### 🧬 Dual-Task Single-Cell Perturbation Modeling (MOA + Response) | Nov 2025 - Present
- Developed a unified dual-task framework that jointly learns drug mechanisms-of-action (fₚ) and gene expression responses (fᵣ) from large-scale single-cell perturbation data.
- Used DMSO-treated cells as a control baseline, computing pseudobulk ΔX signatures (drug − DMSO) to isolate true drug-induced transcriptional effects from basal expression and batch noise.
- Represented perturbation effects using a Cell2Sentence-style Transformer, encoding gene-level expression changes as ordered token sequences selected by the magnitude of \|ΔX\|.
- Initialized gene token embeddings with pretrained scGPT embeddings, injecting biological priors and improving generalization across genes, drugs, and cell-line contexts.
- Integrated DrugBank and ChEMBL multi-label target annotations to supervise the target prediction module (fₚ), optimizing BCE-based multi-label learning alongside response modeling with a shared encoder and task-specific heads.
- Conditioned response prediction on structured contextual signals (drug identity, predicted targets, and cell-line information), enabling mechanism-aware modeling of post-treatment expression states.
- Evaluated robustness under out-of-distribution settings (unseen drugs and unseen cell lines), analyzing when mechanism-aware supervision improves prediction accuracy and interpretability.
- Extended the framework toward a Filter-and-Rank inference pipeline to prioritize candidate drugs that reverse disease-associated expression signatures toward healthy (DMSO-like) states.
- 🔗 GitHub Repository is now in preparation
<br/>

### 🤗 Hugging Face Transformer Fine-tuning | Sep 2025  
- Explored **transfer learning** techniques with Hugging Face Transformers to adapt pre-trained models for Korean NLP tasks.  
- Fine-tuned **KoBERT, DistilBERT, and GPT-2** on custom Korean datasets, addressing both **emotion classification** and **dialogue generation**.  
- Experimented with multiple training strategies, including **Supervised Fine-tuning (SFT)**, **early stopping**, and **hyperparameter tuning**.  
- Evaluated model performance using accuracy and qualitative assessments of generated outputs.  
- Gained practical experience in **adapting large pre-trained models** to domain-specific tasks and comparing their effectiveness across architectures.  
- [🔗 GitHub Repository](https://github.com/JeongMinIsBest/AIFFEL_quest_rs/tree/main/GoingDeeper/GD1516)  
<br/>

### 🔠 Mini-BERT Model Compression | Sep 2025  
- Investigated methods for **compressing large-scale NLP models** to enable efficient on-device inference.  
- Implemented **knowledge distillation** from BERT to a compact student model, reducing model size while retaining accuracy.  
- Applied **parameter reduction techniques** (e.g., pruning and low-rank factorization) to further optimize resource usage.  
- Conducted **benchmarks on text classification tasks**, analyzing the trade-offs between computational efficiency and predictive performance.  
- Gained insights into the practical deployment of **lightweight language models** in resource-constrained environments.   
- [🔗 GitHub Repository](https://github.com/JeongMinIsBest/AIFFEL_quest_rs/tree/main/GoingDeeper/GD1314)
- [📄 View Full Report (PDF)](/files/Width Matters Efficient Scaling of Compact BERT Models.pdf)  
<br/>

### 🤖 Classical Machine Learning and Deep Learning Fundamentals | Aug 2025
- Completed an introductory project to **build foundational skills in machine learning and deep learning**.  
- Implemented core ML algorithms (**SVM, Random Forest, Logistic Regression**) on structured datasets, practicing feature engineering and model selection.  
- Designed and trained **basic neural networks** using TensorFlow and PyTorch to compare performance with classical ML approaches.  
- Evaluated models through **cross-validation and performance metrics**, gaining a solid understanding of trade-offs between classical ML and DL methods.  
- [🔗 GitHub Repository](https://github.com/JeongMinIsBest/AIFFEL_quest_rs/tree/main/GoingDeeper/GD0304)  
<br/>

### 🗨️ NLP Pipeline and Korean Chatbot | Aug 2025  
- Developed a Korean **dialogue system prototype** inspired by the Cornell Movie Dialogs dataset, aiming to explore open-domain chatbot capabilities.  
- Built preprocessing pipelines, including **SentencePiece tokenization, subword vocabulary construction, and text cleaning**.  
- Implemented and trained baseline models (**Seq2Seq and Transformer-based architectures**) for response generation.  
- Conducted evaluation using **BLEU and BERTScore**, and analyzed the effects of different decoding strategies (greedy, beam search, sampling).  
- [🔗 GitHub Repository](https://github.com/JeongMinIsBest/AIFFEL_quest_rs/tree/main/GoingDeeper/GD0910)  
<br/>

### 🌳 ESG-based Credit Scoring Model for Small Businesses | Jun 2025 - Aug 2025
- Developed an **ESG-integrated credit scoring model** to improve financial accessibility for small businesses in Korea.  
- Incorporated **non-financial ESG indicators** (energy savings, social contributions, privacy protection) alongside traditional credit factors.  
- Applied **XGBoost and CatBoost** for predictive modeling, achieving higher fairness and interpretability.  
- Proposed policy implications for regional banks to enhance financial inclusion.  
- [📄 View Full Report (PDF)](/files/MyResearchPoster.pdf)
<br/>

### 🏦 Shinhan Big Data Hackathon: ESG Financial Product Design | Oct 2024 - Nov 2024  
- Defined a **Green Consumption Index** using **PCA and clustering techniques** on consumption data.  
- Identified customer segments based on ESG consumption behaviors.  
- Designed a new **green savings account product**, linking financial incentives to sustainable consumption.  
- Proposed marketing and policy strategies to attract **young customers (20s–30s)** to ESG products.  
- [🔗 Notion Page](https://www.notion.so/Green-Consumption-Savings-Account-ESG-Financial-Product-Proposal-1d1fb4f8761581369fb9c56899e5494a?source=copy_link)
<br/>

### 📚 Shakespeare Text Mining: Tragedies vs. Comedies | Dec 2023
- Performed **computational text analysis** on Shakespeare’s tragedies and comedies to explore linguistic and thematic differences.  
- Quantified the **frequency of “death” and related semantic fields**, highlighting genre-specific lexical patterns.  
- Applied **sentiment analysis** to compare emotional tones across the two genres.  
- Showcased the integration of an **English Literature background** with **NLP and Data Science techniques**, bridging the gap between humanities and computational research.  
- [📄 View Full Report (PDF)](/files/Data_Analysis.pdf)
<br/>
<br/>

## 📂 Research Themes  
My work centers on building language technologies that are efficient, reliable, and accessible—particularly for multilingual and low-resource environments. These research directions are reflected in four interconnected themes:
  
1. **Efficient NLP and Lightweight Language Models**
I develop and fine-tune models for classification, dialogue generation, and multilingual tasks, with a focus on parameter-efficient adaptation, model compression, and scalable deployment. This includes experimenting with knowledge distillation and PEFT techniques to reduce model size while preserving performance.
  
2. **Multilingual and Low-Resource Natural Language Processing**
Much of my research examines how representation learning and cross-lingual transfer can improve performance in languages with limited annotated data. This includes analyzing tokenization challenges, modeling morphologically rich languages, and designing systems that generalize across diverse linguistic structures.
  
3. **Reliability and Responsible Generative Systems**
I explore methods for improving factual consistency, controllability, and safety in generative and dialogue systems. This direction connects technical model improvements with broader goals of fairness, interpretability, and responsible use of AI in real-world decision-making contexts.
  
4. **Multimodal and Socially Impactful AI**
Recently, I have extended my work to include vision-language and multimodal learning, investigating how perceptual grounding can enhance model understanding and support practical applications such as sustainable finance, public-facing AI services, and computational humanities research.
  
Collectively, these themes reflect my broader goal: **developing efficient and socially meaningful NLP systems that bridge human language, machine intelligence, and equitable access to technology.**
<br/>
<br/>
