# Automated Traffic Monitoring System
## Overview

This documentation details a prototype developed for traffic monitoring using OpenCV for computer vision applications. The prototype is designed to analyze and detect moving objects in traffic videos, fulfilling requirements set by a city's need to monitor vehicle flow from downtown to the city center.

## Install and run 
- Download and unzip the repo
- Open the folder with a IDE that can run jupyter notebook and run all the cells

## Requirements of the client

- **Development of an application** for detecting and tracking moving cars in video recordings.
- **Creation of a computer vision application** for counting the number of cars traveling from the city’s downtown to the city center within a specified time interval.

## Approach

### Requirement 1

<img width="776" alt="Screenshot 2024-03-26 124112" src="https://github.com/joseortega9988/traffic_monitoring_system/assets/77720475/1099938b-7192-4ebf-b216-12caa0bbc419">

- Frame-by-frame video analysis for identifying and counting moving objects.
- Application of background subtraction and image processing methods (e.g., Gaussian blur, thresholding, morphological operations) for enhanced detection accuracy.

### Requirement 2
<img width="780" alt="Screenshot 2024-03-26 124256" src="https://github.com/joseortega9988/traffic_monitoring_system/assets/77720475/2298c6ed-1f68-458c-8c77-f74738150259">

- Extension to multiple videos with emphasis on result presentation.
- Calculation of total car counts and rates per minute, displayed in a tabular format.

## Key Processes

- **Frame Extraction and Noise Reduction**
- **Object Detection via Background Subtraction**
- **Contour Processing and Object Identification**
- **Enhanced Tracking**

## Conclusion

The prototypes demonstrate the effective application of computer vision techniques for traffic monitoring, from initial video processing to advanced object tracking. This system showcases the capability of analyzing traffic flow and counting vehicles with high accuracy.

**See documentation.pdf in the repositary to have more details**

