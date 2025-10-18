# QR Code Detection Project

This project focuses on QR code detection and decoding using Huawei Cloud services together with Python-based computer vision tools.  
It integrates Huawei OBS (Object Storage Service) and ModelArts for cloud-based storage and processing, while utilizing OpenCV, Pillow, and ipywidgets for image manipulation and visualization in Jupyter Notebook.

## Project Overview

The main goal of this project is to automatically detect and decode QR codes from uploaded images.  
When an image is uploaded to Huawei OBS, it can be processed through ModelArts or in a local Jupyter Notebook environment using OpenCV-based detection scripts.  
The system identifies the QR code in the image, decodes the embedded data (such as URLs or text), and generates a preview with bounding boxes around detected areas.

<img width="1049" height="542" alt="Ekran Resmi 2025-10-17 09 24 16" src="https://github.com/user-attachments/assets/4f81505c-797d-4692-b100-d3f108936ff2" />

<img width="1049" height="679" alt="Ekran Resmi 2025-10-17 09 24 01" src="https://github.com/user-attachments/assets/0f7f09c0-54df-4986-a1fa-1c02193f50df" />


## Technologies Used

- **Huawei Cloud OBS (Object Storage Service):** For uploading and storing image files  
- **Huawei ModelArts:** For managing and deploying AI-based processing workflows  
- **OpenCV:** For QR code detection and image processing  
- **Pillow (PIL):** For image manipulation and annotation  
- **ipywidgets:** For building interactive UI elements within Jupyter Notebook  
- **Python:** For the main backend logic and QR code processing  
- **Jupyter Notebook:** For development, visualization, and testing


## Features

- Upload images directly to Huawei OBS  
- Automatic or manual QR code detection and decoding  
- Decode QR data such as links, contact information, or text  
- Visualize results with bounding boxes and decoded outputs  
- Save both annotated images and detection results (JSON) to OBS  



