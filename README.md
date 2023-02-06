# Stroma-Vision
This repository is created just for Stroma Vision.

```
PLEASE SEE "MAIN REPORT.pdf" FIRST!
```

```
USE "COCO JSON to YOLO Format.ipynb" to convert the data from COCO JSON to YOLO.
```

```
USE "MP4 to JPG FRAMES.ipynb" to generate frames from .mp4 file.
```


### Steps to run Code

```
1-  OPEN "Stroma_Challenge_YOLOv7_Training_File.ipynb" to train the model in Google Colab.
```

```
2-  ADD coco.yaml to folder panel located on the left of the screen in Google Colab.
```

```
3-  RUN CELLS and start training.
```

```
4-  ONCE THE TRAINING is completed, CREATE a folder named "test" and insert test.mp4 file into the "test" folder.
```

```
5-  RUN !python detect.py cell with the best weight. In my conditions, it is called "best_weight_yolov7.pt". 
    It can be found in the main branch. 
    This cell will provide the detection and classification only.
```

```
6-  USING the best weight from the training, you can OPEN "Stroma_Challenge_YOLOv7_Detect_Classify_Count_File.ipynb" to COUNT falling objects. 
    You need to CREATE a folder named "test" and insert test.mp4 file into the "test" folder.
```

```
7-  RUN !python /content/yolov7-object-tracking/detect_and_track.py cell with the best weight. 
    This cell will provide the counting video of falling objects.
```
