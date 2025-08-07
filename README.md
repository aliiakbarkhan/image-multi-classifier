# Multi-Class Image Classifier using Deep Learning

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

A deep learning image classifier that distinguishes between various object types like **birds**, **donkeys**, **houses**, **forests**, and even **certificates**, built for fun, exploration, and practical understanding of vision models.

---

## Project Description

This project uses a convolutional neural network (CNN) to perform **multi-class image classification**.  
By training on a custom dataset with diverse categories (including animals, buildings, natural elements, and documents), this model showcases how well deep learning can generalize across very different image types.

---

## Author

**Ali Akbar Khan**

---

## Technologies Used

- Python  
- Fastai  
- PyTorch  
- Jupyter Notebook  
- Gradio (optional UI) 

---

## Model Details

- **Architecture**: `resnet18` pretrained CNN  
- **Training**: Fine-tuned using Fastai's `vision_learner`  
- **Metric**: Achieved high validation accuracy on mixed-category data

---

## Dataset

The model can classify images into the following categories:

-  Bird  
-  Donkey  
-  House  
-  Forest  
-  Certificate  

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/aliiakbarkhan/image-multi-classifier.git
cd image-multi-classifier
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the notebook

Use Jupyter or VSCode to open waste-segregation.ipynb and run all cells.

### 4. Or launch Gradio app (if available)
```bash
python eye_app.py
```
### Sample Predictions
The model can take any image of retina and classify it into one of the predefined categories with high accuracy.
Here's a snapshot of predictions from the Gradio interface.

<img src="https://github.com/aliiakbarkhan/image-multi-classifier/blob/main/output.png" />

### File Structure
```bash
image-multi-classifier/
├── is-it-a-bird-model.ipynb   # Main training/testing notebook
├── model.pkl                  # Trained model (optional)
├── app.py                     # Gradio app (optional)
├── README.md                  # Project documentation
└── requirements.txt           # Dependencies
```



