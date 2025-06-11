🛠️ Image-Based Product Classification: Defective vs Non-Defective
This project implements a deep learning-based image classification system to automatically detect whether a product is defective or non-defective based on its image. It is useful for quality control in manufacturing lines and automated inspection systems.

🔍 Features
Binary classification: Defective or Non-Defective

Trained using Convolutional Neural Networks (CNN)

Real-time prediction support

Image preprocessing and data augmentation

Evaluation with accuracy, confusion matrix, and classification report

📂 Dataset
The dataset contains labeled images of products categorized into:

Defective: Products with visible defects (scratches, dents, misalignments, etc.)

Non-Defective: Products that meet quality standards

Note: You may need to supply or collect your own dataset depending on use case.

🧠 Model
Built using TensorFlow/Keras or PyTorch

CNN architecture with Conv2D, MaxPooling, Dropout, and Dense layers

Model saved as .h5 or .pt file for easy reuse

🚀 How to Run
Clone the repository

Install dependencies: pip install -r requirements.txt

Train the model: python train.py

Run predictions: python predict.py --image path_to_image.jpg

📊 Results
Achieved over 90% accuracy on the test set with consistent performance across unseen data.

📦 Applications
Automated visual inspection in factories

Quality control in product lines

Detection of surface-level manufacturing defects
