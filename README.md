# Annotation tool for YOLO
Instructions -

Find the dataset corresponding to the number assigned above from this link.

Clone this repo (or download it if cloning doesn’t work).

Place the images which are to be labelled in "Images/001/" folder.

Please do not change the names of the folder, the variables in the code are adjusted accordingly.

First run the main.py file. A new window would appear which will ask for the Image directory enter 001 for that, then click on load, then start your work.

Note that you have to annotate the “first 3 T-shapes visible in image”, that is 3 bounding boxes per image. And then click next. And do the same for subsequent images.

Once you're done with annotation then run convert.py. Then rename the “001s” folder to “<number>L” (ex : “6L”) and add it to the same drive folder.

After running main.py if it shows an error “No module named tkinter”, run the following.

$ sudo apt-get install python3-tk

For python3 users in main.py replace the 10th and 11th line with-

import tkinter

from tkinter import *

import tkinter.messagebox

