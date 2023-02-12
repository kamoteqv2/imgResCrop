# imgResCrop
 Resize and crop images in the current directory to a specific dimension.
 
****How to use:****

1. Save the file for example "resize_and_crop_images.py".
2. Open your terminal or command prompt and navigate to the directory where the exe file is located.
3. To run the program, type the following command:

   ```python resize_and_crop_images.py <new_width> <new_height> [--fillcolor <color>]```

where <new_width> and <new_height> are the desired width and height for the resized and cropped images, respectively.

The optional argument --fillcolor can be used to specify the color of the padding. If --fillcolor white is specified, the padding will be white. 

If --fillcolor black is specified, the padding will be black. If this argument is not specified, the default value will be white.


****Example:****

```python resize_and_crop_images.py 100 100 --fillcolor black```
This command will resize and crop all the images in the current directory to 100x100 pixels, with black padding.
