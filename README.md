# ImageprocessingSuite

A powerful image processing application that provides various image enhancement and transformation capabilities through a user-friendly Gradio interface.

## Features

### Image Enhancement
- Power Law Transformation (Gamma Correction)
- Histogram Equalization
- Linear Transform
- Log Transform

### Image Compression
- DFT (Discrete Fourier Transform) High-Frequency Cutting
- K-means Quantization

### Image Segmentation
- Threshold Segmentation
- Adaptive Thresholding
- Watershed Segmentation

### Interactive Interface
- Modern Gradio-based web interface
- Real-time image processing
- Side-by-side comparison of original and processed images
- Easy-to-use controls for parameter adjustment

## Installation

1. Clone this repository
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the application:
```bash
python main.py
```

The Gradio interface will open in your default web browser, providing:
- Image upload functionality
- Various transformation options
- Parameter adjustment sliders
- Real-time preview of results
- Download processed images

## Project Structure

- `main.py`: Main application file containing both the image processing functions and Gradio interface
- `requirements.txt`: Project dependencies

## Dependencies

The project uses the following main libraries:
- OpenCV (cv2)
- NumPy
- Matplotlib
- scikit-image
- Gradio
- Pillow (PIL)

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to submit issues and enhancement requests! 