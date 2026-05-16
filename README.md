# 🌿 Plant Disease Classifier: AI for Healthy Crops!

## 🚀 Project Overview

This notebook presents a high-performance **Plant Disease Classification AI model**, built using **EfficientNet-B3 with Squeeze-Excitation (SE) attention**. Our goal is simple: accurately identify plant diseases from images, making this powerful technology accessible for real-world applications, especially on **mobile devices**.

## ✨ Key Features & Achievements

*   **Blazing Accuracy:** Achieved an outstanding **0.9932 Macro-F1 score** on unseen test data across 37 diverse plant disease classes. This means near-perfect identification!
*   **No Overfitting:** Rigorous analysis confirms the model generalizes exceptionally well, performing consistently on new data without just memorizing training examples.
*   **Trustworthy AI (GradCAM):** We use **GradCAM visualizations** to show *exactly what the model sees* when making a diagnosis. It focuses on the actual disease lesions, not background noise, ensuring reliable and interpretable predictions.
*   **Mobile-Ready:** Exported as an **ONNX model**, optimized for seamless integration into mobile applications (Android/iOS), bringing AI diagnostics directly to farmers and enthusiasts.
*   **Robust Training:** Implemented advanced techniques like **Label Smoothing**, **Focal Loss** for challenging cases, and **CutMix/MixUp** augmentations to build a resilient model.

## 🔬 How it Works (in a Nutshell)

1.  **Data Preparation:** Images of 37 plant diseases are processed, cleaned, and split into training, validation, and test sets. Heavy augmentation ensures the model learns robust features.
2.  **Model Training:** An EfficientNet-B3 neural network, enhanced with SE attention, is trained to classify diseases. We carefully manage learning rates and use mixed precision for speed and efficiency.
3.  **Rigorous Evaluation:** We don't just stop at accuracy! Detailed metrics (Macro-F1, Confusion Matrix, Per-Class F1) and GradCAM visualizations ensure the model is not only accurate but also reliable and interpretable.
4.  **Mobile Deployment:** The trained model is converted to the ONNX format, making it lightweight and fast for mobile inference.

## 🎯 Impact for Stakeholders

This project delivers a **highly reliable and interpretable AI solution** for plant disease detection. It directly supports:

*   **Increased Crop Yield:** Faster, accurate diagnosis means quicker treatment and healthier plants.
*   **Sustainable Practices:** Reduced unnecessary pesticide use through precise identification.
*   **Empowering Farmers:** Easy-to-use mobile tools bring advanced diagnostics to every farm.

## 📊 Visual Highlights

*   **`training_curves.png`**: See how stable and effective our training process was.
*   **`confusion_matrix.png`**: A visual proof of minimal confusion between disease types.
*   **`per_class_f1.png`**: Shows consistent high performance across *every single disease class*.
*   **`gradcam_hard_pairs.png`**: Witness the AI focusing precisely on disease lesions, demonstrating its intelligence.
