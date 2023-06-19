# face_feature_detection
A program with uses computer vision(opencv) to find the coordinates of eyes and mouth in a persons image. The dataset used is FFHQ.

Run the ipynb file to generate the output images as well as the csv file containing the coordinates of left eye, right eye and mouth of the person.
To process more image data than 100 change the line number 3 of cell one from

list=list[0:100]

to 

list=list[0:required_no_of_images]

Pre requisites : os library, openvision-python library

Some good examples :

![00098](https://github.com/Saksham3112/face_feature_detection/assets/80478503/85f06c29-9c5b-4047-a983-b7414b1f9061)
![00098](https://github.com/Saksham3112/face_feature_detection/assets/80478503/b40792b0-4f04-4084-8288-b4629e018e06)

![00043](https://github.com/Saksham3112/face_feature_detection/assets/80478503/c1e2f248-2c5f-4788-903c-289d6d693e8a)
![00043](https://github.com/Saksham3112/face_feature_detection/assets/80478503/701b7b4c-494b-4df4-9b20-ea74412ecbae)

Some failed outputs :

![00041](https://github.com/Saksham3112/face_feature_detection/assets/80478503/d04fa8ba-7478-4b48-a14f-d50521a8ed7b)
![00041](https://github.com/Saksham3112/face_feature_detection/assets/80478503/4a97b9a2-182e-41fd-85e7-a0b10d9e0dc4)

![00036](https://github.com/Saksham3112/face_feature_detection/assets/80478503/d019af86-f6f8-4b09-99a9-0d0bd1f1c6fe)
![00036](https://github.com/Saksham3112/face_feature_detection/assets/80478503/145a7c06-8ad3-415d-a627-c2d097edd559)




