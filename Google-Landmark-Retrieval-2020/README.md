# Challenge Discription

Image retrieval is a fundamental problem in computer vision: given a query image, can you find similar images in a large database? This is especially important for query images containing landmarks, which accounts for a large portion of what people like to photograph.

In this competition, the developed models are expected to retrieve relevant database images to a given query image (ie, the model should retrieve database images containing the same landmark as the query). This challenge is organized in conjunction with the Landmark Recognition Challenge 2020. Both challenges will be discussed at the Instance-Level Recognition workshop in ECCV’20.

In the previous editions of this challenge (2018 and 2019), submissions were handled by uploading prediction files to the system. This year's competition is structured in a representation learning format: rather than creating a submission file with retrieved images, you will create a model that extracts a feature embedding for the images and submit the model via Kaggle Notebooks. Kaggle will run your model on a held-out test set, perform a k-nearest-neighbors lookup, and score the resulting embedding quality with mean average precision.

# Dataset
Download from [link](https://www.kaggle.com/c/landmark-recognition-2020/data)
