The 1st block is importing the libraries that are needed.
The 2nd block is to connect to my google drive.
The 3rd block is writing the path for this assessment, and reading in the train and test set.
The 4th block is splitting the training set into label 0 and label 1, and splitting the train.csv into training and validation.
The 5th block is combining the training set with label 0 and label 1, and also combining the validation set with label 0 and label 1.
The 6th block is installing torchtext with version 0.8.0.
The 7th block is installing the needed libraries, loading the train dataset and valid dataset with properly defined fields for label data and text data, building the vocabulary for training dataset, and splitting the train_iter and valid_iter.
The 8th block is calculating the number of OOV vocabularies in the training set.
The 9th block is calculating the number of OOV vocabularies in the validation set.
The 10th block is defining the baseline RNN model.
The 11th block is installing torchsummaryX, and showing the summary of the baseline RNN model.
The 12th block is defining the save_checkpoint, load_checkpoint, and TRAIN function for training and validation.
The 13th block is training the baseline RNN model.
The 14th block is plotting the training loss and validation loss curves of the baseline RNN model.
The 15th block is defining the GRU model.
The 16th block is training the GRU model.
The 17th block is defining the unidirectional LSTM model.
The 18th block is training the unidirectional LSTM model.
The 19th block is plotting the training loss and validation loss curves for RNN, GRU, and unidirectional LSTM models.
The 20th block is defining the bidirectional LSTM model.
The 21st block is training the bidirectional LSTM model.
The 22nd block is plotting the training loss and validation loss curves for unidirectional LSTM and bidirectional LSTM models.
The 23rd block is defining model 4.
The 24th block is importing GloVe and building the vocab with this embedding type.
The 25th block is calculating the L2 distances of the pretrained GloVe embedding for (happy, good), (france, germany), and (france, happy).
The 26th block is training model 4.
The 27th block is defining model 5.
The 28th block is training model 5.
The 29th block is defining model 6.
The 30th block is defining the random vector.
The 31st block is training model 6 with the random vector.
The 32nd block is plotting the training loss and validation loss curves for unidirectional LSTM model, model 4, model 5, and model 6.
The 33rd block is defining model 7.
The 34th block is training model 7.
The 35th block is defining model 8.
The 36th block is training model 8.
The 37th block is plotting the training loss and validation loss curves for unidirectional LSTM model, model 7, and model 8.
The 38th block is putting the test set in the model to test the model.
The 39th block is writing the test set result to pred.csv.