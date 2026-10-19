
# Aerial Video Processing & Object Detection Pipeline

An applied computer vision pipeline developed to detect, evaluate, and monitor herds of wild cattle from aerial drone video feeds and imagery. Originally conceptualized during academic research at Sapienza University of Rome, this project features a modernized detection workflow utilizing YOLOv8 and custom stream post-processing.

---

## 🚀 Key Features

* **Aerial Object Detection:** Fine-tuned YOLOv8 on custom aerial datasets managed via Roboflow to reliably detect small-scale livestock from high-altitude drone perspectives.
* **Stream Post-Processing:** Integrated the `supervision` library to implement custom Non-Maximum Suppression (NMS) thresholds, eliminating spatial bounding box overlap and computing real-time in-frame herd counts.
* **Performance Evaluation:** Evaluated model generalization across challenging flight angles and terrain backgrounds, generating validation metrics, precision-recall curves, and confusion matrices.

---

## 📊 Performance & Validation Metrics

The model was validated against a held-out aerial validation set:

* **mAP@0.5:** 0.7167
* **mAP@0.5–0.95:** 0.2744
* **Precision:** 0.7069
* **Recall:** 0.6598

---

## 📁 Repository Structure

```text
├── data/
├── test/
├── train/
├── valid/
├── weights/
├── output_cleaned_cattle_2/
├── data.yaml
├── README.dataset
├── README.roboflow
├── Aerial_Cattle_Tracking_Pipeline.ipynb
├── videos.mp4
├── metrics1.png
├── metrics2.png
├── metrics3.png
├── metrics4.png
├── metrics5.png
├── metrics6.png
└── README.md
