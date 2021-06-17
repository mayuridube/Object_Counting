# Watershed Algorithm For Object Counting

The watershed algorithm is a classic algorithm used for segmentation and is especially useful when extracting 
touching or overlapping objects in images, such as the coins or medicines in the figure below.

Using traditional image processing methods such as thresholding and contour detection(i.e contour_only.py), 
we would be unable to extract each individual coin from the image.but by leveraging the watershed algorithm, 
we are able to detect and extract each coin  without a problem.

<h3>Usage:</h3>
$ python3 watershed.py --image ./test_images/coins.png

e.g: output of watershed algorithm:<br>

<p align="center">
 <img src="https://github.com/mayuridube/watershed_algorithm/blob/master/test_images/coins.png"></img><br>
 Fig:1 Sample image:<br>
</p>


<p align="center">
 <img src="https://github.com/mayuridube/watershed_algorithm/blob/master/watershed_op/coins_op.jpg"></img><br>
 Fig:2 output image:<br>
</p>



