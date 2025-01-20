# Cartoon_Effect_using_openCV
Cartoon Effect with OpenCV 🖼️🎨

A Python project that applies a cartoon effect to images using OpenCV.

Features ✨

Converts any image into a cartoon-style representation. 🎭

Smoothens the image while preserving edges using a bilateral filter.

Detects edges using adaptive thresholding for a sketch-like effect.

How It Works ⚙️

Image Loading: Reads an input image using OpenCV.

Noise Reduction: Applies a bilateral filter to smooth the image while retaining edges.

Edge Detection: Converts the image to grayscale and detects edges with adaptive thresholding.

Cartoon Effect: Combines the edge mask with the smoothed image.

Prerequisites 🛠️

Python 3.7+

Required libraries:

OpenCV

Matplotlib

NumPy

Install dependencies:

pip install opencv-python matplotlib numpy

Usage 🚀

Clone the repository:

git clone https://github.com/yourusername/cartoon-effect-opencv.git

Navigate to the project directory:

cd cartoon-effect-opencv

Run the script:

python cartoon.py

Replace img.jpg with your desired image file.

Example Output 🖼️

Original Image:


Cartoonified Image:


Contributing 🤝

Feel free to contribute by submitting issues or pull requests. Let's make this project even better! 💡

License 📜

This project is licensed under the MIT License. See the LICENSE file for details.


