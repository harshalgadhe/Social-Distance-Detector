# Social-Distance-Detector

Covid Spreads in a region due to various reasons and one of them is due to violation of Social Distancing. This code can be used to detect if there are any social distance violations in real time by using this real time detector code in CCTV.<br>
Using it we can track the number of violatations in the image and thus can predict the location which can become hotspot for covid spreading.
<br><br>
The below video shows how the program implements in real time. For the detection I have used video from You Tube.<br>
![](https://github.com/harshalgadhe/Social-Distance-Detector/blob/main/social%20distancing.gif)

To use the detector from your camera just replace cv.VideoCapture('street.mp4') with cv.VideoCapture(0,cv.CAP_DSHOW) in 3rd cell of the notebook.
<br>
You can download the resources needed to implement the code from the resources folder also to download yolo weights use this <a href='https://pjreddie.com/media/files/yolov3.weights'>Link</a>.
