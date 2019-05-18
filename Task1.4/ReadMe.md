## Edge Detection

In this, Canny Edge Detection function has been used to detect edges. This has been picked due to the ability to optimize the noise as it uses a gaussian filter of kernel size, 5. After filtering, it smoothens the image with Sobel kernel in both directions (vertical and horizontal). This algorithm also removes unwanted pixels. After than it is thresholded on following set of rules : 


   (a) If value > maxVal  ->  Considered as an edge
        
        
   (b) If value < minVal  ->  Discarded
        
        
   (c) If minVal <= value <= maxVal  ->  If this pixel is directly connected to already considered edge, then it is considered as an                                                edge, otherwise discarded.
        
## Note
In this, two trackbars have been implemented in order to adjust minVal and maxVal which are minimum and maximum value of thresholding. To see implementation, you can refer to GIF.
