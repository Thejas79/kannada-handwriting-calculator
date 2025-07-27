# kannada-handwriting-calculator
This project is a Kannada Handwriting Recognition Calculator built using Python, OpenCV, and machine learning techniques. It allows users to draw handwritten Kannada digits/operators and calculates the result by recognizing the input through a trained model.

📁 Project Structure
graphql
Copy
Edit
Kannada-Handwriting-Calculator-main/
├── dataset/                     # Training dataset (Kannada digits/symbols)
├── model/                       # Trained model files (e.g., .h5, .pkl)
├── gui.py                       # Main GUI for the calculator
├── predict.py                   # Prediction logic using trained model
├── train.py                     # Model training script
├── utils.py                     # Image preprocessing, drawing canvas, etc.
├── README.md                    # Instructions file
└── requirements.txt             # List of Python packages to install
⚙️ Requirements
Python 3.7+

Libraries listed in requirements.txt:

opencv-python

numpy

tensorflow or keras

tkinter

PIL

scikit-learn

🔧 Installation
Clone or download the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/Kannada-Handwriting-Calculator.git
cd Kannada-Handwriting-Calculator-main
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
🚀 How to Run the Project
🧮 Step 1: Run the Calculator
bash
Copy
Edit
python gui.py
A GUI window will appear.

You can draw Kannada digits and operators (like +, -, *, /) in the canvas area.

The program will recognize and compute the result automatically or on button click.

📊 Step 2 (Optional): Train the Model Yourself
If you want to retrain the model using your own dataset:

bash
Copy
Edit
python train.py
Ensure your dataset is in the correct format under the dataset/ folder.

🧠 Step 3: Use the Prediction Module
To test recognition directly:

bash
Copy
Edit
python predict.py image.png
Where image.png is a Kannada digit/operator image.

✨ Features
Recognizes handwritten Kannada digits (0-9)

Supports basic math operations: +, -, *, /

Interactive drawing GUI

Built with deep learning model

Can be retrained with custom datasets

🔍 Possible Enhancements
Support complex multi-digit expressions

Add voice output in Kannada

Improve GUI using PyQt or Kivy

Add real-time webcam-based digit recognition

🙏 Acknowledgements
Kannada MNIST dataset

TensorFlow/Keras framework

OpenCV and Tkinter for GUI and image handling

