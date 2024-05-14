# Brain Tumor Classification Using CNN

Brain tumors are abnormal growths of cells in the brain that can be benign (non-cancerous) or malignant (cancerous). 
Early detection and accurate classification of brain tumors are essential for proper treatment planning and improved patient survival rates.
In recent decades, advances in medical imaging techniques, such as Magnetic Resonance Imaging (MRI) and Computed Tomography (CT), have provided rich data for medical analysis.

Data Source : https://www.kaggle.com/datasets/denizkavi1/brain-tumor

## Brain Tumor Classification
Brain tumor classification refers to the process of identifying the type of tumor based on the characteristics detected in medical images. 
This classification is important for diagnosis and determining appropriate treatment strategies. Brain tumors are generally classified into several categories, such as glioma, meningioma, and Pituitary.

### Challenges in Classification
1. Variability in Tumor Appearance: Brain tumors can vary significantly in shape, size, and intensity on medical images.
2. Difficulties in Data Annotation: The process of annotating medical data requires specialized skills and significant time, often resulting in limited data.
3. Noise and Artifacts in Images: Medical images often contain noise and artifacts that can interfere with the classification process.

## Convolutional Neural Network (CNN)
Convolutional Neural Network (CNN) is a type of deep learning architecture specifically designed for image data processing. 
CNNs are capable of automatically extracting features from image data and have shown excellent performance in various pattern recognition and classification tasks.

### Advantages of CNN in Brain Tumor Classification:
Automatic Feature Extraction: CNNs can automatically learn relevant features from medical images without requiring manual intervention.
Strong Generalization Ability: CNNs can generalize from training data to test data, providing high accuracy even on previously unseen data.
Reduction of Overfitting: Techniques such as regularization, dropout, and data augmentation help reduce overfitting, improving the model's ability to handle data variations.

### CNN Architecture
CNN architecture generally consists of several layers, including:
- Convolution Layer: Performs convolution operations to extract features from the input image.
- Pooling Layer: Reduces the dimensionality of the features to reduce the computational burden and handles translation invariance.
- Fully Connected Layer: Connects all neurons from the previous layer to produce the final classification.
- Activation Layer: A non-linear function such as ReLU is used to introduce non-linearity into the model.
