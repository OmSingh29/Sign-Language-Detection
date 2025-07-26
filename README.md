# SignLanguageDetectionUsingML

1) Gather the data for training by executing following command
```
python collectdata.py
```
Webcam window will open, in blue window make appropriate sign and then press character associated with it on keyboard, this will record image , number of key presses = number of images recorded.

2) Then to convert images to numpy array, run:
```
python data.py
```

3) Then to train the model on numpy array, run:
```
python trainmodel.py
```

4) At last execute
```
python app.py
```
Then a webcam window will open, in which you can show the sign and get prediction by model.

Note : 
1) "functions.py" contain functions needed to process images
2) Press q to turn off the camera.
