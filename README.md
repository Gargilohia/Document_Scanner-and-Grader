# Document_Scanning and grading OMR 

1. Simple Document Scanner using OpenCV

The steps involved include:

Converting Image to grayscale, finding edges, using edges to find contours,select contours and apply warp perspective to get top down view .

Libraries basically perform all functions


Reference : https://dontrepeatyourself.org/post/learn-opencv-by-building-a-document-scanner/#select-only-the-edges-of-the-document



2. Grading OMR 

Relevant contours(question bubbles) are grabbed and thresholding is used to determine filled bubbles 
