# Object-detection-
Use below directory structure, and generate text file containing (KITTI format ) annotation for each image.  . ├── images │   ├── 000000.jpg │   . │   . │   └── XXXXXX.jpg └── annotations     ├── 000000.txt     .     .     └── XXXXXX.txt The text file should contain one annotation per line, with values separated by space. className 0.00 0 0.00 x1 y1 x2 y2 0.00 0.00 0.00 0.00 0.00 0.00 0.00 className 0.00 0 0.00 x1 y1 x2 y2 0.00 0.00 0.00 0.00 0.00 0.00 0.00 Eg., person 0.00 0 0.00 20 50 196 600 0.00 0.00 0.00 0.00 0.00 0.00 0.00 face 0.00 0 0.00 100 120 150 180 0.00 0.00 0.00 0.00 0.00 0.00 0.00 Note:- The dataset is available to download through Google drive &amp; Kaggle , here's what can be done.  Download it manually and upload to colab (https://www.kaggle.com/imneonizer/wider-person/download). 
