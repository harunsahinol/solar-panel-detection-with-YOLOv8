# Solar Panel Hotspot Detection using YOLOv8

This project aims to detect hotspot areas in solar panels using the YOLOv8 object detection model. The model has been trained on a dataset obtained from Roboflow and trained in Google Colab.

###  Dataset
The dataset used for training the model was sourced from Roboflow, which provides a diverse collection of annotated images suitable for training computer vision models. The dataset contains images of solar panels with annotations indicating the presence of hotspots.

### Training
The model was trained using the YOLOv8 architecture, a state-of-the-art object detection algorithm known for its accuracy and efficiency. The training process involved optimizing the model to accurately detect hotspot areas in solar panels.

### Code
The code for training and evaluating the YOLOv8 model can be found in the hotspot_detection.ipynb file. This Jupyter Notebook provides step-by-step instructions on loading the dataset, configuring the model, training it, and evaluating its performance.

### Usage
To use the trained model for hotspot detection in solar panels, follow these steps: 
1. Clone the repository to your local machine.
2. Open the hotspot_detection.ipynb file in a Jupyter Notebook environment or any compatible platform.
3. Follow the instructions provided in the notebook to load the model and perform hotspot detection on your own images or videos.

### Requirements
To run the code and perform hotspot detection, ensure you have the following dependencies installed:

- Python 3.x
- PyTorch
- OpenCV
- Other dependencies as specified in the `requirements.txt` or in the code.

### Acknowledgements
The dataset used in this project was obtained from Roboflow.
The YOLOv8 architecture was implemented.
