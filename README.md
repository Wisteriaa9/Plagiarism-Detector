# Plagiarism-Detector
The outcome of using this plagiarism detector is that we can compare two text
documents as well as two image files. A similarity score is provided by this
plagiarism detector, and it shows what percentage of the text is similar to that
found in the other source and it also obtains whether the images are replicate of
each other or not. This plagiarism detector prints the plagiarized lines or text
between two files and in images, it highlights the area as rectangle which is
similar in both the images

## Features

#### Text Comparison:
Utilizes cosine similarity to assess the plagiarism percentage between two text files.
Identifies common lines between the texts.
#### Image Comparison:
Uses Mean Squared Error (MSE) to evaluate the similarity between two images.
Highlights common areas in the images.

## Usage

### Text Comparison
1. Set the value val to 1 to perform text comparison.
2. Place the text files you want to compare in the /content directory with the names text1.txt and text2.txt.
3. Run the script.
~~~bash
python plagiarism_detection.py
~~~
4. The script will output the percentage of plagiarism between text1.txt and text2.txt, as well as identify similar lines between the two files. 

### Image Comparison
1. Set the value val to 2 to perform image comparison.
2. Place the images you want to compare in the /content directory with the names river1.jpg and river2.jpg.
3. Run the script.
~~~bash
python plagiarism_detection.py
~~~
4. The script will display the original images along with the common area highlighted, and it will determine whether the images are plagiarized based on Mean Squared Error (MSE) threshold.

## Dependencies and Modules used 

1. cv2: OpenCV (Open Source Computer Vision) is a popular open-source computer vision library that provides a set of tools and functions for image and  video processing, as well as machine learning algorithms for object detection, recognition, and tracking.
2. math: It includes functions for performing basic arithmetic operations, advanced mathematical operations, and trigonometric functions.
3. Google Colab: Used for displaying images in Colab environment.
4. from google.colab.patches import cv2_imshow: This function takes an image as input and displays it using the cv2_imshow() function from the google.colab.patches module. You can use this function to display images in your Google Colab notebooks.

## Screenshots 

### Input
![image](https://github.com/Wisteriaa9/Plagiarism-Detector/assets/100563080/7eeeb108-5d01-432c-9f5a-0442e31f1036)

### Text Plagiarism
![image](https://github.com/Wisteriaa9/Plagiarism-Detector/assets/100563080/baada8d1-72b5-45de-bcb6-eab76e0edf83)

### Image Plagiarism
![image](https://github.com/Wisteriaa9/Plagiarism-Detector/assets/100563080/aa761d33-5f94-4365-8181-6891c27e6898)

![image](https://github.com/Wisteriaa9/Plagiarism-Detector/assets/100563080/77388922-7748-4dab-93ad-d864fbbb96de)
