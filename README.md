# MoodBot
## Description
MoodBot is my final project for the data science Lighthouse Labs bootcamp. 

**Topic:**
It is a attention recognition program that can track your face and eyes from a webcam and can
output a value representing your attention. 

**Use Case:**
This program could be used in applications like zoom to track the general attention of a group and give real time feedback to the teacher as a graphical representation.

**Fonctionality:**
To do so I check wether the person is looking at its screen and if his eyes are opened. I use a convolutional network to predict the coordinate of the eye gayes and an other convolutional network to predict the state of the eyes (close or opened). Then I use both these programs in a neural network to output an attention value that will averaged accross every 10 seconds frames.
