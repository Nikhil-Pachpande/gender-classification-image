# gender-classification-image
Classifying an image whether it's male or female using Kaggle dataset.<br><br>
The dataset contains more than 200k images split into Train, Test & Validation Sets.<br><br>
The model contains 5 CNN layers with relu activation function and sigmoid activation function for the last Dense layer to narrow down the probabilities for our binary classification.<br><br>
Optimizer used : Adam, loss : binary crossentropy, learning rate : 0.001, epochs : 12, steps per epoch : 256<br><br>
The Training Result:<br>
![training result](training_capture.JPG)<br><br>
The Model Summary:<br>
![Model Summary](model_summary.JPG)<br><br>
Training and Validation Accuracy:<br>
![Accuracy Plot](accuracy_plot.JPG)<br><br>
Testing the model:<br>
![Male](test_male.JPG)<br><br>
![Female](test_female.JPG)
