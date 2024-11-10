# RailRoad-ForeignObjectDetection
This project detects foreign objects on railroad tracks using computer vision and deep learning, enhancing the safety and efficiency of rail operations.
Project Overview:
The model is trained to recognise and segment foreign objects on railroad tracks using multiple advanced segmentation models. Classes considered for this project 
1. Balloons 
2. Plastic
3. Objects

Dataset:
	•	Training Set: 3,059 samples
	•	Validation Set: 628 samples
	•	Test Set: 628 samples
	•	Annotation Tool: Roboflow Polygon annotation tool was used for labeling, and masked images were generated using masked_extraction.ipynb.

Models Used:
	•	YOLOv8 Instance Segmentation - Input Image Size (640,640)
	•	UNET Segmentation - Input Image Size (336,336)
	•	DeepLabV3+ - Input Image Size (256,256)
