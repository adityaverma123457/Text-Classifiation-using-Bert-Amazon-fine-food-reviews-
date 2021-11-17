# Text-Classifiation-using-Bert-[Amazon-fine-food-reviews]
To determine whether a review is positive or negative and build a machine learning model around it .
It contains 5 parts as below.
   a. Preprocessing 
   b. Creating a BERT model from the Tensorflow HUB.
   c. Tokenization
   d. getting the pretrained embedding Vector for a given review from the BERT.
   e. Using the embedding data apply NN and classify the reviews.
   f. Creating a Data pipeline for BERT Model.
DATA : data has 100000 reviews and corresponding star rating where we are considering rating < 3 as negetive and 
rating more than 3 as positive and rating = 3 (discarded from the dataset)
