# 🤖 Sentiment Analysis: KAI Tumbler Viral Issue using IndoRoBERTa

## 📌 Project Overview
Proyek ini menganalisis sentimen masyarakat di platform X (Twitter) terkait isu viral hilangnya tumbler penumpang di kereta KAI. Menggunakan model **IndoRoBERTa**, proyek ini mengklasifikasikan opini publik menjadi tiga kategori: **Negatif, Netral, dan Positif** untuk memahami persepsi masyarakat terhadap penanganan kasus oleh pihak KAI.

## 🚀 Key Features
*   **Data Scraping**: Mengambil 900+ data real-time menggunakan `tweet-harvest`.
*   **IndoRoBERTa Classification**: Menggunakan model pre-trained `w11wo/indonesian-roberta-base-sentiment-classifier` yang telah di-fine-tune untuk konteks bahasa Indonesia.
*   **Automated Feature Extraction**: Memanfaatkan mekanisme *bidirectional self-attention* dari arsitektur Transformers.
*   **Visual Insight**: Analisis distribusi sentimen dan WordCloud untuk identifikasi isu dominan (seperti kata kunci "dipecat" dan "petugas").

## 🛠️ Tech Stack & Tools
*   **Language**: Python
*   **Libraries**: Transformers (HuggingFace), Scikit-Learn, Pandas, Matplotlib, Seaborn.
*   **Scraping Tool**: Node.js Tweet-Harvest.

## 📊 Evaluation Results
*   **Accuracy**: ~80%
*   **Insight**: Sentimen **Negatif mendominasi (58%)**, mencerminkan kritik tajam publik terhadap kebijakan sanksi internal KAI yang dianggap tidak proporsional.


**Developed by Muhammd Fahri Novarian**  
