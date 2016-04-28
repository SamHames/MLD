# OpenCV3 and Python3
===================

When Jack suggested a machine learning lesson with OpenCV, I had to work out how to get it installed.

By far the easiest way was to install the Anaconda distribution, create a virtual environment especially for OpenCV


 
	condo create -n opencv3 anaconda

then activate that virtual environment


	source activate opencv3

and install opencv3 from a recipe


	conda install --channel https://conda.anaconda.org/menpo opencv3
	
	
check it has worked by opening a python prompt and importing the library

	import cv2
	
if it imports with no errors you have succeeded!

