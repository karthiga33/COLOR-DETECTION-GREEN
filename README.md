Import OpenCV: First, make sure you have OpenCV installed.
 Read the Image: 
 Load the image where you want to perform color detection using the cv2.imread() function.
 Convert Color Space: 
 Depending on the task, you may want to convert the image to a different color space, such as HSV, which is useful for color-based segmentation.
 Define Color Range: 
 Determine the lower and upper bounds of the color you want to detect in the chosen color space. For example, to detect blue, you can set the range
 Create a Mask: 
 Generate a binary mask for the specified color range using the cv2.inRange() function.
 Bitwise AND Operation:
 Use the mask to extract the specific color regions from the original image.
Display the Result: 
Visualize the original image and the color-detected image using cv2.imshow().
