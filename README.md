# Apple-identification-and-classification-
Image detection and classification project. The YOLOv5s model is trained on custom data to identify apples and mangoes. Apples identified by a Convolutional Neural Network model. There are 13 classes of apples. The image data was retrieved from Kaggle.com .
The Roboflow train YOLO V5 notebook was used to train the yolo model on custom dataset (image annotation was done with roboflow)
The CV_la_Pomme notebook was used to develop the CNN model.
The prediction model is where the object identification and classification is carried out. YOLO is invoked to make a prediction, then CNN carries out the classification. The class is then inscribed on the photo and the saved & displayed.
