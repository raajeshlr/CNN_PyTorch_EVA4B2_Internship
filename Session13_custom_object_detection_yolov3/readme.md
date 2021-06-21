Summary

OpenCV YoloV3 Annotated Image:

 <![My Image](https://github.com/raajeshlr/EVA4Batch2Repository/raw/master/Session13/opencvyolov3/images/tableannotated.png)>

YoloV3 Trained on Custom Dataset:

Trained YoloV3 with a dataset to detect Speakers.

1. Video -<https://www.youtube.com/watch?v=AbHJzfJvXSI>


Full Credits:

Open CV Yolo V3 - Default COCO Objects detection:
1. https://pysource.com/2019/06/27/yolo-object-detection-using-opencv-with-python/

YoloV3 on Custom Dataset:
1. https://github.com/theschoolofai/YoloV3
2. https://github.com/ultralytics/yolov3
3. https://github.com/raajeshlr/YoloV3



How to do :

- Take N number of images (I took 500) which you can get from video using ffmpeg or you can download google images too, I have converted my video itself to 500 images, refer ffmpeg demo folder.

- Bounding Box - Place your 500 images inside Annotation tool master folder (inside images folder), go inside annotation folder, open terminal and run commands (refer readme), it will create labels for your 500 images.
- Take your images, labels and keep that in Yolov3 master folder respectively and do other custom changes, refer https://github.com/theschoolofai/YoloV3
- I have made all this and create my own custom repo which I have used in my code - https://github.com/raajeshlr/YoloV3
- code - refer YoloV3Raajesh.ipynb