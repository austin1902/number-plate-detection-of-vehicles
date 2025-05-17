#Number-Plate-Detection-of-Vehicles

 Number Plate Detection of Vehicles is that uses optical character recognition (OCR) to automatically read license plate characters. 

 it involves three major steps:

1.	Number Plate Detection – This is the most important stage of the system. At this stage, the system determines the position of the number plate, inputs an image of the vehicle, and outputs the license plate.

2.	Character Segmentation – This stage is where the characters on the number plate get mapped out and segmented into individual images.

3.	Character Recognition – This stage is where the segmented characters are identified.

Here, the system uses Python, OpenCV and Tesseract to identify vehicles by their Number plates and stored them along with the date and time in a CSV file. OpenCV is used to detect number plates and Python Tesseract is used to extract characters and digits from the number plates.
