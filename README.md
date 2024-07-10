# Shape-Segmentation
Shape Segmentation with OpenCV: Detects and highlights squares in an image using OpenCV and matplotlib, demonstrating basic image processing techniques.

This project demonstrates basic image processing tasks using OpenCV and matplotlib. The code performs the following operations on an input image (`main.png`):

1. **Loading and Displaying the Image:**
   - The image is loaded using OpenCV and converted to RGB format for compatibility with matplotlib.

2. **Converting to Grayscale:**
   - The RGB image is converted to grayscale using OpenCV.

3. **Applying Binary Thresholding:**
   - A binary threshold is applied to the grayscale image to create a binary image.

4. **Detecting Contours:**
   - Contours are detected in the binary image using OpenCV's contour detection functions.

5. **Identifying Squares:**
   - Among the detected contours, squares are identified based on their geometry (four corners).

6. **Highlighting the Largest Square:**
   - The largest square found among the identified squares is highlighted on the original image.

7. **Creating a Mask and Applying to the Image:**
   - A mask is created based on the largest square contour and applied to the original RGB image to isolate the square region.


