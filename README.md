# Data Visualization

I created this Python program in order to read in csv files of data and perform interesting analyses in a 3-D environment. Data can be moved around either with mouse controls or hands-free, using my hand-made webcam detectors. Run display.py with Python27 or higher in order to view the main the program (iOS Terminal: python27 display.py or python display.py depending on your setup). Ensure that you have numpy installed as welled. In the "pictures" folder, you can see pictures of the program running. 

Once the program has loaded, you can either use the top left menu or the shortcut (Cmd-O) in order to read in a csv data set. I provided a nice csv file of australia into the repository called australia.csv. Checks are built into the program in order to ensure the file is of the csv format. You can then click the Select Data button on the right in order to choose which variables appear on which axis. The first three variables will display in the x, y, and z dimensions and the fourth and fifth dimensions will be perceived through color and size respectively. You can move the data around with your mouse. You can scale the data by pressing down on the scroll button on a mouse and then scrolling up or down. You can rotate the data by using the right click of a mouse or Cmd-click.

In addition, you can perform linear regression, clumping, and PCA analysis on the data taken in using the top menu bar. 

Finally, I built computer vision into the program by making a couple of detectors from scratch (shown in the pictures folder). Using them, you can scale, pan, or rotating the data with hand motions. The code for this computer vision is mostly contained in the video file as the video class. I utilized the openCV library in Python. 

