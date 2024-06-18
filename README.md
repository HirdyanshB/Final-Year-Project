# CogniView: Image Captioning and CCTV Integration
This project integrates image captioning with CCTV feeds using a CNN-LSTM model. It 
provides a web application for image captioning and real-time CCTV security monitoring.

Table of Contents
1. Introduction
2. Features
3. Installation
4. Usage
5. Model Architecture
6. Contributing
7. License

## Introduction
This project combines image captioning capabilities with CCTV integration to enhance 
security monitoring. The image captioning is powered by a Convolutional Neural Network 
(CNN) and Long Short-Term Memory (LSTM) network. The web application allows users to
upload images for captioning and view real-time CCTV footage with security alerts.

## Features
- Image Captioning: Generate captions for uploaded images using a CNN-LSTM model.
- CCTV Integration: View real-time CCTV footage and receive alerts.
- Web Application: User-friendly web interface for interacting with the image captioning and CCTV features.

## Installation
Prerequisites
Make sure you have the following installed:
- Python 3.8 or higher
- Git
- pip (Python package installer)
Install Required Libraries

Create a virtual environment and install the required libraries:
```
python -m venv env
env\Scripts\activate
pip install -r requirements.txt
```

If requirements.txt is not available, manually install the necessary libraries:
```
pip install numpy pandas tensorflow keras opencv-python flask
```

## Usage
Running the Web Application:
1. Activate the virtual environment
```
env\Scripts\activate
```

2. Start the Flask server:
```
python app.py
```

Open your web browser and go to: http://127.0.0.1:5000

 Image Captioning
- Navigate to the "Image Captioning" section.
- Upload an image to generate a caption.

CCTV Integration
- Navigate to the "CCTV" section.
- View the live CCTV feed and monitor for security alerts.

## Model Architecture
The image captioning model uses a CNN to extract features from the image and an LSTM to 
generate a sequence of words describing the image.
-  CNN: Convolutional layers extract spatial features from the image.
-  LSTM: Recurrent layers generate the caption based on the extracted features.
## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch: git checkout -b feature-name
3. Make your changes and commit them: git commit -m 'Add feature'
4. Push to the branch: git push origin feature-name
5. Open a pull request.
## License
This project is licensed under the MIT License. 