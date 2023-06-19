# face_feature_detection
A program with uses computer vision(opencv) to find the coordinates of eyes and mouth in a persons image. The dataset used is FFHQ.

Run the ipynb file to generate the output images as well as the csv file containing the coordinates of left eye, right eye and mouth of the person.
To process more image data than 100 change the line number 3 of cell one from

list=list[0:100]

to 

list=list[0:required_no_of_images]

Pre requisites : os library, openvision-python library

