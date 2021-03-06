# Machine-Learning
## Project Description
Application of machine learning in car number identification.

## Environment Requirement
Programming language: Python 3.x<br> 
Third-party library: OpenCV 3<br> 
Processor: Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz 2.71GHz 


## 	Execution
1. cd src
2. Test a real-world scenario: python main.py "../testing_full_system/testing_full_system"
3. Train a new neural network (new or existing): python neural.py "../training_ocr/training_ocr/" "../training_ocr/testing_ocr/"

## Project Requirement
1.	The image text recognition application recognizes text from a given picture. This is much more complicated than recognizing text from a scanned document.
2.	Vehicle is indispensable in social life.
a.	License plate recognition is a very successful application of machine learning in practical engineering.
3.	The license plate recognition system is an important issue for the intelligent traffic system.
4.	The license plate recognition is mainly composed of three steps:
a.	license plate positioning
b.	character segmentation 
c.	character recognition
5.	license plate positioning
a.	The size, angle, color, and clarity of the license plates are different.
b.	The adaptation algorithm in one scenario is not applicable to other scenarios.
c.	Extract the edge information of the image, select the rectangular area in the image after the close operation, and then verify whether it is a license plate.
6.	character segmentation
a.	In general, after binarization, tilt correction, connected component extraction can be done.
7.	character recognition
a.	Large number of pictures are used to train the Neural Network.
b.	And we can get a better model if the number of pictures is big enough.
c.	We also can use Deep Learning to train the data.

## Task Allocation

|Name|Task|
|--|:--:|
|ML|main modul<br> English project document(English Version)|
|WZ|neural modul<br> English project document(English Version)|
|ML|car modul<br> English project document(English Version)|
|ML|utils modul<br> English project document(English Version)|
|ML|English final project document(English Version)<br> In-class final project presentation|
