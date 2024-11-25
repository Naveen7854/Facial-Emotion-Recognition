# Facial Emotion Recognition

This project focuses on leveraging **Convolutional Neural Networks (CNNs)** to recognize facial emotions in real-time. It addresses the challenges in facial expression recognition for applications in **mental health diagnosis**, **human-machine interaction**, and **artificial expression synthesis**.

---

## Features
1. **Dataset**: Utilized the **FER2013 dataset** containing 48x48 pixel grayscale images labeled with seven emotions: Anger, Disgust, Fear, Happiness, Neutral, Sadness, and Surprise.
2. **Data Augmentation**: Applied transformations such as rotation, zooming, and flipping to enhance model robustness.
3. **Model Variants**:
   - CNNs with **2 convolutional layers** and **2 dense layers**.
   - CNNs with **3 convolutional layers** and **3 dense layers**.
4. **Performance**:
   - **Accuracy**: Up to **64.84%** on the test set.
   - **Metrics**: Precision, recall, and F1 scores included for comprehensive evaluation.

---

## Real-Time Emotion Detection
- Integrated with a live webcam feed using **OpenCV**.
- Recognizes emotions in real-time with predictions overlaid on detected faces.

---

## Future Enhancements
- Experiment with advanced optimizers like **RMSprop** and **Adagrad**.
- Increase dataset size for better generalization.
- Implement multimodal approaches (e.g., combining audio and visual data).

---

## Resources
- **Supervisor**: Dr. Muneendra Ojha
- **Repository**: [GitHub - Naveen7854](https://github.com/Naveen7854)
- **Institute**: Indian Institute of Information Technology, Allahabad
- **Dataset**: https://www.kaggle.com/datasets/nicolejyt/facialexpressionrecognition
