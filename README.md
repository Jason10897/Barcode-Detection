# Barcode-Detection
This repository contains codes to detect and decode barcodes in images and videos using the pyzbar library in Python. The code draws a bounding box aroung the detected barcodes and annotates its type and decoded value.
<br>The code for videos also has a line commented to save a video to a set of frames. Uncomment that line to do the same. I have also added a code that assembles these frames with bounding boxes and annotations into a video, for those looking to save the results to a video.

1. Barcode Scanner.ipynb
<br>Code for detecting and decoding barcodes in images.

2. Barcode Scanner for Videos.ipynb
<br>Code for detecting and decoding barcodes in videos. Also has a commented line of code to save a video as a set of frames. There are two methods for processing a video. My code uses FileVideoStream. The other one is VideoStream. FileVideoStream processes the video slower, but generally has a better performance than VideoStream, which processes the video faster with a slightly lower performance. It is advised to use FileVideoStream for videos having a shorter duration or in cases where accuracy is very important. For longer videos or experimentation, use VideoStream instead. 

3. Frames to Video.ipynb
<br>Code for assembling a set of frames into a video.

Note: GitHub may not be able to render a Jupyter Notebook in one go, so kindly reload it a few times to view the Notebook, if it does not load the first time around.
