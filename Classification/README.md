# Supervised Learning - Classification 
## News Classification - Classifying Categories of News on the bases of content of the News Articles.

I have downloaded News from the inshorts and placed them into 5 categories Automobile, Hatke, Enterainment, Science and Technology.
Each category contains atleast 1000 News Article for training the Model and 25 News Article for training the model. <br />

``` Format of News Articles: Title_of_the_News.txt```

<b>Libraries Used</b>: [scikit-learn](http://scikit-learn.org/) and [jupyter notebook](http://jupyter.org/)

### Models
1. Multinomial Navie Bayes
2. Support Vector Machine (SVM)
3. RidgeClassifierCV

## Sections
### 1. Extracting features from text files
Extract features from the text files using the <i>Bag of Words</i> Model. Also, Trasforming the Text using <i>Tf-idf</i> (Term Frequency times Inverse Document Frequency)

### 2. Train our model
Initialize 3 Models and train them using the preprocessed text.<br />
After training the model test the accuracy of each of the model using the <i>Confusion Matrix</i> and <i>accuracy_score()</i>

### 3. Building Pipeline
This section shows the process and techniques behind <i>Building a Pipeline</i> to automate the whole process from preprocessing the text to train our model.

### 4. Tuning Parameters using GridSearchCV
When training the model we can tune parameters and hyperparameters to achieve better perfromace but it's an awfully painfull task to test each parameter one by one but to make our work easier we have GridSearchCV which tunes the parameters using the set of parameters.

### 5. Saving the Model
Last section show us how we can save the Model that we have tuned and trained for future use.<br />



### Datset
``` 
Dataset is availabel in 'Dataset (News).rar' file.
Just Extract the file and Enjoy
```
