# Object size measurement using Auroc Marker

### What is Auroc Marker?

![markers](https://user-images.githubusercontent.com/95399504/146164376-eb6d8854-5605-49a7-979d-c13f32af8a43.jpg)


ArUco stands for Augmented Reality University of Cordoba. That is where it was developed in Spain.

An aruco marker is a fiducial marker that is placed on the object or scene being imaged. It is a binary square with black background and boundaries and a white generated pattern within it that uniquely identifies it.


The black boundary helps making their detection easier. They can be generated in a variety of sizes. The size is chosen based on the object size and the scene, for a successful detection.

Detailed articel : https://www.pyimagesearch.com/2020/12/28/determining-aruco-marker-type-with-opencv-and-python/

**We are using Aurco marker as our reference object**

#### Stage 1 : Measuring the distance of the object with the help of Auroc Marker

#### Stage 2 : Create point matrix get coordinates of mouse click on image

#### Stage 3 : Trying to hide the aurco marker using some sticker


**For object detection we have used a object_detector.py file which is uploaded**

### Libraries :

cv2

numpy

cv2.aruco

### Sample Output image :
![image](https://user-images.githubusercontent.com/95399504/146165759-63fce122-9717-4546-bd7d-ed49195db529.png)


### References : 
https://pysource.com/2021/05/28/measure-size-of-an-object-with-opencv-aruco-marker-and-python/

