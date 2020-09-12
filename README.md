# People-Counting-yolov5

It is my bachelor thesis and its aim is to detect people and pass them into tracking phase

![Alt Text](https://github.com/bardiakzzzz/People-Counting-yolov5/blob/master/images/output.gif)


## Requirements

Python 3.8 or later with all [requirements.txt](https://github.com/bardiakzzzz/People-Counting-yolov5/blob/master/requirements.txt) dependencies installed. To install run:
```bash
$ pip install -r requirements.txt
```

## Train

1. open the notebook file in google colab and all details are elaborated

## Test

1. clone yolov5 repository
1. cd yolov5
1. pip install -r requirements.txt
1. for detection use command below :
  python detect.py --source 'directory of image or video ' --weights 'directory of your pt file'
1. go to inference/output directory in order to see the results  

## References

 * [yolov5](https://github.com/ultralytics/yolov5)
