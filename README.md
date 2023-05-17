# Customer Segmentation with RFM Method
This is a group final project of Machine Leanring subject. The students are required to build at least 2 traditional and 1 deep-leanrning unsupervising algorithms and qualify which algorithm gives the best clustering result. Our group has chosen customer segmentation as our subject, and apply RFM method to cluster the customers.
## Dataset
The dataset is uploaded on Kaggle webiste. It was extracted from O-list - a Brazillian e-commerce platform. The dataset includes the information of orders, customers, sellers. Below is the data schema:
![image](https://github.com/MinhThanh2404/Customer-Segmentation-with-RFM-Method/assets/126949248/ae4f6bfd-c7b8-4638-a89b-87f1d8e4e4d8)
* Here is the link of the original dataset on Kaggle: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
## Target
From the given dataset, we will calculate 3 main indexes: Recency, Frequency, Monetary. After some data preprocessing, we build and train 3 unsupervising models: KMeans, HAC, AutoEncoder. Some specific scores are used to evaluate how well each model clusters the data.
## Workflow:
1. Import/Crawl data
2. Preprocess data
3. Visualize data
4. Calculate R,F,M index
5. Build, train 3 models
6. Evaluate 3 models
7. Analyse the clustering result of the best model

*The report is written in Vietnamese. In summary, we clustered in 2 circumstances: with outliers and without outliers. The evaluation showed that clustering with outliers gives better result. However, based on our professor's feedback, the way we determined outliers was incorrect (we apply 1 range (of the M - monetary) for the whole 3 indexes R,F,M, which was considered inappropriate for the 2 left). I'm on the way of correct it, and will update the report, if possible 🤗*
