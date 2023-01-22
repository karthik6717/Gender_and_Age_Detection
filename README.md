# Gender_and_Age_Detection

The main aim of the project is to detect the Gender and Age of person by using the pre-trained models of caffe,prototxt, pbtxt and pb. <br>
<b>Flow of  the Algorithm :<b> <br>
First by using OpenCv detecting the face of the person and by using the Cv2.dnn.blobFromImages(#parameters) function process 
the image frame that we taken from the  openCv. OpenCv assumes images are in BGR channel order,
however the mean value assumes we are assumes we are using RGb order. After the preprocessing the image it is converted into 4 dimensional array.
From the 4 dimensional array We have to calculate the confidence_value if the confidence_value is greater than 70 then only show the out put.



