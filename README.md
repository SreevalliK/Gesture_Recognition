# Gesture_Recognition

Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognize five different gestures performed by the user which will help users control the TV without using a remote. The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:
  
    Thumbs up: Increase the volume
    Thumbs down: Decrease the volume
    Left swipe: 'Jump' backwards 10 seconds
    Right swipe: 'Jump' forward 10 seconds
    Stop: Pause the movie

Each video is a sequence of 30 frames (or images)

In this group project, you are going to build a 3D Conv model that will be able to predict the 5 gestures correctly. Please import the following libraries to get started. Once you have completed the code you can download the notebook for making a submission.

### Objectives:
<b> Generator:</b> The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing and normalization should be performed successfully.

<b>Model:</b> Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

<b>Write up:</b> This should contain the detailed procedure followed in choosing the final model. The write up should start with the reason for choosing the base model, then highlight the reasons and metrics taken into consideration to modify and experiment to arrive at the final model.
