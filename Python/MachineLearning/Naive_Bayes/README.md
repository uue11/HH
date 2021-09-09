
# Naive Bayes
from sklearn.naive_bayes import GaussianNB
Model = GaussianNB()
Model.fit(X_train, y_train)

y_pred = Model.predict(X_test)

# Summary of the predictions made by the classifier
print(classification_report(y_test, y_pred))
print(confusion_matrix(y_test, y_pred))
# Accuracy score
print('accuracy is',accuracy_score(y_pred,y_test))

### Code
Adaboost algorithm: <br />
<img src="https://github.com/akjadon/HH/blob/master/Python/MachineLearning/images/naivebase.PNG" width="600"> <br />