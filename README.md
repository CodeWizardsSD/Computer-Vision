# Computer-Vision #

## How to install all the nessiary packages for develop this software ##
```
pip install opencv-python
pip install mediapipe
pip install opencv-python-headless numpy
pip install numpy
python3 -m pip install git+https://github.com/RedFantom/ttkthemes
python3 -m pip install pystray
```

Then you can import libary with 
```
import cv2 as cv
```
 
## If you are working with Visual studio and wonders how to create your IntelliSense for cv2 here is how ##
use the find_cv2_path.py file to find your installed cv2 location, Then create a folder with the name .vscode and create a file within the folder called settings.json
This file will adjust your visual studio code's settings.

Write the settings below:
```
{
    "python.autoComplete.addBrackets": true,
    "python.analysis.autoSearchPaths": true,
    "python.analysis.extraPaths": ["path/to/your/opencv/python/library"]
}

```
make sure to insert the path that you find in the cv2 location python file into the python.analysis.extraPaths parameter replacing the string.