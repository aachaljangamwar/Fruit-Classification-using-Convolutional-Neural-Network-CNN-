# Fruit-Classification-using-Convolutional-Neural-Network-CNN-
1. Data Collection and Preprocessing
Dataset: The project begins by gathering a dataset of fruit images. Each image corresponds to a specific type of fruit.
Preprocessing: The images are resized, normalized, and labeled to prepare them for model training. This ensures uniformity and improves the model's ability to learn.

3. Building the CNN Model
Architecture: A Convolutional Neural Network (CNN) is designed with multiple layers, including convolutional layers for feature extraction, pooling layers to reduce dimensionality, and dense layers for final classification.
Compilation: The model is compiled with an appropriate optimizer (e.g., Adam), loss function (e.g., categorical crossentropy), and evaluation metric (e.g., accuracy).

5. Training the Model
Training Process: The model is trained on the preprocessed dataset. During training, the CNN learns to identify key features of each fruit type by adjusting its weights through backpropagation.
Output Metrics: The training process yields an accuracy of 0.8569 and a loss of 1.0081, indicating how well the model is performing on the training data.

7. Evaluating the Model
Testing: The trained model is then evaluated on a separate test set to gauge its generalization ability. The test score (loss) is 1.1944, and the test accuracy is 0.8167. These metrics reflect how accurately the model can classify unseen fruit images.
Interpretation: The model's accuracy and loss values suggest that it performs reasonably well but could benefit from further tuning or additional data.

9. Conclusion and Future Work
Outcome: The CNN model successfully classifies fruit images with decent accuracy. The project demonstrates the practical application of deep learning in image recognition tasks.
