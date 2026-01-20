This project focuses on detecting metastatic cancer from histopathology images using deep learning and transfer learning techniques. A pre-trained ResNet34 model is fine-tuned using PyTorch to classify images into cancerous and non-cancerous categories.

🔧 Technologies Used

Python

PyTorch

Torchvision

NumPy, Pandas

Matplotlib, Seaborn

Google Colab

📂 Dataset

Histopathology image dataset (PCAM)

Images are resized and normalized

Data augmentation techniques such as random rotation and horizontal flipping are applied to improve generalization

⚙️ Model & Approach

Used ResNet34 (pre-trained on ImageNet) for transfer learning

Frozen initial layers and trained the final fully connected layer

Loss Function: Cross Entropy Loss

Optimizer: Adam

Trained and evaluated the model using train and test datasets

📊 Results

Achieved approximately 60% accuracy during hackathon evaluation

Demonstrates the application of deep learning for medical image classification

📌 Key Learnings

Understanding of CNNs and transfer learning

Practical experience with PyTorch datasets and dataloaders

Handling image data preprocessing and augmentation

Model training, evaluation, and performance analysis

🚀 Future Improvements

Hyperparameter tuning

Training for more epochs

Using advanced architectures

Improving dataset balance and size
