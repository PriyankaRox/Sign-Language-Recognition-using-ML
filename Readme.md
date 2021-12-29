# Project Title
Sign Language Recognition Using Hand Gestures Keras PyQT5 OpenCV

## Getting Started
All the source code is available inside SourceCode Directory. It requires python version 3.6 or later as to synchronize with tensorflow.
* winGuiAuto.py available inside source code directory contains the hwnd handler which is used to tweak the default window behavior much similar to windows programming.
* The Recognise.py will recognise the gesture as per the trained dataset, recogniseAppend.py file will make a formation of sentences. These are acting as the stubs for this project. This project has been developed module wise and then has been integrated into a whole full fledge application. Long press 'escape' key for exiting a window.
* gestfinal2.min.mp4 is the introductory video demonstration of the complete application. icons and UI_Files directory contains all the necessary front end assets.
* Capture.py file will help in creating your own dataset and cnn_model.py file will use cnn deep neural nets to train your model and store it in the form of hadoop distributed (h5) format.
* Build the model with name "ASLModel.h5" using cnn_model.py or give any name just modify the line 38 inside "Dashboard.py"
* Install the required libraries and packages.
* Start using the application by simply double clicking "Dashboard.py"
* If you want to move the placing of the window then simply refer to the coordinates available inside cv2.moveWindow() functions.


### Prerequisites

* python 3.6 or later
* pyqt5, tkinter
* keyboard
* winGuiAuto
* pypiwin32
* pyttsx3
* tensorflow
* keras
* scipy
* opencv
* qimage2ndarray
* keras
* pillow


### Installing

Download the software setups and follow the on screen instructions

step 1

```
Installing python 3.7.1 can be downloaded from below link
```
[Click here to visit download page](https://www.python.org/downloads/release/python-371/)

step 2

```
Installing pyqt5 with the following command
```
```
pip install pyqt5
```
*Note: If getting error related to 'No module named PyQt5.sip' you are expected to do as follows:<br>
pip uninstall PyQt5 PyQt5-sip PyQtWebEngine<br>
pip install PyQt5* <br>
[Reference link](https://stackoverflow.com/a/58880976)

step 3

```
Installing keyboard with the following command
```
```
pip install keyboard
```

step 4 (optional)

```
Downloading winGuiAuto.py from the below link, and pasting it to Python installation directory->Lib->Site-Packages
make sure path is registered on system variables.
```
[Click here to visit download page](https://github.com/arkottke/winguiauto)

step 5

```
Installing win32api,win32con,win32gui with the following command
```
```
pip install pypiwin32
```

step 6

```
Installing pyttsx3 with the following command
```
```
pip install pyttsx3
```

step 7

```
Installing tensorflow framework with the following command
```
```
python -m pip install tensorflow --trusted-host files.pythonhosted.org --trusted-host pypi.org --trusted-host pypi.python.org
```
```
For upgradation use the following command
````
```
pip install tensorflow==2.0.0-alpha0
```

step 8

```
Installing keras with the following command
```
```
pip install keras
```
*Note: (if keras doesnt work just replace keras.model to tensorflow.keras.model and keras.preprocessing to tensorflow.keras.preprocessing on line 37 and 156 respectively)*

step 9

```
Installing PIL with the following command
```
```
pip install pillow
```

step 10

```
Installing qimage2ndarray with the following command
```
```
pip install qimage2ndarray
```

step 11

```
Installing scipy with the following command
```
```
pip install scipy
```

step 12
```
Installing opencv for python with the following commands
```
```
pip install opencv-python==3.4.2.16
```
```
pip install opencv-contrib-python==3.4.2.16
```



