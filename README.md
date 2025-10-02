Geo-tagging and Tracking for Detected Vehicles using UAV (SHIV-NATARAJ Dataset)
 Overview

This project was developed in Google Colab to detect, track, and geo-register vehicles from UAV (drone) footage.
It combines YOLOv11n-OBB for detection, ByteTrack for tracking, and homography transformation for pixel → GPS mapping. The outputs are exported as KML files for Google Earth visualization.

 Key Features

Run entirely in Google Colab (no local setup required).

Object detection with YOLOv11n-OBB.

Multi-object tracking using ByteTrack.

Geo-tagging using homography transformation.

Visualization of results on Google Earth.

🛠️ Tech Stack

Languages: Python, OpenCV, NumPy

Models: YOLOv11n-OBB, ByteTrack

Tools: Google Colab, Google Earth

Dataset: SHIV-NATARAJ UAV Dataset

Project Structure
GeoTagging-UAV-Vehicles/
│── UAV_GeoTagging.ipynb   # Main Colab notebook with detection, tracking, and geo-tagging
│── results/               # Output videos & KML files
│── requirements.txt       # Python dependencies
│── README.md              # Project documentation

How to Run (Colab)

Open the notebook in Google Colab:


Upload the UAV dataset (video).

Run the cells to:

Detect & track vehicles.

Apply geo-tagging using homography.

Export results as .mp4 (processed video) and .kml (Google Earth overlay).
