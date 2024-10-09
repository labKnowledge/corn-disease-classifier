# Corn Disease Classifier

## Overview

The Corn Disease Classifier is an interactive web application that uses machine learning to identify diseases in corn plants from images. This project is powered by the EligApris ML Project and provides a user-friendly interface for farmers, agricultural researchers, and enthusiasts to quickly diagnose corn diseases.

Repository: [https://github.com/labKnowledge/corn-disease-classifier](https://github.com/labKnowledge/corn-disease-classifier)

## Features

- **Image Upload**: Users can upload images of corn leaves for analysis.
- **Camera Integration**: Capture images directly using the device's camera.
- **Machine Learning Classification**: Utilizes a TensorFlow model to classify corn diseases.
- **Detailed Disease Information**: Provides comprehensive information about identified diseases, including symptoms, causes, and management strategies.
- **Responsive Design**: Works on various devices and screen sizes.

## Supported Diseases

The classifier can identify the following conditions:

1. Healthy
2. Gray Leaf Spot
3. Blight
4. Common Rust

## Technologies Used

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (ES6+)
- TensorFlow.js
- EligApris TensorFlow ML Project

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/labKnowledge/corn-disease-classifier.git
   ```

2. Navigate to the project directory:
   ```
   cd corn-disease-classifier
   ```

3. Open `index.html` in a modern web browser.

Note: As this is a client-side application, you don't need to install any dependencies. However, you need an active internet connection for the TensorFlow.js and Tailwind CSS CDN links to work.

## Usage

1. Open the application in a web browser.
2. Click on "Choose File" to upload an image of a corn leaf, or click "Open Camera" to take a picture.
3. Once an image is selected or captured, click "Predict Disease" to analyze the image.
4. View the prediction result and detailed information about the identified disease or condition.

## Model Information

The machine learning model used in this project is based on the EligApris TensorFlow ML Project. It has been trained on a diverse dataset of corn leaf images to identify various diseases and healthy leaves.

## Contributing

We welcome contributions to improve the Corn Disease Classifier! If you'd like to contribute, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- EligApris TensorFlow ML Project for providing the machine learning model
- TensorFlow.js team for the excellent library
- Tailwind CSS for the styling utilities

## Contact

For any queries or suggestions, please open an issue on the GitHub repository.

---

Happy Corn Disease Classifying!