This is a program I did while applying for an internship. The program needs an input video and it uses dlib and  cv2_imshow to blur the faces shown in the video.
Given with this code is input screen shots (labelled 1,2,3,4,5)  and output shots ( labelled 1-blurred, 2-blurred, 3-blurred, 4-blurred, 5-blurred)
-----------------------------------------------------------------------------------------------------------------------------
After some trial and error later in life, I prototyped this to work with the user in mind. It now works using the media pipeline with new knowledge learnt. Granted it's not perfect yet, I'm optimizing it in no internet in Mangalore, but it works fine for the most part. It's my first year project a month or two into university.

https://rivapereira123-face-blurring-app.hf.space/?__theme=system&deep_link=72WoKrbf_Lc

# ✅ Current Functionality of My Face Blurring App
Upload Video Files Directly

You can upload a local video file (e.g., .mp4, .mov) through the Streamlit UI.

The app processes the uploaded file, detects faces frame by frame, and blurs them.

Face Detection and Blurring

It uses a face detection model (likely OpenCV’s Haar Cascade or a similar method).

Detected faces are blurred in every frame of the video.

The output is a processed, blurred video with faces anonymized.

Download the Blurred Video

After processing, the app provides a download link to retrieve the blurred video.

# Streamlit UI Flow

UI elements allow for:

File upload

Triggering the blur process

Downloading the output
