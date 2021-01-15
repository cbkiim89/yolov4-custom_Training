# Training a custom detector for Object Detection using YOLOv4

![](z.gif)

## **Mask detection using YOLOv4**

The **yolov4** folder contains the 4 custom files needed. (i.e. **yolov4-custom.cfg**, **obj.data**, **obj.names** and **process.py**) except **obj.zip**(labeled images)

I will be sharing my labeled custom mask dataset **obj.zip** file on the following link. You can download it from here.

https://www90.zippyshare.com/v/JpGui9bx/file.html


The **obj.zip** file contains 1370 images along with their YOLO labeled text files. There are around 900-950 images for class **with_mask** and around 400-450 images for class **without_mask**. 

These images are mostly close-up images. If you want to download more long shot images, you can search for datasets online. There are many sites where you can find more datasets. Check out my Medium article for links to these sites. You can add your own images and their YOLO labeled text files to the dataset. Try to find good quality images.

The **yolov4-custom.cfg**, **obj.data**, and **obj.names** files are customized for the 2 classes I am working with. (i.e. with_mask & without_mask) 

**<ins>NOTE</ins>: You can edit these files for your custom object dataset**



## Colab tutorial for training a custom Yolov4 detector. 

https://colab.research.google.com/drive/1zqRb08ljHvIIMR4fgAXeNy1kUtjDU85B?usp=sharing

## Check out my Medium article on this.

https://medium.com/@techzizou007/training-a-custom-detector-using-yolov4-darknet-61a659d4868

## Watch my YouTube video on this 

[Youtube Link](https://www.youtube.com)


![](video2.gif)




