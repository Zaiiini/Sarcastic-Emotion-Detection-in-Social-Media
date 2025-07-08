# Sarcastic-Emotion-Detection-in-Social-Media
A real-world NLP project that detects sarcasm and emotions from social media texts 

Accurately capturing both the emotional tone and the sarcastic intent in text is crucial for building more intuitive chatbots, enhancing sentiment analysis systems, and aiding mental health monitoring. My objective was to design a single transformer-based model that can recognize six core emotions (Joy, Sadness, Love, Anger, Fear, and Surprise) while also identifying sarcasm in social media.

# Dataset Used
Reddit News Headlines: Binary sarcasm labels.
DAIR-AI Emotion: Six emotion categories.

# Model:
Labeled datasets for sarcasm (news headlines) and emotion (social text) were merged, preprocessed, and tokenized with appropriate label masking. 
A shared DistilBERT encoder was trained, ensuring balanced learning and optimal generalization across both tasks.

 Metric	        Sarcasm	      Emotion
Accuracy      	90.00%      	93.00%
Precision	      90.00%	      93.80%
Recall	        90.00%      	90.50%
F1-Score      	90.00%	      91.60%

