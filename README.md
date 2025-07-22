# Visionary-palette-Image-colorization-and-caption-generation.
Visionary Palette is a deep learning project that colorizes grayscale images using OpenCV and a pre-trained CNN model, and generates captions using CNN-Bi-LSTM architecture. It combines computer vision and NLP to enhance and interpret visual content effectively.

## Features

- Colorizes black-and-white images using a pre-trained CNN model and OpenCV
- Generates descriptive captions using CNN and Bi-LSTM
- Combines Computer Vision and NLP in a single application
- Optional web interface using Flask for real-time interaction

## Tech Stack

- **Languages**: Python
- **Libraries**: OpenCV, NumPy, TensorFlow/Keras
- **Models**:
  - Image Colorization: Pre-trained Caffe model
  - Caption Generation: CNN (e.g., InceptionV3) + Bi-LSTM

  visionary-palette/
├── colorization/
│ ├── colorize.py
│ ├── model/ (prototxt, .caffemodel)
├── captioning/
│ ├── caption_generator.py
│ ├── model/ (trained weights)
├── static/ (for web images)
├── templates/ (for Flask frontend)
├── app.py (Flask app)
├── requirements.txt
└── README.md
