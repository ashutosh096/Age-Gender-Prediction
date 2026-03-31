Age and Gender Prediction using OpenCV
A Python-based Computer Vision project that uses Deep Learning to predict the age and gender of a person from an image or through a real-time webcam feed.

📌 Features
Accurate Face Detection: Identifies faces even in noisy or poorly lit environments.

Multi-Face Support: Can detect and label multiple people in a single frame.

CNN-Powered: Uses trained Convolutional Neural Networks for classification.

Dual Mode: Works with static image files or live video streams.

🛠️ Tech Stack
Language: Python

Library: OpenCV (dnn module)

Models: Caffe, TensorFlow

Tools: NumPy, Argparse

Clone the Repository:

Bash
git clone https://github.com/yourusername/age-gender-prediction.git
cd age-gender-prediction
Install Dependencies:

Bash
pip install opencv-python numpy
Run the Script:

For Image:

Bash
python main.py --image image.jpg
For Webcam:

Bash
python main.py
📊 How it Works
Preprocessing: The input image is converted into a blob to make it compatible with the CNN input requirements (resizing to 227x227 and mean subtraction).

Detection: The face detector identifies the bounding box coordinates.

Prediction: The cropped face is passed through the Gender and Age networks, which return probability scores for each category.

Output: The final result is rendered with a rectangle and text label on the original image.

Built for Data Science portfolio inclusion.
![image alt](https://github.com/ashutosh096/Age-Gender-Prediction/blob/48769073bca9d516459ba0d93673076571d7a096/image%201.png)
