# News-Classification

## News classification using PyTorch LSTMs (in progress!), zero-shot bart and bert classifiers!

![image](https://user-images.githubusercontent.com/57833772/233807384-9e3829d5-91a6-4897-92e6-85458f4d3bc4.png)

## Technologies used
* PyTorch
* Pandas
* Hugging Face
* SeaBorn

## Folder structure
1. ```news_data``` - ~0.5mln rows split into several CSV files containing news headline, news article and news category. 
2. ```notebooks```:
  1. Data Exploration - notebook exploring the data, testing for class imbalance and trying to spot any instant patterns. 80% accuracy on reduced testset.
  2. Hugging Face - notebook implementing zero-shot bart and bert classifiers! Have a go! 90% accuracy on reduced testset.
  

## Sample row

1. Headline: 50-year-old problem of biology solved by Artificial Intelligence
2. Article: "DeepMind's AI system 'AlphaFold' has been recognised as a solution to ""protein folding"", a grand challenge in biology for over 50 years. DeepMind showed it can predict how proteins fold into 3D shapes, a complex process that is fundamental to understanding the biological machinery of life. AlphaFold can predict the shape of proteins within the width of an atom."
3. Category: technology
