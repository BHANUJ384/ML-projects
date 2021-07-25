Quora Question pairsSimilarity

So quora is a platform where people can ask or answer the question of one another. Millions of people visit quora every month and and their is so much chances that many people can ask similarly worded question so and if there is multiple questions which has same meaning can cause seeker to spent more time on finding the best answer and writer to write the same answer for multiple times.

So the problem statement was to find the duplicate question being asked multiple times and to predict whether a pair of questions are duplicates or not, so basically it was binary classification problem.

And the business objective was that there would be high cost of mis-classification, to find the probability of a pair of question to be duplicate and interpretability is partially important.

And i have used the log-loss and binary confusion matrix as a perfomance matrix.

I have splitted the data into 70:30 ratio for train and test resp. and their was 404290 rows and 4 features with label.

then firstly i have done exploratory data analysis to understand the behavior patterns.
then i have done some important feature extraction and then done text preprocessing.
then i have used t-sne to reduce the diamentions and then build the random model.
then applied logistic regression ,svm and xg boost algo.

data source- https://www.kaggle.com/c/quora-question-pairs

