# Covid-19-detector
Simple VGG-16 based Covid-19 detector.
The steps are as follows.

- Load TensorFlow, Keras and Python libraries.
- Load the Covid free and with Covid chest X-ray images.
- Preprocess the data.
- Load the VGG16 network.
- Add a head layer to the model to train on Covid detection.
- Train the model on training data.
- Evaluate the model on test data.
- Use the model for predictions.
- Verify predictions.
