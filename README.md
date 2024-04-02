# Gesture-Recognition
Smart-TV Can Recognise Five Different Gestures Performed By The User Which Will Help Users Control The TV Without Using a Remote.

Problem Statement
Imagine you are working as a data scientist at a home electronics company that manufactures state-of-the-art smart televisions. You want to develop a cool feature in the smart TV that can recognize five different gestures performed by the user which will help users control the TV without a remote.

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

Gesture	Corresponding Action
  (1) Thumbs Up	Increase the volume.
  (2) Thumbs Down	Decrease the volume.
  (3) Left Swipe	'Jump' backwards 10 seconds.
  (4) Right Swipe	'Jump' forward 10 seconds.
  (5) Stop	Pause the movie.
Each video is a sequence of 30 frames (or images).

Objectives:
Generator: The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing, and normalization should be performed successfully.

Model: Develop a model that can train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

Write-up: This should contain the detailed procedure for choosing the final model. The write-up should start with the reason for choosing the base model, then highlight the reasons and metrics taken into consideration to modify and experiment to arrive at the final model.

Installation:
Run pip install -r requirements.txt to install all the dependencies.

Dataset:
You can download the dataset from here. The training data consists of a few hundred videos categorized into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. It looks like this: dataset

https://user-images.githubusercontent.com/29462447/86066087-d03cf680-ba8e-11ea-91f5-960b5f522a39.png

Results:

https://user-images.githubusercontent.com/29462447/86066095-d501aa80-ba8e-11ea-82d8-4681e20e310e.png

