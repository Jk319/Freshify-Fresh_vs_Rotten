# Fresh_vs_Rotten
# Exciting News! 🎉 
 
I am thrilled to announce a major milestone in academic I have successfully published my research paper in the 4th IEEE International Conference, International Conference on Computing, Communication, and Intelligent Systems (ICCCIS)!

My paper, centered around "Classification of Rotten Fruits vs Fresh Fruits Using Sequential Model with Convolutional Neural Network," reflects my dedication and expertise in this fascinating field. Thrilled to contribute to the intersection of technology and agriculture, paving the way for a smarter and more efficient approach to fruit quality assessment. 🔗 

The entire process, from research to writing and submission, was both challenging and immensely rewarding Being featured in the IEEE conference in a significant achievement that will undoubtedly elevate my profile as a researcher and propel my career forward.

   I want to express my heartfelt thanks to my colleagues, mentors. Exciting times ahead, and I eagerly anticipate sharing more of my work with the broader academic community. Here's to embracing the future and all the possibilities it holds! 
 
IEEE Paper Link: https://lnkd.in/dxiSgriG
Conference Link: https://lnkd.in/d8nvrHvQ 

#  Freshify - Fresh vs Rotten Fruit Classification using CNN

A deep learning-based image classification system that detects whether a fruit (apple, banana, or orange) is fresh or rotten using Convolutional Neural Networks (CNN). This project demonstrates the power of computer vision in agricultural and supply chain automation.

---

##  Overview

- **Goal:** Classify fruit images as *fresh* or *rotten* using a CNN model.
- **Dataset:** ~13,599 images (apples, bananas, oranges — fresh & rotten).
- **Approach:** Preprocess images → Augment data → Train CNN → Evaluate accuracy.

---

##  Dataset

- **Source:**  Real Images + [Kaggle - Rotten vs Fresh Fruits Dataset](https://www.kaggle.com/datasets)
- **Categories:**  
  - Fresh Apple, Banana, Orange  
  - Rotten Apple, Banana, Orange  
- **Total Images:** 13,599  
  - **Training Set:** 10,901  
  - **Test Set:** 2,698  
- **Image Size:** Resized to 224x224 pixels

---

## 🔧 Technologies Used

- **Language:** Python  
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy, Matplotlib  
- **Framework:** Sequential CNN model (custom-built)

---

##  Preprocessing Steps

- Image resizing  
- Normalization  
- Data augmentation (rotation, flipping, zoom) to improve generalization  
- Label encoding for classification (Fresh = 0, Rotten = 1)

---

##  CNN Model Architecture

- **Conv2D + ReLU** layers for feature extraction  
- **MaxPooling2D** for spatial downsampling  
- **Dropout layers** to prevent overfitting  
- **Fully connected (Dense) layers** for classification  
- **Sigmoid activation** in the output layer for binary classification

---

##  Results

| Metric     | Value     |
|------------|-----------|
| Accuracy   | 98.79%    |
| Loss       | 0.0337    |
| Model Type | Custom CNN |

- **Evaluation Tools:**  
  - Accuracy & loss plots  
  - Confusion Matrix  
  - Classification Report (Precision, Recall, F1-score)

---

##  Sample Predictions

- ✅ Fresh Banana → Classified correctly  
- ❌ Rotten Orange → Misclassified as Fresh (example for error analysis)

---

##  Folder Structure
```plaintext

FreshVsRotten/
├── images/                 # Sample fruits images
├── models/                 # Trained CNN model
├── trainingonefruit.ipynb  # Model training notebook
├── testingonefruit.ipynb   # Model testing notebook
├── README.md               # Documentation
└── requirements.txt        # Dependencies
```

##  Conclusion

The model achieved **98.79% accuracy**, showing its robustness in classifying fresh and rotten fruits. It demonstrates the potential of CNNs in solving real-world agricultural quality control problems.

---

##  Future Enhancements

- Deploy the model as a web or mobile app for real-time detection  
- Expand to more fruit types and include degree-of-ripeness classification  
- Use Transfer Learning for faster and potentially better results

---

## 👨‍💻 Author

**Jatin Kushwaha**  
[GitHub](https://github.com/Jk319) | [LinkedIn](https://linkedin.com/in/jatin-kushwaha)

---

## 📄 License

This project is for academic and research purposes only.

