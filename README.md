This project focuses on using Machine Learning to detect skin cancer by classifying dermal carcinogenic lesions into seven categories using the HAM10000 dataset.
The dataset, initially imbalanced, was preprocessed to ensure a more linear distribution by resampling and handling missing values. 
Images were resized, normalized, and label-encoded for model training. A Convolutional Neural Network (CNN) was employed, featuring convolutional, dropout, and dense layers to extract and classify features. 
The model underwent rigorous training over 50 epochs, achieving a classification accuracy of 69%.
The evaluation highlighted the impact of class imbalance and the need for a diverse dataset. 
Future improvements could include advanced architectures and hyperparameter tuning to enhance model accuracy and robustness. 
