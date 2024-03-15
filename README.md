GIF Video Editing Tool

This tool is designed to perform editing operations on GIF videos. It allows you to process each frame of a GIF video, apply operations such as Singular Value Decomposition (SVD), and generate an image based on the processed frames.

Features

Frame Processing: The tool processes each frame of the input GIF video.
Singular Value Decomposition (SVD): It applies SVD to the frames of the video.
Frame Modification: The processed frames can be modified using various operations.
Output GIF Generation: After processing and modifying the frames, the tool generates a new GIF video with the modified frames.
Requirements

Ensure you have the following dependencies installed:

Python 3.x
OpenCV (cv2)
Matplotlib (matplotlib)
MoviePy (moviepy)
ImageMagick


Usage

Prepare Input GIF: Place the GIF video you want to edit in the videos directory.
Run the Script: Execute the script gif_editor.py.
Follow Instructions: The script will prompt you to enter the number of the video you want to edit and the time interval between frames.
Wait for Processing: The script will process the frames of the GIF video and generate a modified version.
Check Output: Once the script finishes execution, you can find the modified GIF video in the output directory.
Note

Ensure the input GIF video is placed in the videos directory and the output will be saved in the output directory.
