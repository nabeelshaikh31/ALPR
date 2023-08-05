# Automatic License Plate Recognition System [Team: The Core]

## Prerequisite Packages

### OpenCV:-
For Windows:
pip install opencv-python

For Linux:
sudo apt install python3-opencv

### NumPy:-
For Windows:
pip install numpy

For Linux:
sudo apt install python-numpy

## Code & Files
### Our project performs the following steps:
Frame extraction from video - Done by videoframe.py.

License plate extraction - Done by plateDetect.py. 

License plate Recognition - Done by detectchar.py.

Creates a folder wherein the extracted license plate number is stored.

### How to run our project:
Download the "weights" file folder from "https://drive.google.com/open?id=1298i7Ocyq943klu08WKEIlLAimIfzTm3".
Add the weights folder to VLPR.
The test video should be added in the "Input" folder.
Open the terminal.

cd VLPD
python videoframe.py

Provide the proper filename with extension when it prompts.
Check output in the results folder.

## In order to enhance the computational perfromance a GPU setup is preferrable as it is 500 times faster than CPU.
