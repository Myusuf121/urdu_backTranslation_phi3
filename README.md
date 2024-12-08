# Breaking Language Barriers: Improved Urdu Speech Emotion Sentiment Analysis with Back Translation

## What’s Unique About This Project?
While most sentiment analysis tasks rely on static datasets, this project introduces a dynamic approach to improve the quality and quantity of data for training. It takes three key steps to achieve its goal:

[Dataset Link:] (https://github.com/siddiquelatif/urdu-dataset?tab=readme-ov-file)
## 1. Expanding the Dataset with Back Translation
Back translation is used as a data augmentation technique to generate diverse and contextually accurate Urdu samples. The process involves:

- Translating existing data into another language (e.g., English) and back into Urdu using MarianMT models.
- Ensuring semantic integrity while introducing subtle variations that enrich the dataset.
- This step effectively doubles the dataset, capturing more linguistic nuances and idiomatic expressions unique to Urdu.

## 2. Merging Original and Extended Datasets
The extended dataset is combined with the original to create a robust training set that represents a wider range of emotions and contexts. This enriched dataset provides a solid foundation for fine-tuning the Phi3 model.

## 3. Evaluating the Impact on Sentiment Classification
The project evaluates the performance of the fine-tuned Phi3 model on both the original and extended datasets. By comparing key metrics like:

- Accuracy: How well the model classifies emotions.
- Precision and Recall: The model’s sensitivity to emotional nuances.
- F1-Score: A balanced measure of performance.
- The results offer actionable insights into the benefits of data augmentation for low-resource languages.

## Why This Matters
Urdu, spoken by millions, has immense cultural and linguistic richness but often lacks the resources to train state-of-the-art NLP models effectively. By combining data augmentation techniques with advanced models like Phi3, this project demonstrates how machine learning can break through resource barriers and create more inclusive technologies.

## Who Should Read This?
**NLP Developers:** Discover how to apply back translation to boost dataset diversity and quality.
**Researchers:** Learn about the impact of augmented datasets on sentiment classification for low-resource languages.
**AI Enthusiasts:** Explore the power of combining modern NLP tools with creative problem-solving techniques.
This project isn’t just about numbers — it’s about making sentiment analysis accessible, scalable, and effective for languages like Urdu. If you’re ready to dive into the next frontier of multilingual NLP, this is your starting point.
