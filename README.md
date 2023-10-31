# face-recognition-system
Face Recognition System Using Digital Image Processing Techniques.

## Running the Program:
* Install the libraries, opencv-python and opencv-contrib-python.
    * pip install opencv-python
    * pip install opencv-contrib-python
* Run the preprocessing.py. It will ask for the name of the person and capture 40 images through the webcam. These images will be used for training of the model.
* After capturing the images, run face_recog.py. A webcam window will be opened where the name of the person in the webcam is recognized and displayed.

## Exiting the Program:
The program runs indefinitely until the user presses the 'q' key, at which point it releases the webcam and closes all OpenCV windows, terminating the script.

