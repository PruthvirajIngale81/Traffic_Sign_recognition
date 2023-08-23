Project Overview

The Traffic Sign Recognition project aims to demonstrate the application of AI and machine learning in recognizing traffic signs from images. The project includes a trained machine learning model and a Flask-based GUI for users to upload images and get real-time predictions for traffic signs.


Installation:

To get started with the project, follow these steps:

Clone the repository:

git clone https://github.com/PruthvirajIngale81/-Traffic_Sign_recognition.git

Navigate to the project directory:

cd -Traffic_Sign_recognition

Install the required packages using pip:

pip install -r requirements.txt


Usage:

Run the Flask application:

python app.py

Open a web browser and go to http://localhost:5000 to access the GUI.
Upload an image containing a traffic sign and submit it.
The application will display the recognized traffic sign and its prediction.


File Structure:


app.py: The Flask application script.
requirements.txt: List of required Python packages.
static/: Folder containing static files (CSS, images).
templates/: Folder containing HTML templates.
model/: Folder containing the trained machine learning model.


Technologies Used:

Python: Programming language for the backend.
Flask: Web framework for creating the GUI.
HTML and CSS: Structuring and styling the GUI.
TensorFlow/Keras: Framework for training and using the machine learning model.

Machine Learning Model:

The project uses a pre-trained machine learning model (traffic_sign_model.h5) to recognize traffic signs from images. This model was trained using a labeled dataset of traffic sign images.

Flask GUI:

The Flask-based GUI allows users to:

Upload an image containing a traffic sign.
Display the recognized traffic sign and its prediction.

Contributing:

Contributions to this project are welcome. Feel free to open pull requests for improvements or bug fixes.


Contact Information:

For any inquiries or feedback, contact your-email@example.com.


