# Rice Leaf Disease Detection

## Introduction
Rice is a crucial staple crop, but its production is threatened by bacterial, fungal, and viral diseases. This project aims to detect rice leaf diseases using deep learning techniques, helping farmers take early action to prevent crop damage. A Convolutional Neural Network (CNN) model is developed to classify rice leaves into three disease categories.

## Dataset Overview
The dataset consists of **120 images** categorized into three disease classes:
- **Leaf Smut** (40 images)
- **Brown Spot** (40 images)
- **Bacterial Leaf Blight** (40 images)

### Data Split
- **Training Set**
- **Validation Set**
- **Test Set**

## Project Workflow
The project follows these steps:
1. **Importing Libraries** – Load necessary Python libraries.
2. **Loading and Preparing Data** – Preprocess images and split them into training, validation, and test sets.
3. **Data Processing** – Apply image augmentation techniques like rotation, flipping, and scaling.
4. **Model Building** – Create a CNN architecture with:
   - **Convolutional Layers** (Feature extraction)
   - **Pooling Layers** (Dimensionality reduction)
   - **Fully Connected Layers** (Classification)
5. **Training and Evaluation** – Train the model and analyze performance metrics.
6. **Testing** – Validate the model on unseen test images.

## Model Performance
- **Training Accuracy**: **84.38%**
- **Validation Accuracy**: **91.67%**
- **Model Loss**: **0.53**

## Results
The model successfully classifies rice leaf diseases with **91.66% accuracy**, making it a reliable solution for automated disease detection in rice crops.

## Future Scope
- Increase dataset size for better generalization.
- Deploy as a real-time detection application (mobile/web-based).
- Implement Transfer Learning for improved accuracy.

## Installation & Usage
### Prerequisites
- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy & Pandas

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/rice-leaf-disease.git
   cd rice-leaf-disease
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```bash
   python train.py
   ```
4. Test the model:
   ```bash
   python test.py --image sample_leaf.jpg
   ```

## License
This project is open-source and available under the [MIT License](LICENSE).
