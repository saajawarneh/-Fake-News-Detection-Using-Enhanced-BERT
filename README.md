# Fake-News-Detection-Using-Enhanced-BERT

# Availablity of this publication

The full paper is available through the following links

1- IEEE Transactions on Computational Social Systems:https://ieeexplore.ieee.org/abstract/document/9965362

# Overview

Since there are so many users on social media, who are not qualified to report news, fake news has become a major problem in recent years. Therefore, it is crucial to identify and restrict the dissemination of false information. Numerous deep learning models that make use of natural language processing have yielded excellent results in the detection of fake news. bidirectional encoder representations from transformers (BERT), based on transfer learning, is one of the most advanced models. In this work, the researchers have compared the earlier studies that employed baseline models versus the research articles where the researchers used a pretrained model BERT for the detection of fake news. The literature analysis revealed that utilizing pretrained algorithms is more effective at identifying fake news because it takes less time to train them and yields better results. Based on the results noted in this article, the researchers have advised the utilization of pretrained models that have already been taught to take advantage of transfer learning, which shortens training time and enables the use of large datasets, as well as a reputable model that performs well in terms of precision, recall, as well as the minimum number of false positive and false negative outputs. As a result, the researchers created an improved BERT model, while considering fine-tuning it to meet the demands of the fake news identification assignment. To obtain the most accurate representation of the input text, the final layer of this model is also unfrozen and trained on news texts. The dataset used in the study included 23 502 articles of fake news and 21 417 items of actual news. This dataset was downloaded from the Kaggle website. The results of this study demonstrated that the proposed model showed a better performance compared with other models, and achieved 99.96% and 99.96% in terms of accuracy and F 1 score, respectively.

# Dataset

The dataset which used in this study is downloaded from Kaggle website (www.kaggle.com/datasets/kruzes1/fakenews1). Several processing steps are applied on the data before feeding them to the model. To get the full details of this process, please refer to the paper.

# Methodology

The following figure shows an overview of the methodology that is applied in this work. To get the full details about the methodology, please refer to the paper.

![image](https://user-images.githubusercontent.com/120778517/208239032-91c06d41-c854-4806-9573-eb10ec308849.png)

# Cite this as

@article{aljawarneh2022fake,
  title={Fake News Detection Using Enhanced BERT},
  author={Aljawarneh, Shadi A and Swedat, Safa Ahmad},
  journal={IEEE Transactions on Computational Social Systems},
  year={2022},
  publisher={IEEE}
}
