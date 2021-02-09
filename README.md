
## Player Identification in Different Sports 
[Paper](https://drive.google.com/file/d/1NrdE5ox4NRq6dehhpX5jZGXz7_XV7H-a/view?usp=sharing) | [Presentation](https://drive.google.com/file/d/1xrPXhWb_EVHYKEAvV_HmAlAKWykoXdk8/view) | [Video](https://youtu.be/SyoN0b757mg)

In this paper, we present a deep learning-based framework
to identify the sports player through jersey number. Our framework has three main parts. Firstly, it
detects players on the court using state of the art object detector YOLOv4. Secondly, each jersey number
per detected player bounding boxes is localized. Then a four-stage scene text recognition is employed for
recognizing detected number regions. A benchmark dataset consists of three subsets is collected. Two subsets
include player images from different fields in basketball sport and the third includes player images from ice
hockey sport. 

Getting started
----------------------
You can run the Number detection and recognition.ipynb on Colab and this file includes the steps to install the required package.
Also you can test your player images by just uploading the player images and change the img_dir to your created folder. 

Dataset
-------------------
Sports Jersey Number dataset consists of three subsets. Two subsets
include player images from different fields in basketball sport and the third includes player images from ice
hockey sport.

 For the first basketball subset that is used for training, here are the image files and their annotations.
https://drive.google.com/file/d/1aZjbdSHPJdVsQH8Tl7H2M7g4xHVSp5Xx/view?usp=sharing
https://drive.google.com/file/d/1qe_Eihk96r_-I6ZdJbre-dR_JQLpZC0H/view?usp=sharing
The imageName begins either number or None where None represent the player image don't contain a number.

For the second basketball and Ice hockey subset: here are the image files and their annotations (number or None in image file name)
second basketball subset: https://drive.google.com/uc?id=1MXnvzo4a_N0jtzlmNayxdZqAy-InfNUJ
Ice hockey Sport subset : https://drive.google.com/uc?id=15ukczpqJa4j7Gb_GilzBcvhtXyTN8vBS

Citation
--------------
Nady, A. and Hemayed, E. "Player Identification in Different Sports".
In Proceedings of the 16th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications (VISIGRAPP 2021) - Volume 5: VISAPP, pages
653-660
