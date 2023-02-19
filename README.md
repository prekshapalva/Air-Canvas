## "Air canvas" - A computer vision project implemented using OpenCV

Wouldn't it be great if you could just waffle your finger in the air and draw whatever you wanted? If so, you are in the right place! In this project, I have built an air canvas in just 5 simple steps. This air canvas is built using OpenCV and Python, and can be used to draw anything by simply capturing the movement of a coloured marker held in front of a camera. 


### :one: Introduction
This project is built using the computer vision techniques of OpenCV. OpenCV is an open-source computer vision library that performs various advanced image processing tasks. Although Python is the preferred language due to its extensive libraries and easy-to-use syntax, any OpenCV-compatible language can be used, provided you understand the basics. To achieve the objective, Color Detection and Tracking techniques are also used. The colour marker is detected and a mask is created. As part of the process, further morphological operations are performed on the mask-- where the mask that has been eroded reduces the impurities present, and a mask that has been dilated further restores the mask that has been eroded.

### :two: Prerequisites
Python, OpenCV and Numpy

### :three: Steps to be followed
1. First, read the frames and convert them to HSV color space (easy to detect colors). 
2. Prepare the canvas frame, attach the ink buttons and use the track bar values to determine the mask of the marker. 
3. The mask should be preprocessed with morphological operations (eroding and dilation). 
4. The contours and the center coordinates of the largest contour are found and stored in the array (drawing points on canvas). 
5. Lastly, draw the array of points on the canvas and frames.

### :four: Output

### :five: Conclusion

