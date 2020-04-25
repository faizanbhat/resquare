# Resquare
Simply utility for expanding the frame size of a logo image while preserving the background color of the original image. Detects the background color of the image and draws new background pixels around the original file.

## Prerequisites
Pillow 

## Installation
```
pip install resquare
```

## Usage
```
import resquare
resquare.Resquare(in_file="/Users/abc/logo_file.jpg", out_file="/Users/abc/logo_file_400x400.jpg", target_dimension=400)
```

## Improvements
Background detection currently assumes that the color of the upper left pixel is the background color. While this approach works well for real world use cases, it could be improved upon through a deeper analysis of the image.