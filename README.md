# YOLOv5_Object_Detection and Lane line Detection

YOLOv5 Object Detection using for self driving cars.

Description:
Developed a high-performance object detection system using YOLOv5 trained on the BDDK (Berkeley DeepDrive Kitti-Style) dataset. The project focused on improving detection of small and challenging road objects by combining robust augmentation, anchor tuning, and advanced training techniques.

Key Contributions:

Trained a custom YOLOv5 model on the BDDK dataset with optimized hyperparameters, anchor auto-learning, and multi-class detection.

Improved detection performance on extremely small objects using augmentation tuning, resolution scaling, and anchor re-calibration.

Performed training with AdamW, multi-scale experimentation, and early stopping using patience scheduling.

Conducted detailed evaluation using Precision, Recall, mAP@0.5, mAP@0.5:0.95, and validation visualizations.

Addressed data imbalance and annotation inconsistencies through custom YAML configs and dataset cleaning.

Automated training/validation workflows on Google Colab with GPU acceleration and model checkpointing.

Tech Stack:
Python · PyTorch · YOLOv5 · Google Colab · CUDA · OpenCV · NumPy · Computer Vision · Deep Learning
