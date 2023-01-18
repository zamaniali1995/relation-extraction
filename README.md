## 📚 3-rd Party Libraries
You do not need to list `nltk` and `pandas` here.
* `main.py L:[4]` used `[sklearn.model_selection]` for [importing KFold class].
* `main.py L:[5]` used `[sklearn.metrics]` for [importing confusion_matrix class].
* `main.py L:[34]` used `[KFold]` for [defining the kf object for cross validation purposes].
* `main.py L:[232, 235, 236]` used `[confusion_matrix]` for [constructing the confusion matrix].

## 🏃 Execution
Example usage: use the following command in the current directory.

`python3 src/main.py --train data/train.csv --test data/test.csv --output output/test.csv`

## 📊 Data

The data can be found in [data/train.txt](data/train.txt),and the in-domain test data can be found in [data/test.txt](data/test.txt).

## ✍️ Results

### Accuracy
![Accuracy](https://github.com/zamaniali1995/relation-extraction/blob/master/accuracy.png)

### Confusion Matrix
![Confusion matrix](https://github.com/zamaniali1995/relation-extraction/blob/master/confusion_matrix.png)

### Class 1 (Characters)
![Class 1 (Characters)](https://github.com/zamaniali1995/relation-extraction/blob/master/class1_characters.png)

### Class 2 (Director)
![Class 2 (Director)](https://github.com/zamaniali1995/relation-extraction/blob/master/class2_director.png)

### Class 3 (Performer)
![Class 3 (Performer)](https://github.com/zamaniali1995/relation-extraction/blob/master/class3_performer.png)

### Class 4 (Publisher)
![Class 4 (Publisher)](https://github.com/zamaniali1995/relation-extraction/blob/master/class4_publisher.png)

### Precision and recall
![Class 4 (Publisher)](https://github.com/zamaniali1995/relation-extraction/blob/master/precision_recall.png)
