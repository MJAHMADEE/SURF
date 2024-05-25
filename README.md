# SURF Feature Matching and Image Stitching with OpenCV 🖼️🔍

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.5.1-green.svg)](https://opencv.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1j1LKky_TTLX3UXZ6HJVLllwyMZOQdGNZ?usp=sharing)

Welcome to the SURF Feature Matching and Image Stitching repository! This project demonstrates the use of OpenCV's SURF (Speeded-Up Robust Features) algorithm to detect keypoints, match features, and stitch images together. 🌟

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Example Output](#example-output)
- [Contributing](#contributing)
- [License](#license)

## Installation 📥

To get started, you'll need to install the necessary packages and clone the required repositories.

1. Install necessary packages:
   - `cmake`
   - `libopencv-dev`

2. Clone the OpenCV repository and its extra modules from GitHub.

3. Create a build directory and configure OpenCV with CMake, enabling non-free modules.

4. Build and install OpenCV.

## Usage 🚀

Here's a step-by-step guide to use the provided script:

1. **Import necessary libraries**: Ensure you have the following libraries imported:
   - `cv2`
   - `matplotlib.pyplot`
   - `numpy`
   - `os`

2. **Load and process images**: Write a function to check if the image is loaded correctly, and then load and process the images for keypoint detection.

3. **Detect keypoints using SURF and match features**: Use the SURF algorithm to detect keypoints and compute descriptors for the images.

4. **Draw keypoints and match them**: Utilize the Brute Force Matcher to find the best matches between the images and apply ratio tests to filter good matches.

5. **Warp images and display the stitched image**: Define a function to warp the images based on homography and display the final stitched image.

## Example Output 📸

### Key Point Detectors 1
![Key Point Detectors1](https://raw.githubusercontent.com/MJAHMADEE/SURF/main/Results/Key%20Point%20Detectors1.png)

### Key Point Detectors 2
![Key Point Detectors2](https://raw.githubusercontent.com/MJAHMADEE/SURF/main/Results/Key%20Point%20Detectors2.png)

### Matching Features with All the Detectors
![Matching Features with all the Detectors](https://raw.githubusercontent.com/MJAHMADEE/SURF/main/Results/Matching%20Features%20with%20all%20the%20Detectors.png)

### Matching the Features
![Matching the Features](https://raw.githubusercontent.com/MJAHMADEE/SURF/main/Results/Matching%20the%20Features.png)

### Naive Warping
![Naive Warping](https://raw.githubusercontent.com/MJAHMADEE/SURF/main/Results/naive%20warping.png)

### Better Warping
![Better Warping](https://raw.githubusercontent.com/MJAHMADEE/SURF/main/Results/better%20warping.png)

## Contributing 🤝

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

🌟 **Happy Coding!** 🌟
