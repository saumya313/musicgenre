# Music-Genre-classifier
A deep learning model which classifies tune and songs into their respective genres. Also a comparative study between 3 famous CNN algorithms over the same objective.  


https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification - link for the dataset


Used 4 metrics for evaluation on all the models, namely - accuracy, precision, recall and F1 score. 
The former 3 metrics was maximum for the VGG19 model whereas the later was comparatively low for the same.
Still chose to go with the VGG19 model as the final model since, F1 score are more valuable metric if the dataset is unbalanced class type, i.e. the training dataset has different number of samples in all the classes, whereas accuracy can be valuable when the classes are balanced. In this case since the classes were balanced in the training dataset, so went with the model having highest accuarcy i.e VGG19
The accuracy of the model on the unseen data was coming out to be 67% and the model was able to predict 40-50% of the data correctly.
Reason for low accuracy can be improper split of the data in training, validation and test sets and low number of Samples in the dataset.
Further in the future more models can be tested on the same dataset or the hyperparameters for the models can be tuned more or the number of smaples in the data can be increased for better results.
The genres include-
Blues 
classical
country
hiphop
jazz
pop
metal
reggae
rock
Removing pop genre from the dataset might improve the accuracy since there is no correct definition for pop music.

