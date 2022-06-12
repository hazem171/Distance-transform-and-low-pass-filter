# Distance-transform-and-low-pass-filter

Implementing the distance trasnform algorithm to find: 
1- The distance between the two ships in the image “Suez Canal.png” 
2- The distance from each ship to both banks of the canal 
The function takes the image as an input and the distance measure to be used (Euclidean Distance, City-block Distance or Chessboard Distance). The function outputs the distance transform matrix after the first pass of the algorithm, the final distance transform matrix and the distances indicated above measured relative to the representative point of each ship.

Attached files:  
• A description of the pre-processing steps you did and the reaons for doing each of them named “Description.txt” 
• A .bmp file for the distance transform matrix obtained after the first pass using each of the distance measures mentioned above named “Suez_1_Euclidean.bmp”, “Suez_1_City.bmp”, “Suez_1_Chess.bmp”. 
• A .bmp file for the final distance transform matrix using each of the distance measures mentioned above named “Suez_final_Euclidean.bmp”, “Suez_final_City.bmp”, “Suez_final_Chess.bmp”. 
• A text file that shows the distances required above named “Dist.txt”. 
 
 

 
 
Implementing a function that applies a low-pass filter to an input gray-scale image. The function takes as inputs the input image, the type of the filter (ideal, Butterworth or Gaussian), the order of the filter if it’s Butterworth and the cutoff distance of the low-pass filter D0. It outputs the filtered image by applying the filter to the noisy image “GUC.jpg”. 

Attached files:  
 • The output images obtained using Ideal Low-pass Filter with D0 = 5, D0 = 30 and D0 = 50 named “GUC_ILPF_5.jpg”, “GUC_ILPF_30.jpg” and “GUC_ILPF_50.jpg”, respectively.
 • The output images obtained using 1st order Butterworth Low-pass Filter with D0 = 5, D0 = 30 and D0 = 50 named “GUC_BLPF_5.jpg”, “GUC_BLPF_30.jpg” and “GUC_BLPF_50.jpg”, respectively.
 • The output images obtained using Gaussian Low-pass Filter with D0 = 5, D0 = 30 and D0 = 50 named “GUC_GLPF_5.jpg”, “GUC_GLPF_30.jpg” and “GUC_GLPF_50.jpg”, respectively. 
