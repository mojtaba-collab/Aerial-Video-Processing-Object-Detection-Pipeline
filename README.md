\# Wild Cattle Detection \& Tracking via Drone Imagery



An advanced computer vision pipeline developed to detect, evaluate, and track herds of wild cattle from aerial drone video and imagery. Originally conceptualized during academic research at Sapienza University of Rome, this project features a modernized object detection workflow utilizing YOLOv8 and custom post-processing.



\---



\## 🚀 Key Features

\* \*\*Aerial Object Detection:\*\* Fine-tuned YOLOv8 on custom aerial datasets managed via Roboflow to accurately identify livestock from high altitudes.

\* \*\*Advanced Post-Processing:\*\* Integrated the `supervision` library to implement optimized Non-Maximum Suppression (NMS), resolving dense bounding box overlaps and reducing false positives.

\* \*\*Performance Evaluation:\*\* Evaluated model generalization and metrics across challenging flight conditions, producing detailed precision-recall curves and confusion matrices.



\---



\## 📊 Performance \& Validation Metrics



The model was validated against a held-out validation set, yielding strong baseline performance for aerial livestock monitoring:



\* \*\*mAP@0.5:\*\* 0.7167

\* \*\*mAP@0.5–0.95:\*\* 0.2744

\* \*\*Precision:\*\* 0.7069

\* \*\*Recall:\*\* 0.6598



\---



\## 📁 Repository Structure



```text

├── data/

├── test/

├── train/

├── valid/

├── weights/

├── output\_cleaned\_cattle\_2/

├── data.yaml

├── README.dataset

├── README.roboflow

├── Aerial\_Cattle\_Tracking\_Pipeline.ipynb

├── videos.mp4

├── metrics1.png

├── metrics2.png

├── metrics3.png

├── metrics4.png

├── metrics5.png

├── metrics6.png

└── README.md

