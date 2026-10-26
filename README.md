# CCA 3: Computer Vision

## Project Overview

This project explores fundamental computer vision techniques through four practical tasks involving image restoration, image segmentation, feature extraction, object recognition, and video motion estimation.

The experiments are implemented in Python using Jupyter Notebook and computer vision libraries.

## Objectives

- Understand image noise and image restoration techniques.
- Apply image segmentation methods to identify regions and boundaries.
- Extract and compare image features using HOG and SIFT.
- Detect faces and objects using Viola–Jones and YOLO.
- Analyze video motion using frame differencing, background subtraction, and optical flow.

## Technologies Used

- **Python:** Programming language used to implement the experiments.
- **OpenCV:** Image processing, face detection, video analysis, and optical flow.
- **NumPy:** Numerical operations and array manipulation.
- **Matplotlib:** Visualization of images and experimental results.
- **scikit-image:** HOG feature extraction and image quality evaluation, where applicable.
- **Ultralytics YOLO:** Object detection.
- **PyTorch:** Deep learning framework used by the YOLO implementation.
- **Jupyter Notebook:** Environment for writing and executing the experiments.

## Task 1: Image Restoration and Segmentation

### Techniques
- Gaussian noise and salt-and-pepper noise.
- Gaussian and median filtering.
- PSNR and SSIM for image quality evaluation.
- Binary thresholding and Otsu thresholding.
- Morphological operations: erosion, dilation, opening, and closing.
- Canny edge detection.
- Watershed segmentation.

### Objective
To investigate how image noise can be reduced and how segmentation techniques can identify regions and boundaries in images.

## Task 2: Feature Extraction and Image Matching

### Techniques
- Histogram of Oriented Gradients (HOG).
- Scale-Invariant Feature Transform (SIFT).
- Brute-force feature matching.
- Lowe's ratio test.
- Image rotation and feature-matching comparison.

### Objective
To extract image features, match corresponding keypoints between images, and examine how rotation affects matching performance.

## Task 3: Object Recognition

### Techniques
- Viola–Jones face detection using a Haar Cascade classifier.
- Object detection using a pretrained YOLO model.
- Bounding-box visualization and confidence scores.
- Comparison of the two approaches.

### Objective
To investigate face and object detection using traditional computer vision and deep learning approaches.

## Task 4: Video Motion Estimation

### Techniques
- Video frame extraction.
- Frame differencing.
- Gaussian Mixture Model (GMM) background subtraction.
- Lucas–Kanade optical flow.
- Visual comparison of motion estimation methods.

### Objective
To identify changes and moving regions in video frames and estimate the movement of selected feature points.

## Project Structure

```text
CCA3_Computer_Vision/
├── dataset/
│   ├── original.jpg
│   ├── second.jpg
│   └── original_video.mp4
├── task3_images/
│   ├── face.jpg
│   ├── objects.jpg
│   └── multiple_faces.jpg
├── outputs/
├── Task1_Restoration_Segmentation.ipynb
├── Task2_Feature_Extraction_Matching.ipynb
├── Task3_Object_Recognition.ipynb
├── Task4_Video_Motion_Estimation.ipynb
└── README.md
```

## How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install the required libraries used by the notebooks.
3. Keep the dataset and image files in their expected folders.
4. Open the project folder in Jupyter Notebook.
5. Open each notebook and run its cells from top to bottom.
6. Review the displayed results and generated output images.

## Conclusion

This project demonstrates several important computer vision techniques across images and videos. It explores image restoration, segmentation, feature extraction, object detection, and motion estimation. The experiments provide practical experience with OpenCV, feature descriptors, deep learning-based detection, and video analysis.

## Note

The results depend on the input images, video, model, and parameter settings. Refer to the individual notebooks for implementation details and experimental outputs.