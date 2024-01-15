# Health Claim Analysis using Natural Language Processing

## Project Overview
This project explores the application of NLP techniques in health claim analysis across different domains. The primary focus was on cross-domain classification, zero-shot classification, and clustering analysis. It aimed to categorize health claim strength in PubMed research papers and health news headlines, and to identify common health topics in news headlines.

## Objectives
- **Cross-Domain Classification**: Comparing SVM and BERT models for categorizing health claim strength.
- **Zero-Shot Classification**: Employing Hugging face zero-shot classification for predicting causal claim strength.
- **Clustering Analysis**: Using SBERT+kMeans and BERTopic for revealing common health topics.

## Methodology
1. **Cross Domain Classification**: Analyzed using Unigram TFIDF vectorizer, SVM, and BERT models.
2. **Zero Shot Classification**: Implemented on two distinct datasets to evaluate classifier consistency and effectiveness.
3. **Clustering**: Conducted using SBERT+kMeans and BERTopic models to identify prevalent health topics.

## Results
- **Cross Domain Classification**: BERT outperformed SVM in terms of accuracy and F-1 Macro scores.
- **Zero Shot Classification**: Showed varying precision, recall, and F-1 scores across different categories.
- **Clustering Analysis**: SBERT+kMeans and BERTopic effectively clustered data into coherent health-related topics.

## Technologies Used
- **NLP Models**: SVM, BERT, Hugging Face Zero-shot classifier.
- **Clustering Algorithms**: SBERT+kMeans, BERTopic.

## Conclusion
The study highlights the effectiveness of NLP in health claim analysis across different domains. BERT's superior performance in classification tasks and the insightful clustering of health news topics demonstrate the potential of NLP techniques in extracting meaningful patterns and insights from complex textual data.
