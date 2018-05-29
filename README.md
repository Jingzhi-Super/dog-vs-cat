# dog-vs-cat
Kaggle competition, https://www.kaggle.com/c/iminit-2017
Image classification using keras

Two parts:
1. image: image preprocessing. Divide training set into 4 parts due to computation limits.
2. main_CNN: convolutional neural network.
3. transfer: transfer learning with VGG16 network.
4. prelu_model_1.h5: CNN model file.
5. transfer_1.h5: transfer learning model file.
6. DvCsubmission.csv: submission file.

Result:
0.94343 accuracy on Kaggle test set with transfer learning.

