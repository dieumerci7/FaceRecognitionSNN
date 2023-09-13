# FaceRecognitionSNN

## Description

 Given an image with predefined instances, I do the next:
 - perform face detection on the image using Haar Cascade Classifier, resulting in bounding boxes of all the faces;
 - use the predefined instances to perform face recognition. I use a Siamese Neural Network (SNN) for that. The SNN uses a RegNet-based model as a feature extractor.

## Table of Contents

- [Usage](#usage)
- [Data](#data)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

# Usage
To use this repository, follow these steps:

Clone the repository to your local machine. Install the required libraries specified in the notebook, typically using pip or conda. Open and run the Jupyter Notebook (`FaceRecognition.ipynb`) to train the model and perform face recognition.

# Data
- The training data may be downloaded from here: https://drive.google.com/file/d/1TmzyF9I28nj9_Wz33JVBkNnz_KpoBzr5/view?usp=sharing. My code uses only the `Extraced Faces` subdirectory, but feel free to train with the rest of the images, if it suits your purposes.
- The inference data may be found here: https://drive.google.com/file/d/1i1bSe89HCPqADHXDOfP9Xcq1XC67MXUX/view?usp=sharing.
- If you wish to use the pretrained model, look no further: https://drive.google.com/file/d/1-5NnddaCalayLBwJyAyZT3tU9aGMuRe8/view?usp=sharing.

# Author
Bohdan-Yarema Dekhtiar

# Acknowledgments
Thanks to It-Jim (https://www.it-jim.com/) for providing all the required data. Particular gratitude to the Armed Forces of Ukraine for keeping me safe and able to work with such projects.

# Contact
For any inquiries or issues regarding this repository, please contact yarema.dekhtiar@gmail.com.
