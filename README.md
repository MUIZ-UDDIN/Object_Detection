Object-detection-using-YOLOv5-module-project
Contact Information:
• Name: MUIZ UD DIN

• Email: muizdin143@gmail.com

• GitHub Profile: https://github.com/mueez-uddin

Introduction:
In this group project, we had develop an object detection model for identifying various road conditions and turns in images captured on roads in Gilgit. The primary goal is to enable the model to detect right turns, left turns, straight roads, and unexpected road conditions such as landslides. This project is designed to provide hands-on experience in data gathering, data labeling, and the implementation of object detection models, specifically YOLO (You Only Look Once)

Phase 1: Data Collection:
I have collected diverse data of road images from Gilgit and from other areas. These images had covered a variety of road types. There are 5 classes (right turn, left turn, unexpected, straight and damaged), per class there are 10 or more than 10 images. total we have collected 57 images.

Phase 2: Data Labeling:
The code provided is part of a broader project that involves the implementation of object detection using the YOLOv5 algorithm. In Phase 2, which is not explicitly shown in the code, the data labeling process is essential for training the object detection model. The code assumes that this phase has already been completed, and a labeled dataset is available. The dataset is described as containing images with labels for different road conditions, such as right turn, left turn, straight road, and unexpected road conditions (e.g., landslides).

Phase 3: Classifier Training:
Although not directly evident in the provided code, it is inferred that a separate classifier has already been trained using the labeled dataset to categorize images into predefined classes. The code primarily focuses on the YOLOv5 object detection aspect. Evaluation metrics such as accuracy, precision, recall, and F1-score may have been used to assess the performance of the classification model. However, the code does not explicitly showcase this phase.

Phase 4: YOLO Implementation:
The code corresponds to Phase 4, where the YOLOv5 object detection algorithm is introduced and implemented. The implementation steps are outlined as follows:

Cloning the YOLOv5 Repository: Cloning the YOLOv5 repository from the official Ultralytics GitHub repository. This repository contains the YOLOv5 model and the necessary scripts for training and inference.
Installation of Dependencies: The code installs the required dependencies by running 'pip install' commands using the provided file. Additionally, it installs the 'roboflow' library, which may facilitate dataset management and integration.
Roboflow Integration:
The code integrates the Roboflow platform, presumably to facilitate dataset management. It uses an API key for access and downloads a specific dataset related to road turn detections. The dataset may contain images and associated annotations in YOLO-compatible format.
Object Detection on Validation Dataset:
The code then performs object detection on a validation dataset using the YOLOv5 model. It specifies the model's weights, input image size, confidence threshold, data source (the previously downloaded dataset), and requests to save various outputs, including bounding box annotations, confidence scores, and cropped object images.
Phase 5: Model Evaluation:
Phase 5, the model evaluation phase, is not explicitly demonstrated in the code, but it is typically performed after object detection. In this phase:

Assessment of YOLO Model: The YOLOv5 model's performance would be assessed using metrics such as Mean Average Precision (mAP) and Intersection over Union (IoU). mAP provides an overall measure of object detection accuracy, while IoU measures the overlap between predicted and ground-truth bounding boxes.
Fine-Tuning: Based on the evaluation results, the model may be fine-tuned to improve its accuracy and robustness. This process can involve adjusting hyperparameters, training for more epochs, or augmenting the dataset.
Evaluation Images: The report suggests showing one example image per class for evaluation. This would involve demonstrating the model's ability to detect different road conditions (right turn, left turn, straight road, and unexpected road conditions) accurately.
