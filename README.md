SentiNEWS: 
SentiNEWS is an innovative bilingual news summarization and sentiment analysis platform designed for efficient and accessible news consumption. The platform leverages advanced AI technologies to provide concise summaries, sentiment analysis, dynamic images, and text-to-speech capabilities.

Features: 
1) Bilingual Summarization: Generates summaries in English and Hindi for broader accessibility.
2) Sentiment Analysis: Analyzes the emotional tone of news articles using NLTK's VADER.
3) Keyword-Based Image Generation: Creates visually appealing images based on extracted keywords using Hugging Face's Standard Diffusion Model.
4) Text-to-Speech (TTS): Converts summarized text into speech, making news accessible for visually impaired users.
5) Interactive User Interface: Simple and intuitive interface with features like language selection, audio playback, and ROUGE score display.

Problem Statement: 
The overwhelming volume of news and time constraints make it difficult to consume and understand news comprehensively. Current platforms lack:
1) Multilingual summarization.
2) Accessibility features for individuals with disabilities.
3) Effective sentiment analysis and visual engagement.
4) Motivation

SentiNEWS addresses these challenges by creating a platform that empowers:
>> Busy individuals seeking concise news.
>> People with disabilities, especially those visually impaired.
>> Multilingual users who prefer content in Hindi or English.

Methodology:
1) Text Processing and Summarization: Utilizes NLTK, the Newspaper Library, and the BART model (bart-large-cnn).
2) Sentiment Analysis: Employs a lexicon-based approach using NLTK's SentimentIntensityAnalyzer.
3) Keyword Extraction: Extracts top keywords via TF-IDF for better summaries.
4) Dynamic Image Generation: Generates images using Hugging Face's Diffusion Model with GPU acceleration.
5) Text-to-Speech: Converts text into audio using Google Text-to-Speech (gTTS) and plays it via Pygame.
   
Evaluation:
1) Performance Metrics: ROUGE scores (1, 2, and L) evaluate the quality of generated summaries.
2) Sentiment Analysis: Provides a breakdown of positive, negative, and neutral sentiments in articles.
   
Novelty: 
1) Accessibility: TTS feature for visually impaired users.
2) Engagement: Keyword-based dynamic images for better comprehension.
3) Bilingual Content: Expands accessibility by supporting Hindi and English.
4) Advanced Models: Seamless integration of APIs and models for efficient results.

UI:
![image](https://github.com/user-attachments/assets/148b8877-ac30-4a9f-9a0a-2a6830ce2732)
![image](https://github.com/user-attachments/assets/f727e83f-17ef-4b48-8bc4-e7f9c24a7c9c)
![image](https://github.com/user-attachments/assets/3b327eef-eb61-4d0a-8c8f-2ea571aaa7c9)

