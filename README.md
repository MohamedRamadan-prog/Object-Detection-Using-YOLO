# Generic YOLO Model



![image](https://user-images.githubusercontent.com/53750465/62553532-cd7e5500-b86f-11e9-9aea-a9458b62e001.png)


- YOLO is an object detection pipeline based on Neural Network. Contrast to prior work on object detection with classifiers to perform detection, YOLO frame object detection as a regression problem to spatially separated bounding boxes and associated class probabilities. A single neural network predicts bounding boxes and class probabilities directly from full images in one evaluation. Since the whole detection pipeline is a single network, it can be optimized end-to-end directly on detection performance



![image](https://user-images.githubusercontent.com/53750465/62553615-f0106e00-b86f-11e9-99a6-6e488eaf5f75.png)


# steps to use the YOLO for detection:
I) Resizing the input image to 448x448
II) Running a single convolutional network on the image
III) Thresholding the resulting detections by the model’s confidence

 
![image](https://user-images.githubusercontent.com/53750465/62553670-0dddd300-b870-11e9-95bb-7d880535884b.png)


![image](https://user-images.githubusercontent.com/53750465/62553699-1cc48580-b870-11e9-99ac-c6a1cd9c372f.png)

