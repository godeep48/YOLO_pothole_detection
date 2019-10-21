# YOLO Pothole detection
This is a deep learning model for detecting the potholes on roads. The model is using YOLO-v2. 

Download the weights from this link : https://drive.google.com/open?id=1VwViHDdc4W8t28rMiuGjxChiAtFxMAjN
and place the weights in the root folder. 

Then
`python predict.py -c config.json -w trained_weights.h5 -i path_to_the_image.jpg

The model has been trained with 150 images having 568 potholes labels. The accuracy of the model will increase by traing the model with larger size dataset. 
