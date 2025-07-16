                                                                         Re-Identification Assignment player tracking
 Project Overview:
 
 This project implements player detection on a football match video using YOLO. The model detects
 players in each frame and assigns IDs per frame, visualizing bounding boxes around each detected
 player.

 
 How to set up and run the code:
 1. Install dependencies:
   pip install ultralytics opencv-python

 2. Upload your video file (e.g., broadcast.mp4) to your Colab or local directory.
    
 3. Run the Python code to:
   - Initialize YOLO model.
   - Read video frames.
   - Perform detection.
   - Draw bounding boxes and IDs.
   - Save the output video as output_video.mp4.

     
 Dependencies / Environment requirements:- 
 Python 3.x
- Ultralytics (YOLO)
- OpenCV (opencv-python)
- Google Colab or local Jupyter Notebook

File descriptions:- broadcast.mp4: Input football match video.- output_video.mp4: Output video with player detections and bounding boxes.
