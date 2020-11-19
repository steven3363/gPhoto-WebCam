# gPhoto-WebCam
Uses gphoto  to create a virtual webcamera

A gambas project that is really just a skin. 

You will need gphoto2, v4l2loopback and gambas.

Also, I expect that your user is setup as SuperUser (sudo)
# Directions

# Install 
  gphoto2
  v4l2loopback 
  gambas3
  
  Check your distros for how to install
  

# Complile

Open gambas and then complile. 

or use one of the prebuilt files. a deb (Ubuntu not tested) and rpm (fedora)

# Running

1. Plug in your camera via USB
  if it is supported the name will appear in the form.
  
If you haven't perminatly set up v4l2loopback, complete step 2. Otherwise skip to step 5.

2. Goto the v4l2loopback tab 

3. Type your password (not saved)

4. Click Reset loopback devices
  This will add 2 devices. One for OBS one named after your camera.
  
5. Switch to the Webcam tab

6. If your camera is not an Canon M50 uncheck the box. 

7. Select the output device

8. Click on the 'Start'

# Trouble shooting

If you have any problems, try reseting your camera and stopping and Starting the Webcam app

Note: If you close the App the webcam will stop.

This is the first alpha version. I plan to support mutiple cameras and background removal / replacement

You can't reset v4l2loopback when the webcam is active

You will need to run reset v4l2loopback each time as it is not perminant



