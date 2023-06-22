# Visual search with Azure Computer Vision and Azure Cognitive Search

We will use vectors embeddings generation using **Azure Computer Vision 4** and **Azure Cognitive Search** and its new vectors support capabilities to build a visual search application.


## Visual search with vector embeddings
**Vector embeddings** are a way of representing content such as text or images as vectors of real numbers in a high-dimensional space. These embeddings are often learned from large amounts of textual and visual data using machine learning algorithms like neural networks. Each dimension of the vector corresponds to a different feature or attribute of the content, such as its semantic meaning, syntactic role, or context in which it commonly appears. By representing content as vectors, we can perform mathematical operations on them to compare their similarity or use them as inputs to machine learning models.

## Notebooks

- Introduction to vectors embeddings with Azure Computer Vision 4:<br>
<a href="1. Vectors embeddings with Azure Computer Vision.ipynb">1. Vectors embeddings with Azure Computer Vision</a>
- Creation of a fashion visual search demo using Azure Computer Vision and Azure Cognitive search:<br>
<a href="2. Visual search with Azure Cognitive Search and Azure Computer Vision.ipynb">2. Visual search with Azure Cognitive Search and Azure Computer Vision</a>

Note: You need to write your Azure AI credentials in the **azure.env** file

## Demo video
<a href="https://www.youtube.com/watch?v=uHQFTUjQWp4">Demo video</a>

## Some examples of a prompt search
<img src= "prompt search (1).jpg">
<img src= "prompt search (2).jpg">
<img src= "prompt search (3).jpg">

## Some examples of an image search
<img src= "image_search (1).jpg">
<img src= "image_search (2).jpg">
<img src= "image_search (3).jpg">

## Steps
- Connect to a blob storage where your catalog images are
- Use Azure Computer Vision 4 to embed all these images
- Create an Azure Cognitive search vector store index
- Upload the embeddings into an Azure Cognitive Search index
- Do some visual search using a prompt or an image

## Business applications
- Digital asset management: Image retrieval can be used to manage large collections of digital images, such as in museums, archives, or online galleries. Users can search for images based on visual features and retrieve the images that match their criteria.
- Medical image retrieval: Image retrieval can be used in medical imaging to search for images based on their diagnostic features or disease patterns. This can help doctors or researchers to identify similar cases or track disease progression.
- Security and surveillance: Image retrieval can be used in security and surveillance systems to search for images based on specific features or patterns, such as in, people & object tracking, or threat detection.
- Forensic image retrieval: Image retrieval can be used in forensic investigations to search for images based on their visual content or metadata, such as in cases of cyber-crime.
- E-commerce: Image retrieval can be used in online shopping applications to search for similar products based on their features or descriptions or provide recommendations based on previous purchases.
- Fashion and design: Image retrieval can be used in fashion and design to search for images based on their visual features, such as color, pattern, or texture. This can help designers or retailers to identify similar products or trends.

## To learn more
- https://learn.microsoft.com/en-us/azure/cognitive-services/computer-vision/concept-image-retrieval
- https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search

In this notebook we took some samples fashion images are taken from this link:
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset

22th June 2023
Serge Retkowsky | serge.retkowsky@microsoft.com | https://www.linkedin.com/in/serger/
