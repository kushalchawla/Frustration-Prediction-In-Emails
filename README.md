# Frustrated, Polite or Formal: Quantifying Feelings and Tone in Emails

Abstract:
Email conversations are the primary mode of communication in enterprises. The email content expresses an individual’s needs, requirements and intentions. Affective information in the email text can be used to get an insight into the sender’s mood or emotion. We present a novel approach to model human frustration in text. We identify linguistic features that influence human perception of frustration and model it as a supervised learning task. The paper provides a detailed comparison across traditional regression and word distribution-based models. We report a mean-squared error (MSE) of 0.018 against human-annotated frustration for the best performing model. The approach establishes the importance of affect features in frustration prediction for email data. We further evaluate the efficacy of the proposed feature set and model in predicting other tone or affects in text, namely formality and politeness; results demonstrate a comparable performance against the state-of-the-art baselines.

Link to the paper: https://peopleswksh.github.io/pdf/PEOPLES11.pdf

Link to the Enron FFP dataset: https://bit.ly/2IAxPab

Instructions to use: 

  For Python 2.x/3.x: 
  
  import pandas as pd
  
  df = pd.read_csv("./enron-FFP.csv") #assuming the dataset is downloaded in the same directory as the script.
  

If you use the dataset in your research, please cite: 

1) @inproceedings{khosla2018aff2vec,
  title={Aff2Vec: Affect--Enriched Distributional Word Representations},
  author={{Khosla}, S. and {Chhaya}, N. and {Chawla}, K.},
  booktitle={Proceedings of COLING 2018, the 27th International Conference on Computational Linguistics},
  pages={2204--2218},
  year={2018}
}

2) @inproceedings{chhaya2018frustrated,
  title={Frustrated, Polite or Formal: Quantifying Feelings and Tone in Emails},
  author={Chhaya, Niyati and Chawla, Kushal and Goyal, Tanya and Chanda, Projjal and Singh, Jaya},
  booktitle={Proceedings of the Second Workshop on Computational Modeling of People’s Opinions, Personality, and Emotions in Social Media, NAACL HLT},
  pages={76--86},
  year={2018},
  organization={Association for Computational Linguistics}
}

3) @article{cohen2009enron,
  title={Enron email dataset},
  author={Cohen, William W},
  year={2009}
}
