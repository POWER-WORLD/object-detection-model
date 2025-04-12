<h1>🎯 Object Detection Model-</h1>
A simple yet effective Object Detection Model built using Python and OpenCV. This project uses computer vision techniques to detect objects in images or real-time video streams using a pre-trained model and Haar Cascade classifiers.

<h3>📌 Project Overview-</h3>
<ul>
<li>The objective of this project is to implement an object detection system capable of:</li>
<li>Detecting objects (faces, eyes, etc.) in images or real-time video</li>
<li>Drawing bounding boxes around detected objects</li>
<li>Displaying the detection in real-time using OpenCV windows</li>
<li>This project serves as a great introduction to computer vision concepts and OpenCV's object detection capabilities.</li>
</ul>
<h3>✨ Features-</h3>

✅ Real-time object detection using webcam<br>
✅ Bounding box and label on detected objects<br>
✅ Supports Haar Cascade classifiers (for face, eyes, etc.)<br>
✅ Simple, clean, and beginner-friendly Python code<br>
✅ Easy to customize with different pre-trained models<br>

<h3>🛠️ Technologies Used-</h3>
1.Python 3<br>
2.OpenCV (cv2)<br>
3.Haar Cascade XML Classifiers<br>

<h3>📁 Project Structure-</h3>
object-detection-model/<br>
│<br>
├── haarcascade_frontalface_default.xml   # Pre-trained Haar Cascade for face detection<br>
├── object_detection.py                   # Python script for object detection<br>
├── README.md                             # Project documentation<br>
<h3>🚀 Getting Started-</h3>

<b>📦 Requirements</b><br>

1.Python 3.x<br>
2.OpenCV (pip install opencv-python)<br>

<b>📥 Installation</b><br>

Clone the repository:<br>
git clone https://github.com/POWER-WORLD/object-detection-model.git<br>

Navigate to the project directory:<br>
cd object-detection-model<br>

Install dependencies:<br>
pip install opencv-python<br>

<b>🎮 How to Run</b><br>

Ensure your webcam is connected (for real-time detection)<br>
Run the Python script:<br>
python object_detection.py<br>

A window will open showing the webcam feed with bounding boxes around detected objects (like faces).<br>
Press q to quit the window.<br>

<b>🧠 How It Works</b><br>
<ul>
<li>Loads a Haar Cascade XML file (pre-trained for object detection, like face detection)</li>
<li>Captures video frames using the webcam via OpenCV</li>
<li>Converts each frame to grayscale (Haar Cascades work better with grayscale images)</li>
<li>Detects objects within the frame using the loaded cascade classifier</li>
<li>Draws a bounding rectangle around detected objects</li>
<li>Displays the processed video frame in real-time</li>
<li>Closes when the user presses q</li>
</ul>
<b>🔍 Example Output</b><br>
screenshots or demo gifs of your detection window here — <br>
![Image Apr 12, 2025, 01_09_10 PM](https://github.com/user-attachments/assets/ee6b8a9b-ca47-4c48-b42c-5da1c0e81c5f)

<h3>🙌 Acknowledgements-</h3>
This project was built as part of my computer vision learning journey using Python and OpenCV. Inspired by OpenCV’s robust object detection tools.<br>
If you found this helpful, feel free to ⭐ star the repo and follow for more cool projects!

<h3>🔗 Explore More Projects by POWER-WORLD-</h3>
https://github.com/POWER-WORLD
