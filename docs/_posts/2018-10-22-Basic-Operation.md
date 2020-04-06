---
date: 2018-10-22
title: Basic Operation
categories:
  - manual
author_staff_member: sh_akira
---

Virtual Motion Capture Basic Operation

![After Starting](../images/manual/1-1.png)

## Opening the VRM Model File

Press the Open VRM button and the Import VRM dialog will open.

![Open VRM Button](../images/manual/1-2.png)

Press the Import VRM button in the top left and the Open File Dialog will open.

![Import VRM Button](../images/manual/1-3.png)

Choose the VRM file you want to open.

![VRM File Open Dialog](../images/manual/1-4.png)

Be sure to check the permissions in the license.  If there are no problems, press the Agree / Import button.

![Agree Import Button](../images/manual/1-5.png)

The model will be loaded and the program will return to the main screen.

![Model finished loading](../images/manual/1-6.png)

If the model doesn't appear, go to the Camera tab on the Control Panel and choose Front. This will put the model into the middle of the screen.
If the model still doesn't appear there could be a problem with the VRM model. This can happen especially with if it is using a shader that cannot be used with VRM.

![Front Camera](../images/manual/1-7.png)

Once the model is loaded you need to calibrate it.
On the Settings tab, click on Calibration

![Calibration Button](../images/manual/1-8.png)

Once you click the Calibration button it will calibrate after 5 seconds.

![Begin Calibration](../images/manual/1-9.png)

After 5 seconds calibation will start.  This is to correct for the difference between the avatar and the actual body shape.  Reach out your arms to either side and hold the controllers with the palm of your actual hand facing forward.

![Calibration Finished](../images/manual/1-10.png)

Do not hold the controller totally vertical or horizontal but naturally at an angle.  This will be the same for the Oculus Touch. During calibration the height of the hands is especially important.  Before calibration, look to your left and right hands and confirm they are level.  If the hands are slightly lower the actual height will be measured incorrectly and afterwards there is a possibility of not matching up within the game.

![Calibration Pose](../images/manual/1-11.png)

Once calibration is complete the model on the screen should match your own movements. If the direction of the palms are off, confirm that the calibration is done similar to the image above. You can calibrate as many times as needed so try again if something is off.

![Successful Calibration](../images/manual/1-12.png)

Although using just a headset and two controllers will work fine, if you have LIV installed or have multiple trackers for full body tracking it may not autodetect properly.  In that case you can assign the trackers manually.  
First press the Settings button.

![Settings Button](../images/manual/1-13.png)

In the Settings screen press the Open tracker assignment settings button.

![Open tracker assignment settings Button](../images/manual/1-14.png)

This opens the screen that displays a list of all recognized controllers and trackers and the tracker assignment settings.  
By default everything is set to AutoDetect.

![Tracker Assignment Settings](../images/manual/1-15.png)

If autodetect doesn't work, manually assign the trackers to each body part.  If you move the tracker it will be highlighted in green allowing you to assign them one by one.  Set the body parts that do not have trackers to "No Assign."

![Correct Trackers Listed](../images/manual/1-22.png)

When all the trackers are assigned, close the Settings screen and calibrate again.  If the calibration is successful, the whole body will move.

![Full Tracking](../images/manual/1-23.png)

After confirming that the model is moving properly the next thing to set is for lip sync.
From the control panel go to the LipSync tab and click on the Device drop down list. This shows a list of audio devices available.  Select the device to be used for lip sync.

![Lip Sync Settings](../images/manual/1-24.png)

Once you have selected the device, speak into the mic and the model's mouth should also move.  If it only moves a little or not at all try increasing the microphone sensitivity.

![Finished Setting Lip Sync](../images/manual/1-25.png)

After setting up lip sync, the last thing is the controller settings. Click on the Shortcut key button on the Settings tab.

![Shortcut key Button](../images/manual/1-26.png)

The default preset is "VRChat+(Vive)." 
If you are using an Oculus Touch or a VRoid model, you will need to change to the appropriate preset.
You can also create your own custom preset by assigning keys yourself.  You can use not just the controllers but also the keyboard allowing you to customize in various ways, such as changing the expression with the keyboard while in a game where you need to use trackers for hands.

![Shortcut Key Settings](../images/manual/1-27.png)

Once you have finished changing settings you should save them.  The next time you can use Open settings to load them again so you don't have to set everything up again.

![Save settings](../images/manual/1-28.png)

This concludes the basic settings.  From here you can set the background color to green for chroma keying, use the free camera to record from different angles and change other settings to suit your usage.  The next few pages will explain the use of the externalcamera.cfg file to do Mixed Reality Compositing.
