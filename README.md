# Car-License-Plate-Extraction

## **Goal**
Extract a Car License Plate from an image frame

## **Approach**
- Train Yolov5 on a custom car license plate dataset on object detection task.
- Using trained model to extract only the license plate.
- Preprocess the plate image to reduce noise.
- Read plate number using EasyOCR.

## **Result**
<div align="center">
<img src="https://raw.githubusercontent.com/elfphabet621/Car-License-Plate-Extraction/main/labeled_img_0.jpg">
</div>

## **Custom Data Directories**
<img src="https://raw.githubusercontent.com/elfphabet621/Car-License-Plate-Extraction/main/dir_structure.PNG">

**To do**
- [ ] Train on larger dataset
- [ ] Use Tesseract OCR for better result
- [ ] Extract from a video instead of a still image
