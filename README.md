# Image_Stitching
The goal of this project is to automatically create a panoramic image using two images without using computer vision libs.
### In a nutshell
Image stitching is the process of combining multiple photographic images with overlapping fields of view to produce a segmented panorama or high-resolution image. 
In this project, first I detect the keypoints and descriptors of given images. Then I calculated homography matrix by using RANSAC algortihm. Also I’ve made transformation on image.
