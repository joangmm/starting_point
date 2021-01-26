# starting_point
This is the Unity Project that can be used as a starting point if you want to develop a Unity project that uses the PoseNET Tracking System.

Of course, as I stated in the written document, to have PoseNET tracking your movements, you should follow these steps:

Step 0: Clone [this github repository.](https://github.com/tommymitch/posenetosc)


Step 1: Download "node" from [their official page.](https://nodejs.org/en/download/)

Step 2: Install the last stable version of yarn that we can find [here.](https://classic.yarnpkg.com/en/docs/install/#windows-stable)

Step 3: Open the command line, go to the folder posenetosc-master (that is inside the repository that we just downloaded) and type: 
> yarn
to install the dependencies (it can take several minutes).

Step 4: Open a new command line, go to the folder posenetosc-master and type:
> node bridge.js
and keep that command line open.

Step 5: Open another command line and go to the folder posenetosc-master again, and this time type:
> yarn watch
and we must keep that command line open as well.

This will open a new browser tab, where we are going to be able to see the image captured by our webcams in real time, and the keypoints that are being tracked by PoseNET. We should keep that tab opened as well as the two command lines (from step 4 and 5), and when clicking on the "Play" button in Unity, we can see that the cubes in the scene are moving according to our real movement.
