# Sports-Player-Identification
Player Identification in Different Sports 

In this paper, we present a deep learning-based framework
to identify the sports player through jersey number. Our framework has three main parts. Firstly, it
detects players on the court using state of the art object detector YOLO V4. Secondly, each jersey number
per detected player bounding boxes is localized. Then a four-stage scene text recognition is employed for
recognizing detected number regions. A benchmark dataset consists of three subsets is collected. Two subsets
include player images from different fields in basketball sport and the third includes player images from ice
hockey sport. 

Getting started
----------------------
You can run the Number detection and recognition.ipynb on Colab and this file includes the steps to install the required package.
Also you can test your player images by just uploading the player images and change the img_dir to your created folder. 

Citation
--------------
Nady, A. and Hemayed, E. "Player Identification in Different Sports".
In Proceedings of the 16th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications (VISIGRAPP 2021) - Volume 5: VISAPP, pages
653-660
