# Visual Cryptography

An implementation of various visual cryptography schemes, written in C++. The GUI was
developed in Qt Creator. 

To compile code, save all project files in a repository, open 'VisualCryptography.pro' 
with Qt Creator and build. The OpenCV library must be installed, which can be downloaded from 
https://sourceforge.net/projects/opencvlibrary/

GUI
Only a simple user interface was needed for the implementation, which would allow the user to
input the desired parameters and then display information. A simple and effective way to do
this was using a series of buttons, which progressed through the various stages of the schemes,
allowing the input and output of relevant information. These consisted of:
- Load Image: Allows user to select an image from file
- Choose Scheme: Select the desired scheme
- Set Parameters: Select the threshold k and number of shares n
- Generate Shares: Display the shares on screen
- Combine Shares: Select desired shares to be superposed and display superposition
- Save To File: Save image to disk

Once a design of the GUI was drafted, the GUI needed to be created and integrated with the
schemes that were developed using the OpenCV library. This was carried out in Qt, by
separately implementing each button and incorporating the appropriate schemes and functions
that had already been developed. Qt's design mode proved very useful in implementing various
elements of the GUI.

![image](https://user-images.githubusercontent.com/60361593/128558458-ef77c8b0-a805-4fdd-833e-21e96b059a1a.png)

