# Butterfly Image Classification with TensorBoard

## Project Overview
This project focuses on training an image classification model to identify different species of butterflies using deep learning. The model leverages **MobileNetV2**, a lightweight convolutional neural network, with **transfer learning** to enhance accuracy and efficiency. TensorBoard was integrated to monitor key training metrics, enabling real-time performance analysis.

## Methodology
1. **Dataset Preparation**
   - Collected and preprocessed butterfly images.
   - Applied data augmentation techniques to improve generalization.

2. **Model Selection & Transfer Learning**
   - Used **MobileNetV2** as the base model, pre-trained on ImageNet.
   - Froze the base layers and fine-tuned the top layers to optimize classification performance.

3. **Training Process**
   - Implemented **TensorBoard** to visualize accuracy, loss, and training performance.
   - Trained the model for **five epochs**, showing steady improvement:
     - Training Accuracy: **77.8% → 93.2%**
     - Validation Accuracy: **89%**
     - Loss consistently decreased, indicating enhanced stability.

## Results & Insights
- The model demonstrated significant improvement over training, proving the effectiveness of **transfer learning**.
- TensorBoard facilitated insightful tracking of key metrics, aiding in better model tuning.
- The fine-tuned MobileNetV2 achieved high classification accuracy with a reduced number of parameters, making it efficient for deployment.

