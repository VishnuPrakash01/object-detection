# Object Detection with YOLO and OpenCV

## Project Overview

This repository contains a machine learning project for object detection using the YOLO (You Only Look Once) algorithm with Python and OpenCV. The YOLO algorithm is known for its real-time object detection capabilities, making it suitable for a variety of applications.

## Features

- **Real-time Object Detection:** The project leverages the YOLO algorithm to detect and identify multiple objects in real-time.
- **Python and OpenCV:** Written in Python, the project uses the OpenCV library to handle image processing and computer vision tasks.
- **Modular Structure:** The code is organized into modular components for better maintainability and scalability.

## Requirements

Ensure you have the following dependencies installed:

- Python 3.x
- OpenCV
- YOLO weights and configuration files (Download from the official YOLO website)

Install required Python packages using:

```bash
pip install -r requirements.txt
```

## Usage

1. Download the YOLO weights and configuration files and place them in the `yolo_cfg/` directory.
2. Run the object detection script:

```bash
python object_detection.py
```

3. Provide the input image or video stream when prompted.

## File Structure

- **`object_detection.py`**: Main script for object detection.
- **`yolo_cfg/`**: Directory for YOLO configuration files.
- **`images/`**: Directory for sample input images.
- **`videos/`**: Directory for sample input videos.

## Configuration

Adjust the configuration parameters in `object_detection.py` for your specific use case, such as changing the confidence threshold or selecting different YOLO versions.

```python
# Configuration Parameters
CONFIDENCE_THRESHOLD = 0.5
NMS_THRESHOLD = 0.4
YOLO_CFG_FILE = "yolov3.cfg"
YOLO_WEIGHTS_FILE = "yolov3.weights"
CLASSES_FILE = "coco.names"
```

## Acknowledgments

- YOLO: [https://pjreddie.com/darknet/yolo/](https://pjreddie.com/darknet/yolo/)
- OpenCV: [https://opencv.org/](https://opencv.org/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Contact

For any questions or inquiries, please contact [vishnu] at [vishnuprakashl0112@gmail.com].

"# object-detection" 
