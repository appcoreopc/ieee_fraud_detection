# ieee_fraud_detection

Analysis Work

https://www.kaggle.com/kernels/scriptcontent/17693707/download

https://www.kaggle.com/rajwardhanshinde/stackers-blend-top-4

0.94. https://www.kaggle.com/vincentlugat/ieee-lgb-bayesian-opt
0.93  https://www.kaggle.com/kabure/extensive-eda-and-modeling-xgb-hyperopt

The art of feature engineering 

https://www.kaggle.com/iasnobmatsu/xgb-model-with-feature-engineering



Stacknet
https://www.kaggle.com/kepung/ieee-fraud-stacknet-on-gpu-lgb-xgb-cb/edit


Past competitions

TalkingData AdTracking Fraud Detection Challenge (https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/overview)

1st place  (https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/discussion/56475#latest-436248)

-Negative down sample

-LDA/NMF/LSA

five raw categorical features (ip, os, app, channel, device) 
time categorical features (day, hour) 
some count features 


 
2nd place (https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/discussion/56328#latest-331897)

3rd place (https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/discussion/56262#latest-517655)

6th solution (https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/discussion/56283#latest-408114)


Home Credit Default Risk (this is about risk, but might be useful)
1st place solution (https://www.kaggle.com/c/home-credit-default-risk/discussion/64821#latest-453304)
2nd place (https://www.kaggle.com/c/home-credit-default-risk/discussion/64722#latest-394948)
3rd place (https://www.kaggle.com/c/home-credit-default-risk/discussion/64596#latest-420333)


Elo Merchant Category Recommendation (https://www.kaggle.com/c/elo-merchant-category-recommendation)

Santander Customer Transaction Prediction https://www.kaggle.com/c/santander-customer-transaction-prediction


Lightgbm examples 

https://github.com/microsoft/LightGBM/tree/master/examples

Credit Card Fraud Detection (https://www.kaggle.com/mlg-ulb/creditcardfraud) 
Synthetic Financial Datasets For Fraud Detection (https://www.kaggle.com/ntnu-testimon/paysim1)

relevent pdf

https://arxiv.org/pdf/1905.06247.pdf (Multiple perspectives HMM-based feature engineering for credit
card fraud detection)

https://arxiv.org/pdf/1904.10604.pdf (A Comparison Study of Credit Card Fraud Detection:
Supervised versus Unsupervised)


https://arxiv.org/ftp/arxiv/papers/1903/1903.00410.pdf (Improving fraud prediction with incremental data balancing technique for massive data streams)


https://arxiv.org/pdf/1901.08930 Active Anomaly Detection via Ensembles: Insights, Algorithms, and Interpretability


https://arxiv.org/pdf/1906.06977.pdf  (Dataset shift quantification for credit card fraud detection)

https://arxiv.org/pdf/1907.07212.pdf )(Helen)

https://arxiv.org/pdf/1906.07407.pdf (TitAnt: Online Real-time Transaction Fraud Detection
in Ant Financial)




Question about lightgbm 

It is a black box model and its executions is learning features as 'greedy' as possible. 
 
 > How do you tell it, hey don't look at this, but look at this? 
 
 You can't
 
 > How do you say, if this is device info is different, then the weight is obviously higher. 
 
 Give it a weight? 
 
 lightgbm only works with data, if it is in string, then encode it. 
 

https://people.eecs.berkeley.edu/~raluca/Thesis.pdf

https://crypto.stackexchange.com/questions/46736/how-to-prove-correct-decryption-in-paillier-cryptosystem

RLWE


https://people.eecs.berkeley.edu/~svlevine/



cols_to_drop=['V300','V309','V111','C3','V124','V106','V125','V315','V134','V102','V123','V316','V113',
              'V136','V305','V110','V299','V289','V286','V318','V103','V304','V116','V29','V284','V293',
              'V137','V295','V301','V104','V311','V115','V109','V119','V321','V114','V133','V122','V319',
              'V105','V112','V118','V117','V121','V108','V135','V320','V303','V297','V120']


Project Echo
https://echo-ai.readthedocs.io/en/latest/


Gradient Boosting Machine: A Survey
https://arxiv.org/pdf/1908.06951.pdf (MIT) 

Gradient boost for financial scoring
https://arxiv.org/pdf/1908.03385.pdf





