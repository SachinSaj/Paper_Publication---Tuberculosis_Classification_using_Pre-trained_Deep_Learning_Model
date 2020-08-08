# Paper Publication: Tuberculosis Classification using Pre-trained Deep Learning Models

### Abstract

Deep learning models achieved state-of-the-art performance in many fields including biomedical due to the ability of Convolutional Network (CNN) models and knowledge of transfer learning approaches. The CNN models gave scope for tuberculosis classification by enabling transfer learning approaches. In this paper, we analyzed the effect of
transfer learning techniques on pre-trained deep learning models, which have less feature maps when compared to existing models for classification of Chest X-Ray images of potential Tuberculosis patients. The layer by layer performance was observed and the effect of transfer learning was analyzed in terms of different tuning modes: a) Shallow Tuning, b) Fine Tuning, and c) Deep Tuning, where deep tuning showed the best performance in terms of sensitivity, specificity, ROC-AUC and accuracy.

### Code

- The task is to classify, whether the given chest X-Ray has tuberculosis or not.

- The dataset, which has been used for our task is Montogomery County X-Ray dataset. Preprocessing steps like data-augmentation and histogram equalizations is done to improve their performances.

- The pre-trained models used were MobileNetV2 and DenseNet121 (** In this notebook, only mobilenetV2 is shown). The reason for choosing this models were because of their light weight architecture as a result computation time were be reduced

- Three modes of tuning were used: a) Shallow Tuning, b) Deep Tuning, c) Fine tuning. Shallow tuning means, only the last layer is kept trainable. In fine tuning, layer by layer is made trainable and kept rest of the layers frozen. In deep tuning, it is nothing but complete retraining of the model with this dataset (high time consuming).

- In conclusion, the order of their performance: Deep Tuning > Fine Tuning > Shallow Tuning

### Paper to Cite

- This paper is presented in this conference on Feb 2020 " The International Conference on Automation, Signal Processing, Instrumentation and Control (i'CASIC 2020) ". 
- Publisher - Springer (Germany Based)
- This paper is yet to be published online. 

#### If any ideas from this project is been used, kindly let me know and do cite our paper.

#### Paper is not uploaded, as it is not published online yet.
