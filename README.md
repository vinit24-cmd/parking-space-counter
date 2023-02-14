# parking-space-counter


This project uses image processing and computer vision techniques to count the number of available parking spots in a given parking lot. The output of the program is the number of available spots out of all the available spots in the lot.

How it works

The program works by manually defining regions of interest (ROIs) for each parking spot in the lot. The program then counts the number of pixels in each ROI and sets a threshold to determine whether the parking spot is free or occupied. The program then counts the number of free spots and returns the total number of available spots.

Requirements:

To run the program, you'll need to have Python 3 and the following Python packages installed:

NumPy
OpenCV
Matplotlib

You can install these packages using pip:


pip install numpy opencv-python matplotlib


Usage:

The program consists of two Python files:

main.py: The main program file that performs the parking space counting.

parking_space_picker.py: A utility program that allows you to manually define the ROIs for each parking spot in the lot.


To use the program, follow these steps:

Run parking_space_picker.py to define the ROIs for each parking spot in the lot. This program will display the parking lot image and allow you to draw rectangles around each parking spot.

python parking_space_picker.py
Once you have defined the ROIs, run main.py to perform the parking space counting. This program will display the parking lot image with each parking spot labeled as "free" or "occupied", as well as the total number of available spots.

Run python main.py

License:

The code in this repository is licensed under the MIT License. Feel free to use it for your own projects or research.


Credits to Murtaza Hassan opencv Workshop
