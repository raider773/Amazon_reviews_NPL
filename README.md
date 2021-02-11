# Amazon_reviews_NPL
Used amazon reviews of electronics products to try and predict if comments are "good" or "bad"


notebook_1: transform the json docs to csv. visualize data and how classes are balanced. Also created a binary class column (positive or negative review) for training.\
notebook_2: Train a multiclass bayes for predicting the score based on the review (scores: 1-5).Balanced classes. Used sample instead of complete dataset. Accuracy and f1 weren't great.\
notebook_3: Train another bayes but with binary classes as target. if score was 4 or 5 then comment was positive. if it was lower then it was negative. scores increased a lot.\
notebook_4 and notebook_5: Used the binary model from notebook_3 to predict if new self-made reviews are positive or negative. Notebook_4 is like hosting and notebook_5 would be the "client".\

Original dataset that i transform into data.csv in notebook_1 is not in repository since it was quite big.\
The model_binary.pkl is the model trained in notebook_3




