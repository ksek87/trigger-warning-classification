# CLASSIFICATION OF 'TRIGGERING' CONTENT ON SOCIAL MEDIA

## Overview
  This project was completed during my time in CSCI 4152 - Natural Language Processing. It considers the problem of automating the assignment of trigger warning labels   to social media posts using traditional classifiers and machine learning techniques.

  ## Research Project Report
  The full paper can be found here: [report.pdf](https://github.com/ksek87/trigger_warning_classification/blob/main/report.pdf)
  
  If you use my work, please cite it! :)
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
  - For my research, the dataset comprises of 361,641 reddit posts upon completion of pre-processing. 

## Models
- Linear SVC Classifier 
- Multinomial Naive Bayes Classifer
- Feed Forward Neural Network
    - Architecture adapted from Gkotsis et al.'s [6] research in mental health classification.
- Convolutional Neural Network
    - Architecture adapted from Kim et al.'s [7] research in mental health classification.

Check out my experimental results in this [jupyter notebook](https://github.com/ksek87/trigger_warning_classification/blob/main/src/pre_processing_and_modelling.ipynb) or my final presentation [slides](https://github.com/ksek87/trigger-warning-classification/blob/main/slides.pdf)!

## Libraries Used
- Sci-kit Learn
- Tensorflow Keras
- Pushshift.io
- NLTK
- Gensim
- Pandas
## References
[1] A. Vingiano, “How The ‘Trigger Warning’ Took Over The Internet,” Buzzfeed News, 
Buzzfeed, 05-May-2014. 

[2] M. Sanson, D. Strange, and M. Garry, “Trigger warnings are trivially helpful at reducing 
negative affect, intrusive thoughts, and avoidance,” Clinical Psychological Science, vol. 7, 
no. 4, pp. 778–793, 2019.

[3] O. L. Haimson, J. Buss, Z. Weinger, D. L. Starks, D. Gorrell, and B. S. Baron, “Trans time: 
Safety, Privacy, and Content Warnings on a Transgender-Specific Social Media Site,” 
Proceedings of the ACM on Human-Computer Interaction, vol. 4, no. CSCW2, pp. 1–27, 


[4] S. Modha, P. Majumder, T. Mandl, and C. Mandalia, “Detecting and visualizing hate speech 
in Social Media: A cyber watchdog for surveillance,” Expert Systems with Applications, vol. 
161, p. 113725, 2020. 

[5] I. Soldevilla and N. Flores, “Natural language processing through Bert for identifying gender-based violence messages on social media,” 2021 IEEE International Conference on 
Information Communication and Software Engineering (ICICSE), 2021. 

[6] G. Gkotsis, A. Oellrich, S. Velupillai, M. Liakata, T. J. Hubbard, R. J. Dobson, and R. Dutta, 
“Characterisation of mental health conditions in social media using informed Deep 
Learning,” Scientific Reports, vol. 7, no. 1, 2017. 

[7] J. Kim, J. Lee, E. Park, and J. Han, “A deep learning model for detecting mental illness from 
user content on social media,” Scientific Reports, vol. 10, no. 1, 2020. 

[8] J. Ive, G. Gkotsis, R. Dutta, R. Stewart, and S. Velupillai, “Hierarchical neural model with 
attention mechanisms for the classification of social media text related to mental health,” 
Proceedings of the Fifth Workshop on Computational Linguistics and Clinical Psychology: 
From Keyboard to Clinic, 2018. 

[9] Z. Yang, D. Yang, C. Dyer, X. He, A. Smola, and E. Hovy, “Hierarchical Attention Networks 
for document classification,” Proceedings of the 2016 Conference of the North American 
Chapter of the Association for Computational Linguistics: Human Language Technologies, 
Jun. 2016. 

[10] Ankit Murarka, Balaji Radhakrishnan, and Sushma Ravichandran. 2020. Detection and 
Classification of mental illnesses on social media using RoBERTa. arXiv Prepr. 
arXiv2011.11226 (2020).

[11] “An Introduction to Content Warnings and Trigger Warnings,” Univeristy of Michigan 
Inclusive Teaching LSA. [Online]. Available: https://sites.lsa.umich.edu/inclusive-teaching-sandbox/wp-content/uploads/sites/853/2021/02/An-Introduction-to-Content-Warnings-and-Trigger-Warnings-Draft.pdf. 

[12] “Reddit,” reddit. [Online]. Available: https://www.reddit.com/.

[13] Pushshift.io. (2019). Pushshift.io. Available: https://pushshift.io/.

[14] Natural Language Toolkit. NLTK.Available: https://www.nltk.org/.

[15] Scikit-Learn. (2021). Scikit-Learn. Available: https://scikit-learn.org/.

[16] Keras. (2021). Tensorflow. Available: https://keras.io/

[17] Gensim: Topic modelling for humans. (2021). Available: https://radimrehurek.com/gensim/.
