# ultrasound-img-segmentation-classification
Ultrasound image segmentation and classification project

Data: Ultrasound Image

Process:
1. Image Data Preprocessing: Image Filtering
    - Convert RGB to Grayscale
    - Speckle Reduction
    - Contrast Enhancement
    - Binarization
    - Convert Grayscale to RGB
2. Segmentation
    - U-Net architecture
    - Optimizer -> Adam
    - Loss -> BinaryCrossEntropy
    - Metrics -> Accuracy
    - Training for 100 epochs
3. Feature Extraction and Classification
    - DenseNet201
    - Training for 100 epochs
    - Metrics -> Accuracy, Precision, Recall, f1-score, AUC and ROC

