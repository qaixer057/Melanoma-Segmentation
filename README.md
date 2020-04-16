# Melanoma-Segmentation
All the code and python notebook which contains my project named "Melanoma Segmentation using Mask R-CNN and Transfer Learning".
This project was done as a term project for my Master's Algorithms Class.
A custom Mask R-CNN was trained on ISIC 2019 Dataset to detect and segment the melanoma in skin dermoscopic images.
I used ResNet 101 for transfer learning and http://www.robots.ox.ac.uk/~vgg/software/via/ was used as annotation tool.
ISIC 2019 also provides segmentations but as it was just a prototype so I just manually annotated images.
Code was used by @waleedabdullah. Which I modified as per my requirements.

P.S: There is a little bit probelm in the infrence code. While annotating my images I unconciously named my lesions "gun" instead of "melanoma" and "non-melanoma" which are two of my classes in this project. (Actually I was working with my guns classifier so I used much of the code from that file. ;)
