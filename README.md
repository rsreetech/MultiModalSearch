# Multi Modal Search (Text+Image) using Tensorflow, HuggingFace  in Python on Kaggle Shopee Dataset
In this repository I demonstrate how you can perform multimodal(image+text) search to find similar images+texts given a test image+text from a multimodal (texts+images) database . I use the Kaggle Shopee dataset. I use Tensorflow  MobileNet CNN and hugging face sentence transformers BERT  to extract image and text embeddings to create a joint embedding search space. Given an image and it text description I extract joint embedding and then use nearest neighbours algorithm to find top 5 similar images+texts description from my joint embedding search space

Pre-requisites

Python 3.6
https://www.python.org/downloads/release/python-360/ 

Tensorflow 2.0 and above
https://www.tensorflow.org/install 

Hugging Face transformers
https://huggingface.co/transformers/ 

Sentence transformers
https://www.sbert.net/ 

Kaggle Shopee dataset:
https://www.kaggle.com/c/shopee-product-matching/data 


References:
MobileNet : https://arxiv.org/pdf/1704.04861.pdf   

Sk-learn nearest neighbours :
 https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.NearestNeighbors.html#sklearn.neighbors.NearestNeighbors ,
 https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.DistanceMetric.html#sklearn.neighbors.DistanceMetric , 
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.pairwise.paired_cosine_distances.html 

BERT: http://jalammar.github.io/illustrated-bert/ 

