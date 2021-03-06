## Surveillance Camera Using Raspberry Pi

This project aims to make a surveillance camera using motion detection using **Raspberry Pi** and **Android**. System will take pictures automatically  when there are have moving objects and notify to the user. In addition, the resulting image will be automatically upload in to the  cloud storage **Drobox**. Picture bellow this is the block diagram that represent about this project

<img src="./asset/block_diagram.JPG" >

### Install requirements

you need to set you working environment as a project requirement,   you can make a virtual environment and install the important library following this command line:

```
$ pip install -r requirements.txt
```

### Running the program

you can running use following command bellow this:

```
$ python main.py
```

### Motion detection based on face detection open-cv

<img src ="./asset/detect.JPG" >

Using LINE notify can send the automatic announcement when have object detected

<img src= "./asset/notify.JPG" >

Then the system will automatically upload the picture to cloud storage (Dropbox)

<img src="./asset/dropbox.JPG" > 

### Video demo 

[![video demo](http://img.youtube.com/vi/q0oBydkTq3U/0.jpg)](https://www.youtube.com/watch?v=q0oBydkTq3U "video demo")
