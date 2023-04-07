![Amazon Review Sentiment Analysis](https://user-images.githubusercontent.com/111559921/230529142-3a2d2a46-4ecd-477b-97d1-8e9407601c04.png)

  ## Summary
In this project I compare the accuracy of pretrained sentiment analysis tools, VADER and ROBERTA, to determine which of the two is more efficent for determining the sentiment of Amazon Video Game Reviews.

## Overview
The task of this project is to determine which Pretrained Natural Language Procesing model (VADER or ROBERTA) is more efficent for determining the sentiment of amazon reviews. I do this by taking the dataset and running it thorough each model. After I do so I compare the success rates of each model against one another as well as other features to see which model overall performed the best.

  ### Data
  * Type: Numerical & Text input
  * Instances: 110798
  * Features: 3

  ## Models
  * ROBERTA
  * VADER
  
  
  ## Performance Comparison 
  the VADER model had a 74% accuracy when it came to determining the sentiment of the amazon reviews. Based on the graphs, it seemed like the model had the most difficulty determining if a review was negative. The ROBERTA model had an accuracy of 77%. The graphs produced by the ROBERTA models findings seemed more orderly and compartmentalized than those of VADER.  
  
  ## Future Work 
  I would like to take this a step further to use the models on articles eventually. I believe these models with a few other tools will be able to take the sentiment of articles/social media posts and generate the general publics opinion on certain subjects. 
  
  ## Overview of files in repo
  * code.ipnyb - the jupyter notebook containing all of my code and findings
  
  ## software setup 
  * numpy
  * pandas
  * matplotlib
  * transformers
  * scipy
  
  ## Data
  * https://nijianmo.github.io/amazon/index.html
  
  
  ## Performace Evaluation 
  Accuracy aside, the VADER model was significantly faster than ROBERTA. While VADER took only a few moments to generate its findings, ROBERTAs took about an hour to process all of the data. 
  
  ## Citations 
  * XLM-Roberta - Hugging Face. https://huggingface.co/docs/transformers/model_doc/xlm-roberta. 
  * Beri, Aditya. “Sentimental Analysis Using Vader.” Medium, Towards Data Science, 27 May 2020, https://towardsdatascience.com/sentimental-analysis-using-vader-a3415fef7664. 
