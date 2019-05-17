## Face Detection using Haar Cascade Algorithm

In this, classifier has been defined with xml file only targeted for front face detection. In detectMultiScale function, image is taken as a matrix of type cv2.cv_8U. Scale factor is taken to be 1.3. It specifies how much image size should be reduced at each image scale. Here, minneighbors is taken as 5 i.e. minimum number of neighbors each rectangle should retain. High value means less detections but higher quality.
In return, it returns Rect(x,y,w,h) i.e. coordinates of the rectangle around a face, if found.
