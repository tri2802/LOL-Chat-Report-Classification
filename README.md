# LOL-Chat-Report-Classification
Given the rising false reports in League of Legends game system, my goal aims to develop merged pipeline hosting two models:
- an Naive Bayes - Support Vector Machine (NBSVM) for sentiment (binary) classification
- Fine-tune HF's Albert for multiclass categorization
The message that is reported would be send to analyze the sentiments (positive/negative). If negative, it will be further send to Albert to classify to the 5 report categories of League of Legengs
