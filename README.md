# Depression_Detection
The main aim of this project is to determine whether the person is depressed or not .
The working is as follows:
1-The Virtual interviewer is made (chat bot) through which the audio data in the real time is taken from the user and at the end of teh interview it is predicted whether the person is depressed or not.

Training of the model-

Dataset- the dataset consists of the 100+ audio files in which there is the recorded interview of the person and the interviewer 

data cleaning- To work on the persons voice we have trimed the virtual interviewer voice with the help  of the sox . the code is given in the file Automate_trimming.ipynb
 
 Feature extraction--
 the Feature are extracted using the libraray librosa 
 
 Model-
 The ANN model is used in training .  
 The accuracy is observed between 65-75%.
