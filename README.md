# CLASSIFICATION OF 'TRIGGERING' CONTENT 
# ON SOCIAL MEDIA

## Overview
  This project was completed during my time in CSCI 4152 - Natural Language Processing. It considersthe problem of automating the assignment of trigger warning labels to   social media posts using traditional classifiers and machine learning techniques.

  ## Research Project Report
  The full paper can be found here: [report.pdf](https://github.com/ksek87/trigger_warning_classification/blob/main/report.pdf)
  ### Abstract
  The growth of social media has changed the way people discuss sensitive topics, making it difficult 
  for people with a history of trauma or Post Traumatic Stress Disorder (PTSD) to avoid content that 
  may be triggering. As a result, the need to automatically warn users of sensitive content to suit 
  user preferences has become increasingly important to promote safety and inclusion online. In this 
  project, we collected text-based posts from communities about sensitive topics and mental health 
  topics from the platform Reddit. We then analyzed these posts using traditional and deep learning 
  classification methods to investigate whether we could accurately identify an appropriate trigger 
  warning for the content. We employ four classifiers to establish a baseline for classifying social 
  media posts under one of 9 identified trigger warning labels using our new dataset. Our 
  experiments determine that this task is well captured by more complex models, with the Linear 
  SVC and CNN models yielding well-rounded results. We discuss the implications of the models’ 
  performance and any difficulties in selecting the correct theme in this complex task. We believe 
  that these results indicate that it would be possible to build a system to automate the labelling of 
  triggering content with simple model architectures to support reduced computational requirements 
  in some cases. This work appears to be the first attempt at automating trigger warnings using 
  natural language processing techniques. We hope that this study brings attention to the topic for 
  further research that will allow for further inclusivity and harm reduction in online spaces
  
 ## Dataset 
  - The dataset for this project was collected from Reddit using the [data_scraping_processing](https://github.com/ksek87/trigger_warning_classification/blob/main/src/data_scraping_processing.ipynb) notebook. 
  - For my research, the dataset comprises of 361,641 reddit posts upon completion of pre-processing (too large for github). 

## Models
- Linear SVC Classifier 
- Multinomial Naive Bayes Classifer
- Feed Forward Neural Network
- Convolutional Neural Network

Check out my experiments in [here](https://github.com/ksek87/trigger_warning_classification/blob/main/src/pre_processing_and_modelling.ipynb)!
