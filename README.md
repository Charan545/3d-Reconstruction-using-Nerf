# 3D Reconstruction using Neural Radiance Fields (NeRF)

## Overview
This project implements a cutting-edge 3D reconstruction pipeline that combines Neural Radiance Fields (NeRF) for neural volumetric rendering with Agisoft Metashape’s photogrammetry tools. The system creates highly detailed and photorealistic 3D scenes from 2D images, enabling novel viewpoint rendering and precise texture mapping.

## Features
- Continuous volumetric scene modeling using NeRF  
- Camera pose estimation using COLMAP  
- Sparse and dense point cloud generation with Agisoft Metashape  
- 3D mesh reconstruction and texture mapping  
- Python scripting for data preprocessing, training, and rendering  
- Optimization techniques to enhance 3D model fidelity


 Setup Agisoft Metashape and COLMAP as per their official instructions.
## Steps we implemented
1) We have taken a video of a ball.
2) Then we have extracted the frames from the video which is basically the ball from all sides or every point of view.
   
![Screenshot](001.png)    ![Screenshot](19.png)   ![Screenshot](20.png)  ![Screenshot](40.png)  ![Screenshot](149.png)  ![Screenshot](250.png)


3) Generate a detailed cloud that accurately represents scene geometry in the Agisoft MetaShape
4) Create a 3D surface mesh and apply realistic textures from source images.

![Screenshot](c.png)
![Screenshot](d.png)
![Screenshot](a.png)
![Screenshot](b.png)

## Usage
- Prepare images with known camera poses or run COLMAP for pose estimation.  
- Train NeRF model on posed images using provided scripts.  
- Render novel views and generate 3D mesh with texture mapping in Metashape.  

## Technologies Used
- PyTorch for neural radiance field modeling  
- Agisoft Metashape for photogrammetry and mesh reconstruction  
- COLMAP for camera pose estimation  
- Python for scripting and data processing  

## Applications
- Virtual reality scene generation  
- Cultural heritage preservation  
- Robotics and environment mapping

## Contribution
Contributions are welcome! Please submit issues or pull requests.

