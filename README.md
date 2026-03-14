\# Food vs Non-Food Image Classification



Deep learning project for \*\*binary image classification\*\* using \*\*CNN, ResNet-style networks, and transfer learning with EfficientNetB0\*\*.



The models are trained on the \*\*Food-5K dataset\*\* using \*\*TensorFlow / Keras\*\*.



\---



\## Author



\*\*Md Imtiaz Kamru\*\*  

PhD Student — Electrical \& Computer Engineering  

The University of Alabama  



\---



\## Project Overview



This project explores multiple deep learning architectures for distinguishing between \*\*food\*\* and \*\*non-food images\*\*.



Three different model types are implemented and compared:



1\. \*\*Custom CNN Model\*\*

2\. \*\*Residual CNN (ResNet-style architecture)\*\*

3\. \*\*Transfer Learning using EfficientNetB0\*\*



The goal is to analyze how \*\*architecture complexity\*\* and \*\*pretrained feature extraction\*\* influence classification performance.



\---



\## Dataset



The project uses the \*\*Food-5K dataset\*\*, which contains approximately \*\*5000 images\*\* divided into two classes:



\- Food  

\- Non-Food  



\### Dataset Structure



Food-5K/

├── training/

├── validation/

└── evaluation/





Images are resized to \*\*256 × 256 resolution\*\* during preprocessing.



\### Dataset Source



https://www.kaggle.com/trolukovich/food5k-image-dataset



\---



\## Implemented Models



\### 1. Custom CNN



A baseline convolutional neural network using stacked convolution blocks, pooling layers, and dropout regularization.



\### 2. Residual CNN



A deeper architecture using \*\*custom residual blocks inspired by ResNet\*\*.  

Residual connections help stabilize training and allow deeper feature extraction.



\### 3. EfficientNetB0 Transfer Learning



A pretrained \*\*EfficientNetB0\*\* model is used as a feature extractor.  

The pretrained backbone is frozen while a classification head is trained on the dataset.



\---



\## Training Techniques



The following techniques were used to improve model performance:



\- Data augmentation

\- Dropout regularization

\- Batch normalization

\- Transfer learning

\- Validation-based model selection



\---



\## Results



Training and validation curves were analyzed to evaluate \*\*model convergence and generalization\*\*.



\### Key Observations



\- Data augmentation improved model robustness

\- Dropout reduced overfitting

\- Residual connections improved training stability

\- Transfer learning provided strong feature extraction and faster convergence



\---







