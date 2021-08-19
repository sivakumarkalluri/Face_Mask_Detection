<h1 text-align="center"><div style="float: left;"><img src="https://img-premium.flaticon.com/png/128/2059/premium/2059372.png?token=exp=1629358287~hmac=6018712a14c7c8a611ab3472ba1d3755" width="35" height="35">     FACE MASK DETECTION</div></h1><hr>

<p align="justify">COVID-19 pandemic has rapidly affected our day-to-day life disrupting the world trade and movements. Wearing a protective face mask has become a new normal. In the near future, many public service providers will ask the customers to wear masks correctly to avail of their services. Therefore, face mask detection has become a crucial task to help global society. This paper presents a simplified approach to achieve this purpose using some basic Machine Learning packages like TensorFlow, Keras, OpenCV and MobileNet. The proposed method detects the face from the image correctly and then identifies if it has a mask on it or not. As a surveillance task performer, it can also detect a face along with a mask in motion. The method attains accuracy up to 98% on a dataset. We explore optimized values of parameters using the Sequential Convolutional Neural Network model to detect the presence of masks correctly without causing over-fitting.</p><br>
 
<h2 text-align="center"><div style="float: left;"><img src="https://img-premium.flaticon.com/png/128/4319/premium/4319207.png?token=exp=1629357704~hmac=b029136115e3137212d8a6f6980942cb" width="45" height="45"> TechStack/framework used</div></h2><hr>

- Python
- OpenCV
- TensorFlow
- MobileNet
- Keras
- Kaggle Dataset
<br>
<h2 text-align="center"><div style="float: left;" text-align="center"><img src="https://img-premium.flaticon.com/png/128/2986/premium/2986258.png?token=exp=1629357509~hmac=efafb9eadbccdbb0b3e45ec24f480813" width="40" height="40">      Introduction</div></h2><hr>

<p >Face mask detection is an AI based technology that analyzes a video stream to detect and recognize a face mask worn by an individual person or a crowd of people. Our DeepSight software outputs a confidence value for each detection. Every individual is classified either as ‘wearing a mask’ or flagged as ‘not wearing a mask’.</p><br>
<div style="float: left;" text-align="center"><h2 align="justify"><img src="https://image.flaticon.com/icons/png/128/2245/2245313.png" width="40" height="40">  DataSet</h2></div><hr>
<p align="justify">The dataset used in this project is downloaded from <b>Kaggle</b>. You can download the images dataset by clicking on this download icon  <a href="https://www.kaggle.com/omkargurav/face-mask-dataset/download">
<img src="https://img-premium.flaticon.com/png/512/3121/premium/3121602.png?token=exp=1629359723~hmac=e4b12674ef3303795d21b7a37ff8095e" alt="HTML tutorial" width="25" height="25">
</a> 
 
 This dataset consists of 3,584 images belonging to two classes:
 <b>
- with_mask: 1,792 images
- without_mask: 1,792 images</b>
 
 <h2 text-align="center"><div style="float: left;"><img src="https://img-premium.flaticon.com/png/128/1022/premium/1022216.png?token=exp=1629364585~hmac=8e3cf8a50e54609bf02ca6ef19438db8" width="45" height="45"> Prerequisites</div></h2><hr>
 
 
 - Python interpreter should be installed in your PC/Laptop.
 - After Python is installed download the following required modules
    - <b>Tensorflow
    - Keras
    - MobileNet
    - Numpy
    - Imutils
    - Opencv-python
    - Matplotlib
    - Scipy</b>


<h2 text-align="center"><div style="float: left;"><img src="https://img-premium.flaticon.com/png/128/2482/premium/2482499.png?token=exp=1629366162~hmac=33f74fbfb7f3d2766a00ee8450f38b55" width="45" height="45"> Downloading the Project</div></h2><hr>

#### Step 1: Cloning the repository
<code> git clone </code>



