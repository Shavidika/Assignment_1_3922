# Image Processing Assignment

This project demonstrates basic image processing operations using Python and OpenCV. The operations are implemented in a Jupyter notebook and include:

## Features

1. **Reduce Number of Intensity Levels**

   - Reduces the number of intensity levels in a grayscale image from 256 to a user-specified value (must be a power of 2).
   - **Example Output:**
     - ![Intensity Levels 2](outputs/intensity_levels_2.png)
     - ![Intensity Levels 4](outputs/intensity_levels_4.png)
     - ![Intensity Levels 8](outputs/intensity_levels_8.png)
     - ...

2. **Spatial Averaging (Mean Filtering)**

   - Applies a mean filter with kernel sizes 3x3, 10x10, and 20x20 to the image.
   - **Example Output:**
     - ![3x3 Mean Filter](outputs/mean_filter_3x3.png)
     - ![10x10 Mean Filter](outputs/mean_filter_10x10.png)
     - ![20x20 Mean Filter](outputs/mean_filter_20x20.png)

3. **Image Rotation**

   - Rotates the image by 45 and 90 degrees.
   - **Example Output:**
     - ![Rotated 45](outputs/rotated_45.png)
     - ![Rotated 90](outputs/rotated_90.png)

4. **Block-wise Averaging (Spatial Resolution Reduction)**
   - For each non-overlapping block of size 3x3, 5x5, and 7x7, replaces all pixels in the block with their average value.
   - **Example Output:**
     - ![Blockwise 3x3](outputs/blockwise_3x3.png)
     - ![Blockwise 5x5](outputs/blockwise_5x5.png)
     - ![Blockwise 7x7](outputs/blockwise_7x7.png)

## How to Use

1. Open the notebook `image_processing_assignment.ipynb` in Jupyter or VS Code.
2. Update the `image_path` variable in the notebook to point to your image file (e.g., `Cat.jpg`).
3. Run each cell in order to see the results of each operation. The notebook will save output images in an `outputs` folder for easy reference.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib

You can install the required packages using:

```
pip install opencv-python numpy matplotlib
```

## Notes

- The notebook assumes the input image is grayscale. If you use a color image, it will be converted to grayscale.
- Make sure your image file is in the same directory as the notebook or provide the correct path.
- Output images will be saved in an `outputs` directory for documentation and review.

## License

This project is for educational purposes.
