# ECT(SuperEdge)face_recognition
This project is based on OpenCV library, uses Haar cascade and Dlib library for face detection and real-time tracking, and develops a relatively complete face recognition system using LBPH algorithm. The system uses SQLite3 to store serialized data, which can alarm the intrusion of unknown faces, and has GUI implementation based on PyQt5 design.

## ECT(SuperEdge) Project 
### Team introduction
![](images/LOGO.png)

ECT (SuperEdge) team has encountered difficulties and been blessed since its establishment. Block chain entrepreneurship itself is unknown. There are many mysteries waiting for us to discover and practice with time. Like science fiction, we are looking forward to the moment when we develop applications. We pay more attention to product lists. Clear and accurate, most of the team is science background, in the machinery, Internet, electronics, physics and other disciplines, we all have research, will learn things can be fully integrated into the block chain.

Now we have our own studio, server center, Design Library neural network testing center and negotiation team.

Later, we continued to innovate the combination of AI and edge computing, so that large data and AI complement each other and transfer from multi-dimensional cube to network.

Thank you again for your support.

## Face_Recognition XML
## How Does It Work?
The following operations are based on the Anaconda3 environment and tested on Windows 10 x64.
### Creating Python Virtual Environment
```
$ conda create -n opencv python=3.6
$ activate opencv
```
### Install OpenCV
```
$ cd face_recognition_py
$ cd modules
$ pip install opencv_python-3.4.1+contrib-cp36-cp36m-win_amd64.whl
```
### Install dlib
```
$ pip install dlib-19.8.1-cp36-cp36m-win_amd64.whl
```
### Install other dependency packages
```
$ cd ..
$ pip install -r requirements.txt
```
### Operating Core Framework
```
$ python core.py
```
### Running Face Acquisition System
```
$ python dataRecord.py
```
### Running Data Management System
```
$ python dataManage.py
```
### Exit from Virtual Environment
```
$ deactivate
```

## License
GPL-3.0
