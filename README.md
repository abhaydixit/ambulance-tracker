## Real-Time Object Detection and Tracking
#### Authors: 
- Abhay Rajendra Dixit
- Adya Shrivastava
- Nikhil Kaushik

#### All python notebooks were tested on Google Colaboratory with GPU. 

#### Dataset
All the images used for training and evaluation is uploaded on Google Drive due to storage constraints. To download the data, follow below steps:
- Download the `Dataset` folder, `val.text` and `train.txt` from https://drive.google.com/drive/folders/1E2zndzi83CIUSAHI1c2TC8AzUcAZGYUQ?usp=sharing
- upload it to the below path:
  `CVTermProject/ train/ data`

#### To run object detection - training
- Upload the CVTermProject folder to Google Drive
- Open the file CVTermProject-Training.ipynb
- Change the path of the configuration files (only if required)
- Run all the cells from first till the end.

Note: Sections "Data" and "Load the data" are one-time run sections.

#### To run object tracking
- Open the file CVTermProject-Tracking.ipynb
- Change the `BASE_PATH` to match the location of the configuration files and saved weights
- Run all the cells 

#### To evaluate the performance of object detection and tracking
- Open the file CVTermProject-Evaluation.ipynb
- Change the `BASE_PATH` to match the location of the configuration files and saved weights
- Run all the cells

Note: CVTermProject-Evaluation-Epochs.ipynb evaluates the model performance on every 25th epoch.


#### References
- https://github.com/cfotache/pytorch_custom_yolo_training
- https://github.com/cfotache/pytorch_objectdetecttrack
- https://github.com/Cartucho/mAP
