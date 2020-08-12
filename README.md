# Person_Tracking
The Code works by employing a yolov3 model for Object Detection. The yolov3 weights can be found by running  
```
!wget https://pjreddie.com/media/files/yolov3.weights
```
or by visiting from https://pjreddie.com/darknet/yolo/

The Risk Predictor looks at the centre of box and uses the distances to approximate closeness. This is obviously an incorrect metric but that is the best we
can do with a single image.

To run the code, keep everything in same directory and run

```
!python3 Risk_Predictor.py
```

Some outputs are as follows :

![Screenshot from 2020-08-13 01-16-44](https://user-images.githubusercontent.com/56398422/90060955-18dd0600-dd03-11ea-96ff-830c4f001f3f.png)
