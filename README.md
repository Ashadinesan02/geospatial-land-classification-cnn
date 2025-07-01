# Geospatial Land Classification via Image Processing using CNN


## 🎯 Project Objective

To build a Convolutional Neural Network (CNN) model for classifying geospatial land types using satellite imagery, with a focus on detecting agricultural land and identifying specific crop types through image segmentation and color analysis. This project demonstrates practical applications in remote sensing, precision agriculture, and land-use monitoring.



## 🧠 Key Skills Demonstrated

- **Deep Learning** – Built and optimized a CNN model for satellite image classification.
  
- **Image Processing** – Used segmentation and color detection to identify crop regions.
  
- **Geospatial Analysis** – Interpreted satellite imagery for land-use mapping.
  
- **Python Programming** – Developed preprocessing, training, and testing scripts in Python.
  
- **TensorFlow & Keras** – Employed deep learning libraries for model development.
  
- **Data Handling** – Processed large-scale geospatial image datasets efficiently.
  
- **Problem Solving** – Tackled real-world agricultural monitoring challenges.



## 📂 Project Structure

├── train.py            # CNN model for training on satellite images
├── test.py             # Loads model & performs land/crop classification
├── requirements.txt    # Python dependencies for local use (optional)
├── images/             # Folder with sample satellite image data
├── model/              # Folder to store saved.h5 model files
├── README.md           # Project documentation


📌 **Dataset**: [UC Merced Land Use Dataset](http://weegee.vision.ucmerced.edu/datasets/landuse.html)  
Note: Model weights (.h5) and large image files are excluded from repo.



## 🚀 How to Run (Google Colab Recommended)

1. Open Google Colab

2. Upload the following files:
train.py, test.py, and sample images

3. Install dependencies:
!pip install -r requirements.txt

4. Run the files:
%run train.py
%run test.py



## 🧾 Output Summary

The model successfully classifies satellite land types such as urban, forest, and agricultural areas. For agricultural zones, it further detects specific crop types (e.g., Red Spinach, Green Wheat, Tea) using segmentation and color analysis techniques.
📂 Output images are available in the output/ folder.



## 📄 **Research Publication**

This project has been officially published as part of a research paper, highlighting its academic and real-world relevance in the field of geospatial analysis and agricultural monitoring.

📘 Paper Title: Geospatial Land Classification via Advanced Image Processing using CNN
🔗 Publication Link: [https://ijisrt.com/assets/upload/files/IJISRT24MAR1914.pdf]



## 📍**Contact**

Email: ashadinesan002@gmail.com
LinkedIn: https://www.linkedin.com/in/asha-d-59026424a




