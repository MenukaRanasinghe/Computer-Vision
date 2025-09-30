🌿 Plant Disease Detection

  This project demonstrates a web application that utilizes deep learning models to identify plant diseases from leaf images. Built with Flask and TensorFlow, it serves as a practical tool for farmers, researchers, and enthusiasts to diagnose plant health issues efficiently.

📌 Project Overview

  The application employs two deep learning models:
    CNN Model: A Convolutional Neural Network trained to classify plant diseases.
    Transfer Learning Model: A model leveraging pre-trained networks to enhance classification accuracy.
  These models were trained on the PlantVillage Dataset, which contains images of healthy and diseased leaves from various plant species.

🧠 Dataset

  The dataset used is the PlantVillage Dataset, comprising over 87,000 RGB images categorized into 38 classes, including:
    Bell Pepper (healthy and diseased)
    Potato (Early Blight, Late Blight, healthy)
    Tomato (various diseases and healthy)
  This diverse dataset enables the models to learn and predict a wide range of plant diseases.

⚙️ Technologies Used

  Backend: Python, Flask
  Deep Learning Framework: TensorFlow, Keras
  Frontend: HTML, CSS, JavaScript
  Model Formats: .keras (saved models)

🚀 Features

  Upload a leaf image through the web interface.
  Predict the plant species and its disease status.
  Receive predictions from both CNN and Transfer Learning models.
  View the uploaded image along with the prediction result.

🛠️ Setup Instructions

  1. Clone the repository:
    git clone https://github.com/MenukaRanasinghe/Computer-Vision.git
    cd plant-disease-detection

  2. Install dependencies:
    pip install -r requirements.txt

  3. Place your trained models (Plant_Disease_Model1.keras and Plant_Disease_Model2.keras) in the project directory.

  4. Run the Flask application:
    python app.py

  5. Open your browser and navigate to http://127.0.0.1:5000/ to use the application.

📷 Example Interface

  Above: Screenshot of the Leaf Disease Detection Flask App interface.

📄 License

  This project is licensed under the MIT License.

📌 Acknowledgments

  PlantVillage Dataset for providing the dataset.
  TensorFlow and Keras for the deep learning frameworks.
  Flask for the web application framework.
