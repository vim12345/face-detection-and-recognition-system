# face-detection-and-recognition-system

Here's a step-by-step implementation guide to build a face detection and recognition system using:

* YOLOv8 for face detection (via Ultralytics)

* FaceNet for face recognition

* Embedding handling for faces with mask and cap

* Targeting 98%+ accuracy on your custom dataset (assumes properly labeled, high-quality data)

# ✅ Tips to Achieve 98%+ Accuracy
* Train your own YOLOv8 on face + mask + cap using Roboflow or LabelImg.

* Fine-tune FaceNet on your dataset (using triplet loss if needed).

* Normalize lighting conditions and use data augmentation.

* Maintain at least 5-10 images per person with various occlusions (mask, cap, angles).

