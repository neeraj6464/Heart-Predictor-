🔬 DermaScan: Skin Cancer Detection System
A high-efficiency deep learning web application capable of detecting 7 different types of skin cancer from dermoscopic images.

Last Commit Python TensorFlow Streamlit


📖 Overview
DermaScan is an AI-powered diagnostic tool designed to assist in the early detection and classification of skin lesions. Leveraging a highly efficient MobileNetV2 transfer learning architecture, the model runs swiftly on both CPU and GPU environments without compromising on accuracy.

The application features a sleek, dark-themed Streamlit user interface, allowing users to upload dermoscopic images and receive real-time diagnostic predictions alongside confidence scores.

Features
⚡ High-Efficiency Inference: Powered by MobileNetV2, optimized for web deployment.
🎨 Modern UI: A responsive, animated, glassmorphism-inspired dark mode interface.
📊 Detailed Diagnostics: Provides probability breakdowns across all 7 cancer classes.
📄 PDF Reporting: Automatically generates downloadable PDF diagnostic reports.
🧠 Optimized Training Pipeline: Utilizes tf.data for seamless handling of massive datasets.
🗄️ Dataset
This model is trained on the renowned HAM10000 dataset (Human Against Machine with 10000 training images), a massive collection of dermatoscopic images of common pigmented skin lesions.

🔗 Download the Dataset from Kaggle

Note: The dataset is over 2.5GB and is explicitly ignored in this repository. If you wish to retrain the model locally, please download the dataset from Kaggle and place the images in the dataset/ folder.

🧬 Supported Classifications
DermaScan is capable of identifying the following 7 diagnostic categories:

Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec)
Basal cell carcinoma (bcc)
Benign keratosis-like lesions (bkl)
Dermatofibroma (df)
Melanoma (mel)
Melanocytic nevi (nv)
Vascular lesions (vasc)
🚀 Getting Started (Local Development)
Prerequisites
Make sure you have Python 3.9+ installed on your machine.

Installation
Clone the repository:

git clone https://github.com/pravinkodle19/DermaScan.git
cd DermaScan
Create a virtual environment (Recommended):

python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
Install the dependencies:

pip install -r requirements.txt
Running the Application
To launch the web interface locally:

streamlit run app.py
The app will automatically open in your browser at http://localhost:8501.

🧠 Retraining the Model
If you wish to retrain or fine-tune the model:

Download the HAM10000 dataset from the link above.
Extract all images into the dataset/ directory.
Ensure the HAM10000_metadata.csv file is in the dataset/ directory.
Run the training script:
python train.py
The new model (skin_cancer_model.keras) and label encoder (class_names.pkl) will be automatically saved to the models/ directory.

☁️ Deployment
DermaScan is perfectly optimized to be deployed on Streamlit Community Cloud or Hugging Face Spaces.

Since the heavy dataset is .gitignore'd, you can simply point Streamlit Community Cloud to this repository, select app.py as your main file, and it will deploy instantly!
