# 👋 Hi, I'm Harshvardhan Sekar

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=0969DA&center=true&vCenter=true&random=false&width=600&lines=Credit+Risk+Analyst+%7C+ML+Engineer;%2418B%2B+Portfolio+Experience+at+HSBC;UIUC+MS+Data+Science+%7C+3.94+GPA;Vision-Language+Models+%7C+RAG+Pipelines;CECL%2FIFRS-9+%7C+Loss+Forecasting)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harshvardhan-sekar/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)](https://harshvardhan-sekar-portfolio.vercel.app/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sekar6@illinois.edu)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/harshvardhan-sekar)

![Profile Views](https://komarev.com/ghpvc/?username=harshvardhan-sekar&label=Profile%20Views&color=0e75b6&style=flat)

---

## 🚀 About Me

> **"I've forecasted losses on $18 billion. Now I'm building AI that reads comics and answers medical questions."**

I'm a **Data Scientist** and **Credit Risk Analyst** pursuing my **M.S. in Information Management (Data Science Track)** at the **University of Illinois Urbana-Champaign** with a **3.94 GPA**. Previously, I spent **2 years at HSBC** in Bangalore working on US Loss Forecasting and Credit Decision Modeling for consumer mortgage portfolios exceeding **$18 billion** and credit card portfolios over **$230 million**.

My work sits at the intersection of **quantitative finance**, **machine learning**, and **generative AI** — from building CECL/IFRS-9 compliant ECL frameworks to fine-tuning vision-language models on NVIDIA H200 GPUs.

---

## 💼 Professional Experience

### 🏦 HSBC — Decision Science Analyst
**Bangalore, India | Aug 2022 – Jun 2024**

#### US Loss Forecasting (RE1/RE2 Mortgages)
- 📊 Managed **$18B+ mortgage portfolio** ECL analytics
- 📈 Built 8-quarter forecasting models using mean-reversion
- 🔄 Tracked roll rates (30→60, 60→90, 90→120+ DPD)
- 📉 Monitored **8.7% Capital Adequacy Ratio** under stress

#### Credit Decision Modeling (Cards)
- 💳 Managed **$230M+ credit card portfolio**
- ✅ Validated Gini, KS, PSI metrics (<10% QoQ deviation)
- 🎯 Monitored behavioral scorecards for 230K+ accounts
- 📊 Geographic analysis of 180+ DPD receivables by state

#### Key Achievements
- 🏆 Developed **probability-weighted ECL scenarios** (80% Central, 10% Upside, 10% Downside)
- 📊 Built **Excel-to-PowerPoint VBA automation** for Credit Review Forum presentations
- 🔬 Applied **CECL (ASC 326)** and **IFRS-9** frameworks across portfolio segments

---

## 🎓 Education

### University of Illinois at Urbana-Champaign
**M.S. Information Management (Data Science Track)** | GPA: **3.94/4.00**

*Aug 2024 – May 2026*

**Relevant Coursework:** Applied Machine Learning • Text Mining & NLP • Data Warehousing & BI • Statistical Modeling

**Certifications:**
- 📜 Deep Learning Specialization (DeepLearning.AI)
- 📜 Machine Learning (Stanford Online)

---

## 🔬 Featured Projects

### 🏥 Medical Question-Answering RAG Pipeline
*Retrieval-Augmented Generation for Clinical NLP*

[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/harshvardhan-sekar/medical-qa-rag)

> Built a production-grade RAG system on NIH's **MedQuAD dataset (16,407 QA pairs)** with a groundbreaking discovery in retrieval strategy.

| Metric | Achievement |
|--------|-------------|
| **ROUGE-L** | 0.293 (102% improvement over baseline) |
| **BERTScore F1** | 0.869 |
| **Q→Q Recall@10** | 99.8% vs 86.7% (Q→A) |

🔑 **Key Innovation:** Discovered **Question-to-Question retrieval outperforms Q-to-Answer** — a 151.7% improvement that challenges conventional RAG design.

**Tech Stack:** `BioBART` `SciFive` `Sentence-BERT` `BM25` `RRF Fusion` `PSC Bridges-2 GPUs`

<details>
<summary>📊 Click to expand Technical Details</summary>

- **Hybrid Retrieval:** BM25 + Dense (SBERT) with Reciprocal Rank Fusion
- **CUI-based Splitting:** Prevented data leakage across 5,125 diseases
- **Error Analysis:** Cross-disease hallucination detection & mitigation
- **Infrastructure:** HPC training on PSC Bridges-2 V100/H100 GPUs

</details>

---

### 🎨 Beyond the Frame: Multimodal COMICS Cloze
*Vision-Language Models for Comic Panel Prediction*

[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/harshvardhan-sekar/comics-cloze)

> Fine-tuned **LLaVA-OneVision-7B** on the **COMICS dataset (1.2M panels)** to predict missing panel descriptions from narrative context.

| Metric | Zero-Shot | Fine-Tuned | Improvement |
|--------|-----------|------------|-------------|
| **ROUGE-1** | 0.349 | **0.439** | +25.9% |
| **ROUGE-2** | 0.071 | **0.133** | +87.4% |
| **ROUGE-L** | 0.179 | **0.232** | +30.1% |
| **BERTScore** | 0.854 | **0.878** | +2.8% |

🔑 **Key Innovation:** Integrated **Stable Diffusion** for generating panel images from predicted descriptions, evaluated via CLIPScore.

**Tech Stack:** `LLaVA-OneVision-7B` `LoRA Fine-tuning` `Stable Diffusion` `Vertex AI Gemini` `NCSA Delta H200 GPUs`

<details>
<summary>🏗️ Click to expand Pipeline Architecture</summary>

```
Context Panels (1-5) → LLaVA (Fine-tuned) → Scene Description → Stable Diffusion + LoRA → Generated Panel
                    ↓
        OCR-Extracted Dialogue
```

- **Ground Truth Generation:** Vertex AI Gemini Batch API for 54K+ sequences
- **Training:** NCSA Delta H200 GPUs with attention masking
- **Evaluation:** ROUGE, BLEU, BERTScore, CLIPScore

</details>

---

### 📈 LendingClub Credit Risk Portfolio Analysis
*CECL-Compliant ECL Framework*

[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/harshvardhan-sekar/lending-club-credit-risk)

> End-to-end credit risk analytics on a **$195M LendingClub portfolio** with PD, LGD, and EAD models.

| Model | Performance |
|-------|-------------|
| **EAD MAE** | $5,283 |
| **LGD MAE** | 0.064% |
| **ECL Error** | 24.3% |

**Components:**
- 📊 **PD Model:** XGBoost with WoE transformation
- 💰 **LGD Model:** Two-stage beta regression on recovery rates
- 📈 **EAD Model:** Credit Conversion Factor (CCF) regression
- 📉 **Scenario Weighting:** CECL-compliant probability-weighted ECL

**Tech Stack:** `XGBoost` `SHAP` `Lifelines` `Tableau` `scikit-learn`

---

### 🎬 Red Carpet Analytics: Oscar Prediction
*Entertainment Analytics with XGBoost*

[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/harshvardhan-sekar/red-carpet-analytics)
[![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?style=flat-square&logo=tableau)](https://public.tableau.com/app/profile/harshvardhan.sekar/viz/CanDataPredicttheOscarsATableauVisualizationofXGBoostInsights)

> ML classifier predicting Oscar wins across **1,270 nominations (1928-2024)**.

| Metric | Random Forest | XGBoost |
|--------|---------------|---------|
| **Recall (Winners)** | 21% | **80%** (+280%) |
| **Accuracy** | 79% | ~80% |

🔑 **Key Insight:** Threshold tuning (0.4) + class balancing achieved **80% recall** — catching 4 out of 5 actual winners.

**Tech Stack:** `XGBoost` `Random Forest` `Tableau` `Power BI`

---

### 🫁 Pneumonia Detection using CNNs
*Medical Imaging with Transfer Learning*

> Built CNN classifier on **5,400+ chest X-rays** for pneumonia/COVID-19 detection.

| Approach | Accuracy |
|----------|----------|
| Baseline CNN | 70% |
| **Transfer Learning** | **88%+** |

**Models:** `VGG16` `DenseNet-201` `EfficientNet-B0`

---

## 🛠️ Tech Stack

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Machine Learning & AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗_Hugging_Face-FFD21E?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logo=xgboost&logoColor=white)

### NLP & Vision
![LLaVA](https://img.shields.io/badge/LLaVA-FF6B6B?style=for-the-badge)
![BioBART](https://img.shields.io/badge/BioBART-4ECDC4?style=for-the-badge)
![Stable Diffusion](https://img.shields.io/badge/Stable_Diffusion-B762C1?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)

### Cloud & HPC
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![NCSA Delta](https://img.shields.io/badge/NCSA_Delta-13294B?style=for-the-badge)
![PSC Bridges](https://img.shields.io/badge/PSC_Bridges--2-003594?style=for-the-badge)

### Data & BI
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

---

## 📊 GitHub Stats

![Harsha's GitHub Stats](https://github-readme-stats.vercel.app/api?username=harshvardhan-sekar&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=harshvardhan-sekar&layout=compact&langs_count=8&theme=tokyonight)

[![GitHub Streak](https://streak-stats.demolab.com?user=harshvardhan-sekar&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

---

## 🏆 Highlights

| 💼 Industry | 🎓 Academic | 🔬 Research |
|:-----------:|:-----------:|:-----------:|
| **$18B+** Portfolio Management | **3.94** GPA at UIUC | **102%** RAG Improvement |
| **2 Years** HSBC Credit Risk | **Stanford/DeepLearning.AI** Certs | **111.7%** ROUGE-2 Gain |
| **CECL/IFRS-9** Compliance | **7+** End-to-End Projects | **Q→Q** Retrieval Discovery |

---

## 📫 Let's Connect!

I'm actively seeking **2026 Full-Time** opportunities in **Credit Risk Analytics**, **Data Science**, and **ML Engineering** where I can leverage my unique combination of quantitative finance expertise and cutting-edge AI skills.

| 📧 Email | 🔗 LinkedIn | 🌐 Portfolio | 📍 Location |
|:--------:|:-----------:|:------------:|:-----------:|
| [sekar6@illinois.edu](mailto:sekar6@illinois.edu) | [harshvardhan-sekar](https://www.linkedin.com/in/harshvardhan-sekar/) | [Portfolio](https://harshvardhan-sekar-portfolio.vercel.app/) | Urbana, IL |

---

### ⭐ If you found my work interesting, consider giving my repositories a star!

![Wave](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer)
