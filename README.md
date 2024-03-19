**Image-to-Text Web Application using Flask and ResNet50**    
This repository contains the source code for a web application that converts images into descriptive text captions using a combination of Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs). The application is built using Python and Flask framework, and it utilizes a pre-trained ResNet50 model for feature extraction and a custom LSTM-based model for generating text captions.

**Features**  
Upload an image through the web interface.  
Process the image using ResNet50 for feature extraction.  
Generate descriptive text captions for the image using a trained LSTM-based model.  
Display the generated captions on the web interface.

**Prerequisites**  
Before running the application, ensure you have the following dependencies installed:  
Python (3.x recommended)  
Flask  
OpenCV (cv2)  
TensorFlow  
Keras  
NumPy  
tqdm  
You can install these dependencies using pip commands.

**Dataset used**  
flickr8k_sau

**Usage**  
Clone this repository to your local machine:  
git clone https://github.com/aqsaa2/imagecaptioning.git  
Navigate to the project directory:  
cd imagecaptioning  
Run the Flask application:  
python app.py  
Open a web browser to access the application.  

Upload an image through the web interface and wait for the text caption to be generated.

**File Structure**  
app.py: Main Flask application file containing routes and logic.  
templates/: Directory containing HTML templates for the web interface.  
index.html: Homepage template with image upload form.  
output.html: Template to display the generated text caption.  
static/: Directory for storing static files (e.g., uploaded images).  
vocab.npy: File containing vocabulary mappings for text generation.  
mine_model_weights.h5: Pre-trained weights for the LSTM-based model.

**Model Architecture**  
ResNet50: Pre-trained CNN model used for image feature extraction.  
LSTM-based Model: Custom model architecture comprising an embedding layer, LSTM layers, and dense layers for text generation.

**Acknowledgments**  
This project utilizes the power of deep learning and natural language processing techniques.  
The Flask framework is used for building the web application.  
Pre-trained models such as ResNet50 and LSTM have been employed for efficient feature extraction and text generation.

**Credits**  
This project was inspired by various tutorials and resources available online.
