 In this project, I have used supervised algorithms to identify emails from the Enron corpus by their authors I started start with Naive Bayes, and then expand to other algorithms in later projects.

Naive Bayes is a good algorithm for text classification. When dealing with text, it is very common to treat each unique word as a feature. This makes for a large number of features, but the relative simplicity of the algorithm and the independent features assumption of Naive Bayes make it a strong performer for classifying texts.

Support vector machines (SVMs) are another popular supervised algorithm. SVMs are more complex than Naive Bayes, but they can be more accurate. One way to speed up an SVM is to train it on a smaller training dataset. The tradeoff is that the accuracy almost always goes down when you do this.

Decision trees are another supervised algorithm. Decision trees are easy to understand and interpret, but they can be less accurate than other algorithms.

In this project, I have used all three of these algorithms to identify emails from the Enron corpus by their authors. compared the accuracy of the different algorithms and discuss the trade-offs between accuracy and speed.

Here are the steps involved in the project:

1) Preprocess the data. This involves cleaning the data and removing stop words.
2) Split the data into training and testing sets.
3) Train the different algorithms on the training set.
4) Make predictions on the testing set.
5) Evaluate the accuracy of the different algorithms.
6) Used the scikit-learn library to implement the different algorithms.
