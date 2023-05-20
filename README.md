# Emotion-Detection

The program is a facial emotion detection system using Python. It utilizes OpenCV for face detection and a pre-trained deep learning model to predict the corresponding emotion for each detected face.

To run the program, follow these instructions:

1. Make sure you have Python installed on your system. You can download it from the official Python website (https://www.python.org/) if needed.

2. Install the necessary libraries by running the following command in your command prompt or terminal:
   ```
   pip install opencv-python tensorflow
   ```

3. Save the provided code into a Python file, for example, `facial_emotion_detection.py`.

4. Download the pre-trained model file for emotion detection (`emotion_model.h5`) and place it in the same directory as the Python file. You can find pre-trained models online or train your own using deep learning techniques.

5. Open a command prompt or terminal and navigate to the directory containing the Python file and the pre-trained model.

6. Run the program by executing the following command:
   ```
   python facial_emotion_detection.py
   ```

7. The program will open your webcam and display the live video stream. It will detect faces in the video stream and predict the corresponding emotions, drawing rectangles around the faces and displaying the predicted emotion labels.

8. Press the 'q' key to exit the program.

Ensure that you have a working webcam connected to your system, and make sure the lighting conditions are adequate for accurate facial emotion detection.

That's it! You can now run the facial emotion detection program and observe the predicted emotions in real-time.
