# Helping_Hand
<img src="https://user-images.githubusercontent.com/15254803/113495887-9340dd00-94c2-11eb-8965-c73ada8f6434.JPG" height="400" />

## Video Demo
https://youtu.be/rRl7A4UaKBI 

Built together with Shafinul Haque, Ronit Kothari, and Matthew Fernandes.

## Inspiration
Peripheral nerve compression syndromes such as carpal tunnel syndrome affect approximately 1 out of every 6 adults. They are commonly caused by repetitive stress and with the recent trend of working at home due to the pandemic it has become a mounting issue more individuals will need to address. There exist several different types of exercises to help prevent these syndromes, in fact studies show that 71.2% of patients who did not perform these exercises had to later undergo surgery due to their condition. It should also be noted that doing these exercises wrong could cause permanent injury to the hand as well. 

## What it does
That is why we decided to create the “Helping Hand”, providing exercises for a user to perform and using a machine learning model to recognize each successful try. We implemented flex sensors and an IMU on a glove to track the movement and position of the user's hand. An interactive GUI was created in Python to prompt users to perform certain hand exercises. A real time classifier is then run once the user begins the gesture to identify whether they were able to successfully recreate it. Through the application, we can track the progression of the user's hand mobility and appropriately recommend exercises to target the areas where they are lacking most.

## How we built it
The flex sensors were mounted on the glove using custom-designed 3D printed holders. We used an Arduino Uno to collect all the information from the 5 flex sensors and the IMU. The Arduino Uno interfaced with our computer via a USB cable. We created a machine learning model with the use of TensorFlow and Python to classify hand gestures in real time. The user was able to interact with our program with a simple GUI made in Python.

## What we learned
We learned how to collect real-time data from sensors and create various scripts to process the data. We also learned how to set up a machine learning model including parsing the data, splitting data into training and testing sets, and validating the model.


We would also like to create an app so that the user can conveniently perform these exercises anywhere, anytime. 

Lastly, we would like to implement an accuracy score of each gesture rather than a binary pass/fail (i.e. display a reading of how well you are able to bend your fingers/rotate your wrist when performing a particular gesture). This would allow us to more appropriately identify the weaknesses within the hand. 

