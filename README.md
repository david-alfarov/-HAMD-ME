# -HAMD-ME
Human Action Monitoring Dataset in Manufacturing Enviroments

## Description
The dataset was generated on a workstation with three cameras to capture multimodal data. 
The recordings take at the Human Factors Laboratory of the School of Industrial Engineering.   
All captures are recorded simultaneously and synchronized to facilitate multimodal data analysis. 

The dataset is composed of video captures of 3 views while a person performs wiring tasks. A camera has been placed in the top view, side view, and front view.

The top and side views take using Logitech C310 cameras. The front camera is a Microsoft HD camera. 
All cameras used are high-definition cameras with autozoom. The quality of the videos is 1280 x 720 pixels with a frame rate of 30 frames per second. All videos have no audio.

The dataset was build involving male and female participants. All the videos show the assembly and disassembly operations of the product shown .
The Assembly consists of 3 gears, 3 shafts, 8 sinkers, nuts, and bolts. 

In the top view the following has been captured: hands, tools, and items to assemble the product. In this view we have also labeled the following actions:

1. Hold
2. Release
3. Screw

These actions are performed with all the tools. 
The tools used in the experiments are the following:

1. Wrench
2. Allen Key
3. Ratchet
4. Screwdriver

In the side view, the skeleton of the person has been labeled, where it is possible to analyze the posture of the person when executing the actions.

In the front view there is a capture of the person's face, where it is possible to analyze if the person shows signs of fatigue while performing the work

## Download the Dataset
The datset annotations have been generated for YOLO and can be downloaded at the following link:
https://drive.google.com/drive/folders/1vJ_FeODlzWD3s3dblOJeiMEB2b05Wubw?usp=sharing
## Download from Roboflow
📦 Dataset Overview
This dataset contains 2,405 annotated images captured from a top-down perspective in a manual assembly workstation. Each image includes bounding box annotations for various tools, components, and operator interactions.

🔹 Dataset Split
Training set: 2,220 images (92%)

Validation set: 93 images (4%)

Test set: 92 images (4%)

The dataset is structured for computer vision tasks such as object detection, human-tool interaction analysis, and action recognition in industrial settings.

🔗 Access
The dataset is hosted on Roboflow and can be accessed and downloaded from the following link:
https://universe.roboflow.com/universidad-de-costa-rica-ifroi/manufacturing-tool-detection/dataset/1
