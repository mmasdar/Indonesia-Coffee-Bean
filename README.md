# Data Acquisition, Pre-Processing, and Model Development for Coffee Bean Analysis
This project focuses on data acquisition, pre-processing, and model development for analyzing coffee beans.

![Image Alt Text](https://github.com/mmasdar/Indonesia-Coffee-Bean/blob/main/Design%20Dataset%20Acquisition%20Platform%202.jpg)

## Data Acquisition
We employ a data acquisition process that includes a lighting platform with RGB adjustment capabilities and a scaling plate. The lighting platform ensures consistent and controlled lighting conditions, while the RGB adjustment allows precise control over the light's intensity and color composition. Additionally, the scaling plate provides accurate measurements of coffee bean sizes, enhancing the reliability of subsequent analyses.

<p float="left">
  <img src="/Design%20Dataset%20Acquisition%20Platform.jpg" width="100" />
  <img src="/Dataset%20Acquisition%20Process.jpg" width="100" /> 
</p>

## Pre-processing
During the pre-processing stage of coffee bean analysis, several techniques are applied to enhance the quality of the acquired images. This includes edge detection to identify the boundaries of coffee beans, contour detection to extract their shape information, and morphology operations to refine the bean contours. Furthermore, the pre-processing stage involves separating each coffee bean from the image to ensure individual analysis. By employing these techniques, the pre-processing process enables improved segmentation and extraction of essential features from coffee bean images, facilitating accurate and comprehensive analysis.

![Image Alt Text](https://github.com/mmasdar/Indonesia-Coffee-Bean/blob/main/Lightning%20Effect%20for%20Acquisition.jpg)
![Image Alt Text](https://github.com/mmasdar/Indonesia-Coffee-Bean/blob/main/Edges5-100.jpg)

## Model Details
The coffee bean analysis model utilizes deep learning techniques to classify and analyze coffee beans. It is trained on a dataset of coffee bean images, covering different varieties and quality levels of coffee beans. The model aims to accurately classify and provide insights into the quality and characteristics of the coffee beans.

![Image Alt Text](https://github.com/mmasdar/Indonesia-Coffee-Bean/blob/main/FlowChart%20kopinet.jpg)
![Image Alt Text](https://github.com/mmasdar/Indonesia-Coffee-Bean/blob/main/kontras%20-%20asm%20-%20energi%20-%201.png)

# Getting Started
To begin working on the coffee bean analysis project, follow the steps below:

## Clone the repository to your local machine.
- Install the required dependencies listed in the Prerequisites section.
- Acquire the coffee bean dataset, ensuring it includes a variety of coffee bean images.
- Pre-process the dataset by cleaning, resizing, and augmenting the images as necessary.
- Develop a model for coffee bean analysis using deep learning techniques.

## Prerequisites 
- Python 3.7 or higher 
- TensorFlow 2.0 or higher 
- OpenCV
- Numpy
- Matplotlib

