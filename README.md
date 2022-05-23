## A Deep Attentive Multimodal Learning Approach for Disaster Identification From Social Media Posts

**Author:** Eftekhar Hossain, Mohammed Moshiul Hoque, Enamul Hoque, Md. Saiful

**Venue:** IEEE Access (Q1, IF-3.367)   

**Paper Link:** [https://ieeexplore.ieee.org/abstract/document/9764741](https://ieeexplore.ieee.org/abstract/document/9764741)

**Dataset Link:** [Damage Identification](https://archive.ics.uci.edu/ml/datasets/Multimodal+Damage+Identification+for+Humanitarian+Computing)



## Contribution
- We propose a multimodal architecture that utilizes ResNet50 and BiLSTM recurrent neural network with attention mechanism to classify the damage-related
posts by exploiting both visual and textual information.
- We compare the performance of the proposed model with a set of existing unimodal (i.e., image, text) and multimodal classification techniques.
- We empirically evaluate the proposed model on a benchmark dataset and demonstrated how introducing attention could enhance the system performance through an
intrinsic evaluation.
- We perform both quantitative and qualitative analysis to get deeper insights about the error types which provide future directions for improving the model.


- 

## System Overview
Figure 2 presents the schematic diagram of our system, which has three major phases: preprocessing, feature extraction and classification.
<img title="" src="Figures/Fig2.PNG" alt="">

## Results 
Table 3 presents the evaluation results of task-A on the test set.
<img title="" src="Figures/Table3.PNG" alt="">

Evaluation results of task-B on the test set are presented in table 4.
<img title="" src="Figures/Table4.PNG" alt="">

Tables 5a-5f represent the confusion matrices of the classes for task-A and B.
<img title="" src="Figures/Table5.PNG" alt="">

Some misclassified examples with there actual (A) and predicted label (P) presented in table 6.
<img title="" src="Figures/Table6.PNG" alt="">

## Conclusion
This paper presents the system description with detailed results and error analysis developed in the CONSTRAINT 2021 shared task. Various learning technique have explored with tf-idf feature extraction, andWord2Vec embedding technique to accomplish the tasks A and B. Results shows that SVM with tf-idf achieved the highest of 94.39% f1 scores for the task-A and LPSVM with n-gram (1, 3) obtained the highest of 86.03% f1 scores for the task-B. However, the BERT pre-trained model provided the 98% accuracy in task-A and 97% accuracy in task-B. Since CNN and BiLSTM did not achieve satisfactory accuracy, it will be interesting to see how they perform after applying ensemble technique or adding attention layer. Increasing the number of posts in hostile classes can help to improve the performance of the models. These issues will address in future work.

## Ackonwlegement
Without my teammate [Eftekhar Hossain's](https://eftekhar-hossain.github.io/portfolio/) support and dedication this work would not be possible. Finally, thanks to [Prof. Dr. Mohammed Moshiul Hoque](https://www.researchgate.net/profile/Moshiul_Hoque) for his valuable guidance.

## Note
`If you find any anomaly or have any query/suggestion feel free to ping.`



# Disaster_IEEE-Access

Dataset Link: [Damage Identification](https://archive.ics.uci.edu/ml/datasets/Multimodal+Damage+Identification+for+Humanitarian+Computing)
