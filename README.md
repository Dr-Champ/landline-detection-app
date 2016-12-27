# laneline-detection-app

A simple Android app to detect laneline on the road. 

## Usage and Disclaimer

This is a simple app to serve as a starting point on how to set up and use Android / OpenCV APIs to process continuous video frames and detect lanelines on the road. You can swap the detection class with your own by simply implementing the <code>ILaneFinder</code> and use it in the <code>Mainactivity</code>.

You need to get OpenCV for Android from <a href="http://opencv.org/downloads.html">here</a> (I use the latest version 3.10) and configure your Android Studio to include it as a dependency module for your project. This <a href="http://stackoverflow.com/questions/27406303/opencv-in-android-studio">stackoverflow post</a> is a really good step-by-step guide on how to configure your environment.

At the time being, I do not have concrete plan to improve the app further yet. Adding a setting menu to allow adjusting various OpenCV parameters in real time would be nice, along with improved detection pipeline itself to be more robust to noises in the image. Feel free to make improvements and ask for a pull request.
