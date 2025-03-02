# Sign Language to Speech Conversion

## Overview
This project aims to bridge the communication gap between the hearing and speech-impaired community and the general public by converting sign language into speech. The system leverages computer vision techniques and machine learning models to recognize hand gestures in real time and translate them into audible speech output.

## Features
- **Real-time Gesture Recognition**: Uses OpenCV to detect and classify hand gestures.
- **Speech Conversion**: Implements Google Text-to-Speech (gTTS) for converting recognized text into speech.
- **Deep Learning Model**: Utilizes a Convolutional Neural Network (CNN) trained on the MINT ASL dataset for accurate gesture classification.
- **Webcam Integration**: Captures hand gestures through a live video feed.
- **User-Friendly Interface**: Provides a seamless experience for users to interact and communicate effectively.

## Technologies Used
- **Python**
- **OpenCV** (for image processing)
- **TensorFlow/Keras** (for training the deep learning model)
- **Google Text-to-Speech (gTTS)** (for speech synthesis)
- **NumPy & Pandas** (for data manipulation)
- **MoviePy** (for video processing)

## Installation
### Prerequisites
Ensure you have Python installed (preferably Python 3.8+). Then, install the necessary dependencies:
```sh
pip install opencv-python numpy pandas tensorflow keras gtts moviepy
```

### Running the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/sign-language-to-speech.git
   cd sign-language-to-speech
   ```
2. Run the script:
   ```sh
   python main.py
   ```
3. Allow camera access and perform gestures to see the real-time translation.

## Dataset
The project uses the **MINT ASL dataset**, which contains labeled images of American Sign Language (ASL) gestures. The dataset is preprocessed and augmented for improved model accuracy.

## Model Training
The deep learning model is trained using TensorFlow/Keras with a CNN architecture. The training steps include:
1. Data Preprocessing: Image resizing, grayscale conversion, and augmentation.
2. Model Training: Using a CNN model with multiple convolutional and pooling layers.
3. Evaluation: Testing the model accuracy and fine-tuning hyperparameters.

## Future Enhancements
- **Support for More Sign Languages**: Expand beyond ASL to include ISL, BSL, etc.
- **Mobile Application**: Develop an Android/iOS app for real-world usability.
- **Gesture Sentence Prediction**: Implement NLP to predict full sentences based on gestures.

## Contributors
- **Kangkan Patowary** (Developer & ML Engineer)

## License
This project is open-source under the MIT License.

## Contact
For inquiries, reach out via:
- **Email**: kangkanpatowary18@gmail.com
- **LinkedIn**: [kangkan-patowary](https://www.linkedin.com/in/kangkan-patowary/)

