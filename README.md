# Sentiment Analysis of Pospay App Reviews using BERT

This project analyzes user sentiment toward the **Pospay** application using the **BERT deep learning method**. It is based on 16,760 user reviews from the Google Play Store and represents (to our knowledge) the **first study applying BERT for sentiment analysis** of Pospay reviews in Indonesia.

## 📝 Abstract

E-money usage in Indonesia has grown significantly due to increasing internet penetration and smartphone adoption. Digital transactions are becoming more common, with platforms like GoPay, OVO, and Dana leading the market. The government and financial institutions actively support this shift through regulations and initiatives.

This study applies BERT to classify user sentiment in Pospay reviews. The model captures subtle nuances in informal Indonesian expressions—such as "gk" (abbreviation of *nggak*)—that traditional models often miss. Our results demonstrate strong performance:

- **Precision**: 0.82 (negative), 0.93 (positive)  
- **Recall**: 0.92 (negative), 0.93 (positive)

The findings suggest that PT Pos Indonesia should prioritize:
- Improving app **stability and security**
- Enhancing **transaction processing**
- Strengthening **customer service**
- Issuing **regular updates** to meet user expectations

## 📁 Dataset

- Source: Google Play Store reviews for "Pospay"
- Total: 16,760 reviews (collected up to [insert date])

_(Note: Due to Google Play Store scraping restrictions, dataset availability may vary. See `data/` or `data/README.md` for more info.)_

## 🧠 Methodology

- Model: Pre-trained **IndoBERT** fine-tuned for binary sentiment classification
- Preprocessing: Cleaning, stopword removal, normalization
- Tools: Python, HuggingFace Transformers, TensorFlow/PyTorch

## 📊 Results

| Sentiment | Precision | Recall |
|-----------|-----------|--------|
| Negative  | 0.82      | 0.92   |
| Positive  | 0.93      | 0.93   |
----------------------------------


