# Sign_Language_Detection

## Overview
This repository contains the code and files for my first computer vision project, focusing on sign language recognition. The goal of this project is to develop a machine learning model that can interpret sign language gestures using computer vision techniques.

## Project Structure
```
├── data/                   # Directory containing training and test datasets
├── signLanguage/            # Directory containing sign language recognition code
├── templates/               # Directory for HTML templates (if applicable)
├── yolov5/                  # YOLOv5 object detection model for real-time detection
├── .gitignore               # Git ignore file
├── Dockerfile               # Docker configuration file for containerization
├── LICENSE                  # License file
├── README.md                # Project documentation (this file)
├── app.py                   # Main application script
├── requirements.txt         # Python dependencies
└── setup.py                 # Setup script for the project
```

## Key Features
- **YOLOv5 Integration**: Used for real-time object detection and tracking.
- **Sign Language Recognition**: Trained model to recognize sign language gestures.
- **Docker Support**: Easily deploy the application using Docker.
- **Flask Backend**: Python Flask is used to serve the model and handle requests.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/BiswajitJena2002/first-computer-vision-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd first-computer-vision-project
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Run the Application

To start the application, simply run the `app.py` script:

```bash
python app.py
```

The application will be available at `http://localhost:5000/` in your browser.

### Docker

You can also use Docker to containerize the application:

1. Build the Docker image:
   ```bash
   docker build -t sign-language-recognition .
   ```
2. Run the Docker container:
   ```bash
   docker run -p 5000:5000 sign-language-recognition
   ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an issue if you have suggestions or ideas to improve the project.

## Contact
For any questions or inquiries, please contact [BiswajitJena2002](mailto:jbiswajitlife@gmail.com).

