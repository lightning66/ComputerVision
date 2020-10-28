The notebook loads a pretrained face detection model from Caffe. Then classification on the detected image is done in Keras using pretrained weights to detect 7 emotion categories. Real-time emotion is shown at the top of the bounding box.<br/>
The code is tested on Ubuntu 20.04,but runs on Windows 10 and macOS Catalina 10.15.7.<br/><br/>

<b>Requirements:</b><br/>
-OpenCV 4.4.0 (works fine on 4.2.0)<br/>
-Numpy 1.18.5<br/>
-Keras 2.4.3 (works fine on 2.1.2)
