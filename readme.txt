The most important part is in joystick.cs (attached to gui_joystick under canvas).

By default, the 'accelerometer' is checked.  The GUI joystick will override it if used.

There is an option for 'gyro', however use it for your own purposes, as it is not perfected in this demo (no real intermediary between left/right).

To test with Unity Remote make sure you have the build platforms installed and if needed iTunes (if using iOS device on a Windows machine).

Make sure in Project Settings -> Editor -> Device you select 'Any iOS Device' or whatever device you are using.

![alt text](https://github.com/ChristianFager/mobile_skiing_accelerometer/blob/main/mobile_skiing_accerometer.png?raw=true)

Thanks to the people in the Unity forums for help with the lowpass & pitch/roll calculations.
