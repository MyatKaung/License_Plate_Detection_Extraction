# Number_Plate_Detection
 
It is important to have an automated system that can detect and extract license plate numbers. With the help of deep learning, data scientists can now use deep learning to make real time number plate recognition with YOLO( you only look once) algorithm, which is a state of the art object detection algorithm. Although the YOLO algorithm is much better than deep Convolutional Neural Network(CNN) architectures such as InceptionV3, MobileNet, ResNet etc, I have used the InceptionResNet V2 model in this project to make predictions on detecting license plates. In addition, I will use Pytesseract to extract the number plate from the image cropped. Furthermore, I have developed the License Plate Web Application with Flask and integrated my model. Here is my workflow. I have installed the required libraries such as OpenCV, Tensorflow 2.0. So as I am using M1 Mac, I have installed Tensorflow 2.0 in M1 mac version. You can check how to install it here. (https://github.com/mrdbourke/m1-machine-learning-test)

First, we will get the dataset and will crop the license plate from image using LabellImg.We will use PascalAfter that, we will change from XML to CSV file. After that, there is a step called data processing. In this step, we will read the data, verify the data,data preprocessing and split the data into train and test set.

Then, we will use InceptionResNet V2 model for training and will save the model. Futhermore, we will make predictions and create pipeline model. In addition, Pytesseract will be used to extract number plate text from image.

Finally, Number Plate Web App will be made using HTML, Boostrap and Flask.

In additon, Real Time Number Plate recognition can be developed using YOLO algorithm. I will update it once I have finished the YOLO Model.
