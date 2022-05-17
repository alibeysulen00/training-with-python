# Real-time object identification and classification

!! in this project, the training process of weight files will not be mentioned

Written in Python, this project performs real-time object identification and classification
- After training the tagged dataset, weighting files are created so that we can perform real-time object identification and classification
- after performing our darknet and drive connections, we perform our test with the make command if an error is not encountered, we pull our config and weight files from our user's network
- Now that we have a trained data set available, we can proceed to the test stage
- we are testing our test data that has already been created and created with about 20% of the data set
- it's time to knock on opencv's door :)
- we are using the opencv library for real-time detection, and finally we are now able to do classification and object detection

Libraries;
- OpenCV
- Numpy
- PIL
- io
- matplotlib
