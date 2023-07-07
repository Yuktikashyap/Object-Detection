# Object Detection Model using OpenCV and YOLO

This repository contains code for an object detection model using OpenCV and YOLO (You Only Look Once). The model can detect various objects in an image and draw bounding boxes around them, along with labeling the objects.

## 🔗 Colab Link:
- https://colab.research.google.com/drive/1YmCbd1bv_WemSk0-uZyKEu5RzsYy9BsD?usp=sharing

## 📁 File Structure
- `Object_Detection_ComputerVision.ipynb`: Jupyter Notebook containing the code for the object detection model.

## 🚀 Usage
1. Clone the repository:
   ```
   git clone https://github.com/your-username/object-detection-model.git
   ```
2. Open the `Object_Detection_ComputerVision.ipynb` notebook using Jupyter Notebook or any compatible environment.
3. Make sure you have the necessary dependencies installed, such as OpenCV and matplotlib.
4. Run the notebook cells to execute the code step by step.
5. You can provide your own input images by replacing the file paths in the code or use the provided example images.
6. The model will detect objects in the images and display the results, including bounding boxes and labels.

## ⚙️ Dependencies
The following dependencies are required to run the code:
- OpenCV
- Matplotlib

Install the dependencies using `pip`:
```
pip install opencv-python matplotlib
```

## 📚 Explanation
The code uses the YOLO object detection model to detect objects in images. It loads the pre-trained YOLO weights and configuration files and sets up the necessary parameters. The images are then processed through the YOLO model to obtain the class IDs, confidence scores, and bounding box coordinates of the detected objects.

The code then draws bounding boxes around the detected objects and labels them using the class names. It utilizes OpenCV functions to perform these operations. The resulting images with bounding boxes and labels are displayed using matplotlib.

You can modify the code as per your requirements, such as changing the confidence threshold, using different pre-trained weights and configurations, or applying the object detection on videos.

Feel free to experiment and explore the capabilities of the object detection model!

## 🤝 Contributing
Contributions to the object detection model are welcome! If you have any ideas for improvements, new features, or bug fixes, please open an issue or submit a pull request.

## 📃 License
This project is licensed under the [MIT License](LICENSE).

Please note that the original code for the object detection model was generated in a Colaboratory notebook. Make sure to attribute the original author if you reuse or modify the code.

Happy object detection! 🚀👁️
