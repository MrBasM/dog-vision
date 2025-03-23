# 🐶 Dog Vision - CNN Dog Breed Classifier

This project is part of the **Complete A.I. Machine Learning and Data Science: Zero to Mastery** course. It is a computer vision project where a Convolutional Neural Network (CNN) is trained to classify dog images by breed.

## 📚 Project Description

The goal of this project is to build and train a deep learning model that can accurately recognize dog breeds from images. This includes:

- Loading and preparing image data
- Creating a custom CNN using TensorFlow and Keras
- Training and evaluating the model
- Visualizing performance metrics like accuracy and loss

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy & Pandas
- Matplotlib & Seaborn
- Google Colab (for training with GPU)

## 📁 Project Structure

```
dog-vision/
│
├── dog_vision.ipynb               # Main Jupyter notebook for model training and testing
├── data/                          # Folder containing training and test images
├── model/                         # Saved model files (optional)
├── predictions/                   # Example predictions
├── utils.py                       # Custom helper functions (optional)
├── requirements.txt               # List of required packages
└── README.md                      # This documentation
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/MrBasM/dog-vision.git
   cd dog-vision
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook in Jupyter or Google Colab:
   ```bash
   jupyter notebook dog_vision.ipynb
   ```
   Or upload to [Google Colab](https://colab.research.google.com/) for free GPU training.

## 📈 Results

- Training Accuracy: ~XX%
- Validation Accuracy: ~XX%
- Final Test Accuracy: ~XX%

> Replace `XX%` with your actual results once training is complete.

## 🧪 Example Predictions

Here are a few example predictions made by the model:

| Image | Predicted Breed |
|-------|------------------|
| ![](predictions/dog1.jpg) | Labrador Retriever |
| ![](predictions/dog2.jpg) | Golden Retriever |

*(Add your own images and results)*

## 📌 Future Improvements

- Add more dog breeds or a larger dataset
- Apply transfer learning with a pretrained model (e.g. EfficientNet, MobileNet)
- Build a front-end demo using Gradio or Streamlit
- Add data augmentation for better generalization

## 📄 License

This project is for educational purposes only, developed as part of a learning journey in deep learning and computer vision.

---

Made with ❤️ by [Mr. Bas](https://github.com/MrBasM)
