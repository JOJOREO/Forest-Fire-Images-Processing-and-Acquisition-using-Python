# Forest-Fire-Images-Processing-and-Acquisition-using-Python


INTRODUCTION:
There is a huge risk of fires destroying the natural forests all over the world and to protect these forests , prevent fires from damaging the trees and wildlife there must be a software in cameras monitoring the forests in which this software can automatically detect the presence of fire in the pictures taken for the forest .
The problem is that the software cannot differ between the normal trees, objects in the picture and the fire. To solve this problem, we can use several image features , image enhancement techniques to differentiate between them.







Features used in problem solving:

Mean: A quick, simple, and uncomplicated method for reducing the intensity variance between neighbouring pixels in images is mean filtering. It is often used to reduce image noise.

Entropy: Discrete entropy, which is used in image processing, is a measurement of the number of bits needed to encode visual data. The image will be more detailed the higher the entropy value. The distinction between an image's light and dark parts is known as contrast.

Sobel: The Prewitt operator and the Sobel operator are extremely similar. It serves as an edge detector and is a derivative mask. Like the Prewitt operator, the Sobel operator is used to find both horizontal and vertical edges in an image.

Green colour& Red colour intensity : used to differentiate between red colour of fire and green colour of forest

Image Contour: Image contouring is process of identifying structural outlines of objects in an image which in turn can help us identify shape of the object. Consider an example below. On the left we have a hollow rectangle and solid circle. When we apply contouring with red colour, what we get is image on the right.

Harris Corner: Harris Corner Detector is a corner detection operator that is commonly used in computer vision algorithms to extract corners and infer features of an image. It was first introduced by Chris Harris and Mike Stephens in 1988 upon the improvement of Moravec’s corner detector. Compared to the previous one, Harris’ corner detector takes the differential of the corner score into account with reference to direction directly, instead of using shifting patches for every 45-degree angle and has been proved to be more accurate in distinguishing between edges and corners.

Canny Image: The Canny filter is a multi-stage edge detector. It uses a filter based on the derivative of a Gaussian to compute the intensity of the gradients. The Gaussian reduces the effect of noise present in the image.



 

 

 

 

 
Classifiers (4):
1.	Random Forest Classifier
2.	GaussianNB
3.	GradientBoostingClassifier
4.	tree

Project Result:
As the number of features increase the accuracy of the classifier increase
With 8 feature extractions the model had an 82.31% accuracy
with 4 feature extractions the model had a 78.10% accuracy
with 2 feature extractions the model had a 74.81% accuracy

