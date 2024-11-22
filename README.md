1. Apply Mean filtering with mask size 3x3 and 5x5
2. Apply Highpass filtering with mask size 3x3 and 5x5
3. Apply lowpass filtering with mask size 3x3 and 5x5
4. A bilateral filter with mask size 5 × 5 with appropriate values of o and, set 2 d or 2 through experimentation.
5. A Gaussian filter with mask size 5 × 5 appropriate values of σ.
6. A laplacian filter with mask size 5 × 5 appropriate values of σ.
7. A median filter of appropriate window size. Verify your implementation with OpenCV filtering functions.
** Once the filtering is done, observe the changes in the histogram of the images and write your observations. Compare the point down below.
Original image with the Filtered image
Original histogram with the Filtered image histogram
