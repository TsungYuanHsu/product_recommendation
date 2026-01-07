
# 📝 Product recommendation

## 🌟 Highlights
From this project "Product recommendation", the highlights are addressed as:
- Data visualization to explain dataset
- Efficiency improvement of feature extraction by 88% from VGG16 model to parallel processing/ MobileNetV2 model
- Utilize cosine similiarity on feature similarity analysis
- Output MobileNetV2/ cosine similarity as numpy to shorten time of running repeatedly
- Apply hard filter "subCategory" to increase recommendation performance
- Recommendation function call-out

## ℹ️ Project Introduction 
In the modern era, the rapid growth of data collection and analysis has led to data-driven world. Making decision based on data creates more efficient and precise outcome.  
Recommendation system is a kind of information filtering system. It analyzes similar contents and users to decide which items or product the user might like.  
This approach improves quality of search results and capability of providing more relevant information to users.  
There are 3 types of recommendation systems
- Content-based filtering: Recommend based on items with similar features and properties
- Collaborative filtering: Recommend based on what similar users already like
- Hybrid

**Product recommendation in this project recommends similar products to users based on content similarity**  
In this project, I will build up a recommendation system to recommend similar products according to similar features of products.  

## 🎯 Mission & Goal
As a data scentist working on a recommendation system, I am asked to build system to provide similar products to users, which has a potential to create more options to userss for product purchase based on their preferred taste. Eventually, this recommendation can bring up shopping experience and profit.  
  
**The outcome of this project should recommend products which are similar to user product input**

## 🧠 Thinking
To be able to recommend the product with similar features, we will need the following items:
- [x] product image dataset
- [x] Preprocess the dataset
- [x] Load the image
- [x] Convert the image (pixel block value) to numeric data that mechine recognizes
- [x] Extract the image features
- [x] Similarity analysis to judge similarity between product according to features
- [x] Function to recommend similar products from input product


## 🏭 Build Flow
- Import libraries
- Import dataset
- Inspect/preprocess the dataset
- Load the image
- MobileNetV2 (since VGG16 is a heavy CNN)
- Load training data after modeling from numpy
- Similarity analysis to judge similarity between product
  - Cosine similarity
- Function to recommend similar products from input product