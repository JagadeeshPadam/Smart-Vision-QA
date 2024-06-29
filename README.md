# Smart Vision QA

Smart Vision QA is a web application that utilizes computer vision and natural language processing to answer questions based on images captured via a webcam.

## Features

- Capture an image using the webcam.
- Process the image to recognize objects or scenes.
- Accept voice input for questions.
- Provide answers based on the processed image and voice input.

## Prerequisites

Before running the application, ensure you have the following installed:

- Python 3.x
- Flask (`pip install Flask`)
- pyttsx3 (`pip install pyttsx3`)
- OpenCV (`pip install opencv-python`)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/JagadeeshPadam/Smart-Vision-QA.git
   cd Smart-Vision-QA

## Folder Structure

Smart-Vision-QA/
│
├── app.py                # Main application file
├── config.py             # Configuration file (contains API key)
├── API.py                # API handling functions
├── static/               # Static assets (CSS, images)
└── templates/            # HTML templates
    ├── index.html        # Landing page
    └── chat.html         # Chat interface

Replace `"YOUR_API_KEY"` with the actual placeholder for your API key in `config.py`. Adjust any other specific details to match your project setup.
