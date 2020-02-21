## Voice emotion detection:
* Goal of this project to predict the emotion in voice dataset
* Dataset used: Toronto emotional speech set (TESS) and Ryerson Audio-Visual Database of Emotional
## Speech and Song (RAVDESS)
* Feature extraction and feature processing for audio files.
* Experimented with Model architecture using CNN, LSTM and GRU cells.
* Achieved a model with the performance of 85 percent accuracy on validation set.
## Text data augmentation:
* Grammar rule is used to choose the possible word for augmentation
* For possible words used the synonyms replacement technique to increase the number of samples for
training.
* Used BLEU and Rouge score for measuring the augmented data quality
* Translated the whole sentence into possible langugages and transfer back to required language for
model.
## Predict next word by given number of input words:
* Tried to predict the next word by taking the n number of input words
* Trained the model using LSTM cells for word sequence prediction
* Achieved the model performance with 55 percent of accuracy in word prediction
## Red blood cell detection:
* Used the open source image set contains blood cell images
* Trained on tiny yolo model.
* Achieved about 43 percent of accuracy in optimization so far.
