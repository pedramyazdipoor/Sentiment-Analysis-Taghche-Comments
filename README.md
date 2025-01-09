## Sentiment Analysis On Taghche Comments

In this project we fine-tuned [ParsBert](https://github.com/hooshvare/parsbert) using its rich embeddings in order to do sentiment analysis.\
The dataset is found [here](https://www.kaggle.com/datasets/saeedtqp/taaghche).\
We define only 2 classes, positive for comment scores over 3 and negative for below this threshold.\
We pre-processed comments by removing links, hashtags, digits, emojis and etc. We also normalized comments using Hazm library.

![image](https://github.com/user-attachments/assets/2b403144-f9d2-40cc-9b06-645c302bc37f)

