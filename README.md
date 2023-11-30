# ASL Recognition Model
An LSTM model that recognizes alphabets from the American Sign Language using Mediapipe and Tensorflow. It uses mediapipe to get landmarks of the left and right hands and passes it through the LSTM model.
## Dependencies required
- Tensorflow
- Mediapipe
- OpenCV
- NumPy
- scikit-learn

**Installation**: `pip install tensorflow opencv-python scikit-learn numpy mediapipe`

# Working
After running the python notebook we get a webcam stream with the predicted alphabet displayed in the window as below:

<img src="/assets/images/aslDemo.png" alt="image" width="40%" height="auto">
