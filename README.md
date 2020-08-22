# Background-Subtraction

Background subtraction is the process of separating out foreground objects from the background in a sequence of video frames.
Background subtraction is a widely used approach for detecting moving objects from static cameras.
Logic behind the background subtraction is to find absolute difference between background image and current frame. After that apply some thresholding.
It is widely used in traffic monitoring, human action recognition, object tracking and in many other application of computer vision.

# Frame Differencing

Process for finding frame difference is same as a background subtraction but instead of using background image, frame difference uses previous frame and find absolute difference between current frame and previous frame.
