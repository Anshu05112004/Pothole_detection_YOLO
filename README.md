# Pothole Detection using YOLOv8 and OpenCV
[image]()
## Overview
This project aims to detect and segment potholes using machine learning techniques. The implementation leverages YOLOv8 for object detection and the OpenCV and CVZone libraries for image processing. The dataset used was sourced from [roboflow.com](https://roboflow.com) and includes a total of 780 images annotated in the YOLOv8 format.

## Dataset
The dataset consists of 780 images with pothole annotations. The images have undergone pre-processing and augmentation to enhance the robustness of the model. 

## Models
Three different models were trained, with the YOLOv8 nano model providing the most optimized results. Due to the absence of a GPU, the processing time was slower than desired, but performance can be significantly improved by using a GPU.

## Libraries and Tools
- **YOLOv8:** For object detection and segmentation.
- **OpenCV:** For image processing tasks.
- **CVZone:** An additional library for facilitating OpenCV operations.
- **Python:** The programming language used for implementation.

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pothole-detection.git
2. Change to the project directory
    ```bash
   cd pothole-detection
3. Install the required dependencies

## Results
The YOLOv8 nano model provided the best results in terms of accuracy and performance. However, due to the lack of a GPU, the processing time was slower. Using a GPU or other optimization techniques can enhance performance.

## Contributing
If you would like to contribute to this project, please create a pull request.

## License
This project is licensed under the MIT License.

## Authors
 * [Anshu05112004](https://github.com/Anshu05112004/) 
 * [Grishm](https://github.com/2228115grishm/)

_Feel free to modify any sections according to your specific requirements and to include additional details if necessary._

