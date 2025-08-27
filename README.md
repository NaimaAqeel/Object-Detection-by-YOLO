##  Demo Video  

[![Watch the demo on LinkedIn](https://img.shields.io/badge/▶%20Watch%20on%20LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/feed/update/urn:li:ugcPost:7177718745560170496/)


---

# YOLOv8 Object Detection & Segmentation 

This project demonstrates the use of **Ultralytics YOLOv8** for running **object detection and image segmentation** on both images and videos.

---

##  What This Project Covers

1. **Installing YOLOv8**

   * The project begins by installing the YOLOv8 library and checking PyTorch installation with GPU availability.
   * This ensures that the environment is ready for running detection and segmentation.

2. **Loading Pretrained Models**

   * The small version of YOLOv8 (`yolov8s.pt`) is used for object detection.
   * For segmentation tasks, the segmentation model (`yolov8s-seg.pt`) is used.

3. **Object Detection on Images**

   * The model is applied to images stored in Google Drive.
   * Detection results are saved automatically in the project folder.

4. **Adjusting Confidence Threshold**

   * The detection threshold can be adjusted (e.g., setting confidence to 0.8).
   * This helps filter out low-confidence predictions.

5. **Saving Cropped Objects**

   * Detected objects can be automatically cropped and saved as separate images.
   * This is useful for isolating detected items for further processing.

6. **Hiding Labels and Confidence**

   * The results can be displayed without labels or confidence values.
   * This makes the output cleaner when only bounding boxes are needed.

7. **Object Detection on Videos**

   * YOLOv8 can also be run on videos.
   * The model detects objects frame by frame and produces an annotated video.

8. **Image Segmentation**

   * The segmentation model is used to generate masks for detected objects.
   * This highlights object boundaries rather than just bounding boxes.

---

##  Learning Dependencies and Libraries

* **Python 3.8+** → Core programming language.
* **Ultralytics YOLOv8** → Main library for object detection and segmentation.
* **PyTorch** → Deep learning framework used by YOLOv8 for training and inference.
* **CUDA (optional)** → For GPU acceleration (faster predictions).
* **IPython / Jupyter** → To run commands and display outputs interactively.
* **Google Drive Integration** → Used for storing and accessing input images/videos.

---

##  Output

* **Detection results** → saved in `runs/detect/predict`
* **Segmentation results** → saved in `runs/segment/predict`
* **Cropped objects** → saved in `runs/detect/predict/crops`


---

 This project provides a complete demonstration of running **YOLOv8 detection and segmentation** on real-world images and videos. The accompanying video shows the actual workflow in action.

---


