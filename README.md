# Gender Identification using 5-Layer CNN

## Project Overview
This project focuses on building an optimized Deep Learning model to classify gender from facial images. The model was developed using **TensorFlow/Keras** and achieved an impressive **98% accuracy** on the Kaggle Gender Classification dataset.

## Key Technical Features
- **Architecture:** A custom-built 5-layer Convolutional Neural Network (CNN).
- **Optimization:** Used **AdamW** optimizer with **L2 Regularization** to prevent overfitting.
- **Data Pipeline:** Implemented advanced **Data Augmentation** (rotation, zoom, brightness) to improve model generalization.
- **Handling Imbalance:** Computed **Class Weights** to ensure fair learning across different classes.
- **Custom Metrics:** Developed a custom **F1-Score metric** for more reliable performance evaluation beyond simple accuracy.
- **Advanced Training:** Utilized **Cosine Annealing Learning Rate Scheduler** and **Early Stopping** to reach the optimal global minima.

## Performance
- **Test Accuracy:** 98%+
- **Evaluation:** High F1-Score, demonstrating robustness in binary classification.

## Tools & Libraries
- Python, TensorFlow, Keras
- NumPy, Matplotlib, Seaborn (for visualization)
- Scikit-learn (for evaluation metrics)

## How to use
The code is designed to run in a Kaggle environment or locally with a GPU.
