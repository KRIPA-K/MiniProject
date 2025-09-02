🌱 Crop Disease Detection System
📌 Overview

This mini-project is an AI-powered Crop Disease Detection System that leverages Deep Learning to identify plant diseases from images.
It is designed to help farmers and researchers detect crop diseases early, ensuring better yield and reduced losses.

The project includes:

📊 Model Training (Train.ipynb)

🧪 Model Testing (Test.ipynb)

🚀 Deployment Script (main.py)

📈 Training Logs (training_hist.json)

🚀 Features

🌿 Upload crop/leaf images and get instant disease detection results.

🧠 Built using Convolutional Neural Networks (CNNs) for image classification.

📉 Training history and evaluation metrics available for model improvement.

🖥️ Easy to use deployment with a Python script (main.py).

🛠️ Tech Stack

Programming Language: Python 🐍

Deep Learning: TensorFlow / Keras

Data Handling: NumPy, Pandas

Visualization: Matplotlib, Seaborn

Deployment: Streamlit / Flask (if used in main.py)

📂 Project Structure
├── Train.ipynb          # Notebook for training the CNN model
├── Test.ipynb           # Notebook for testing & evaluation
├── main.py              # Deployment script for inference
├── training_hist.json   # Training history (loss & accuracy logs)
├── requirements.txt     # Dependencies (if needed)
└── README.md            # Documentation (this file)

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/your-username/crop-disease-detection.git
cd crop-disease-detection


Create virtual environment (recommended)

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


Install dependencies

pip install -r requirements.txt


Run training (optional)

jupyter notebook Train.ipynb


Run testing

jupyter notebook Test.ipynb


Run deployment script

python main.py

📊 Usage

Prepare your dataset of crop images (healthy & diseased).

Train the CNN model using Train.ipynb.

Evaluate the model on test data using Test.ipynb.

Use main.py to predict diseases from new crop images.

📈 Training History

The file training_hist.json contains accuracy and loss logs from model training.
You can visualize it with Matplotlib/Seaborn for deeper analysis.

🌾 Applications

Early disease detection in crops.

Precision agriculture & smart farming.

Reducing crop yield losses.

Assisting farmers with AI-driven insights.

🤝 Contribution

Contributions are welcome!

Fork the repo

Create a new branch (feature-branch)

Commit your changes

Open a Pull Request
