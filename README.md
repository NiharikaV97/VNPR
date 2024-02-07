# VNPR(Vehicle Number Plate Recognition)
Project Objectives
Developed a program to recognize automatic license plates based on limited dataset.

Localized license plate by applying morphological operations and utilizing contour properties.

Segmented character-like regions of the license plates by applying perspective transforms, performing a connected component analysis, and utilizing contour properties.

Scissored the true characters from previous step by pruning extraneous license plate character candidates, and extracting each character from binary image to create a training set for building classifiers.

Extracted BBPS features from the training set and Built two SVM classifiers for recognizing the letters and numbers of the license plate.
