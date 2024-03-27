# **Using Word Embeddings for Twitter Sentiment Analysis**
# **Project implementation**
### **1. Learn the basic concepts of Natural Language Processing**
### **1.1. Learn about Word Embeddings (eg: Bag of Words (BOW), Word2Vec,..)**
### **1.2. Refer to related research articles**
### **1.3. Refer to related code articles**
## **2. Deploy project construction**
### **2.1. Collect data (Here I use kaggle)**
**- The link to the dataset is**
[DATASET](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis?select=twitter_training.csv)

**- Data chart**

![屏幕截图 2024-03-27 063613](https://github.com/FPT-ThaiTuan/Using-Word-Embeddings-for-Twitter-Sentiment-Analysis/assets/105273233/75ee6fec-e2bd-4a63-a0e4-6aa6c4a60829)
![屏幕截图 2024-03-27 063550](https://github.com/FPT-ThaiTuan/Using-Word-Embeddings-for-Twitter-Sentiment-Analysis/assets/105273233/c30dda82-ac62-4c1c-95f4-96a7c6eea4db)

### **2.2. Data preprocessing**
**- Select inputs for model target and features**
**- Delete emoticons, special characters, limit the number of words in a sentence**
**- Standardize train data, validation data**
**- Converted our label to a one-time encoded value for the label**
### **2.3. Build the model**
**- Model architecture**

![屏幕截图 2024-03-27 063833](https://github.com/FPT-ThaiTuan/Using-Word-Embeddings-for-Twitter-Sentiment-Analysis/assets/105273233/b1964c29-d104-4dff-b03a-c539686cd193)

### **2.4. Visualize parameters and results**
**- Show loss and accuracy train and validation**

![屏幕截图 2024-03-27 064110](https://github.com/FPT-ThaiTuan/Using-Word-Embeddings-for-Twitter-Sentiment-Analysis/assets/105273233/ae582be9-61ab-4617-ac83-13d7322e42e3)
![屏幕截图 2024-03-27 064013](https://github.com/FPT-ThaiTuan/Using-Word-Embeddings-for-Twitter-Sentiment-Analysis/assets/105273233/25c1621d-9c20-4c0b-8fe6-1b94f90691b5)

### **2.5. Perform testing on external data sets**
**- Basic results and examples**

![屏幕截图 2024-03-27 064533](https://github.com/FPT-ThaiTuan/Using-Word-Embeddings-for-Twitter-Sentiment-Analysis/assets/105273233/9c365d53-4d09-4d87-bd8c-afc661d81240)

**- Results with binance test set**

![屏幕截图 2024-03-27 064554](https://github.com/FPT-ThaiTuan/Using-Word-Embeddings-for-Twitter-Sentiment-Analysis/assets/105273233/675a6ee5-4016-4822-b20e-95735b0071ca)

### **2.6. Visualize the vector and text above**
**- Vector data image** 
**- Points: 9999**
**- Dimension: 64**

![屏幕截图 2024-03-27 065022](https://github.com/FPT-ThaiTuan/Using-Word-Embeddings-for-Twitter-Sentiment-Analysis/assets/105273233/73e1f19e-808d-47d0-a570-69aa53ff0841)

## **3. Conclusion**
### **3.1. Advantages and disadvantages of the method used**
Word embeddings are powerful representations of words in a continuous vector space, capturing semantic relationships and improving NLP tasks' performance. They offer advantages such as semantic representation, dimensionality reduction, and transfer learning. However, they have limitations like fixed vocabulary, contextual ambiguity, and data bias. 
### **3.2. Find ways to improve the model in the future**
- Further development in terms of application
- Train the model with larger data
- Model improvements (combining other models, changing parameters,...)


### **Hope this article can help you.**
### **If you have any questions please contact me for help!**
### **Gmail: tuanddt.ai.work@gmail.com**

### ***Thanks everyone!***

