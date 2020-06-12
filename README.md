# watershed_algorithm

The watershed algorithm is a classic algorithm used for segmentation and is especially useful when extracting 
touching or overlapping objects in images, such as the coins or medicines in the figure above.

Using traditional image processing methods such as thresholding and contour detection(i.e contour_only.py), 
we would be unable to extract each individual coin from the image.but by leveraging the watershed algorithm, 
we are able to detect and extract each coin  without a problem.

e.g: output of watershed algorithm:<br>

Sample image:<br>
![Test Image 3] ./watershed_algorithm/test_images/coins.png 
