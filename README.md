Image Processing GUI
This module provides a GUI for performing various image processing actions using tkinter and cv2.

Attributes
img (numpy.ndarray): The current image being processed.
Methods
select_image(): Opens a file selection dialog and loads the selected image.
k(): Converts the current image to RGB.
convert_to_gray(): Converts the current image to grayscale.
flip_vertical(): Flips the current image vertically.
flip_horizontal(): Flips the current image horizontally.
crop_image(x, y, w, h): Crops the current image using the specified coordinates (x, y) and dimensions (w, h).
plot_histogram(): Plots a histogram for the current image.
adjust_brightness_contrast(brightness, contrast): Adjusts the brightness and contrast of the current image.
apply_adabtive_threshold(block_size, constant): Applies adaptive thresholding and histogram equalization to the current image.
apply_scaling_translation_rotation(scale_x, scale_y, translation_x, translation_y, rotation_angle): Applies scaling, translation, and rotation to the current image.
smooth_image(kernel_size): Smooths the current image using a low pass filter with the specified kernel size.
apply_gaussian_filter(kernel_size): Applies a Gaussian filter to the current image.
apply_averaging_filter(kernel_size): Applies an averaging filter to the current image.
apply_sobel_edge_detector(): Applies a Sobel edge detector to the current image.
apply_median_filtering(kernel_size): Applies median filtering to the current image.
apply_erosion(kernel_size): Applies erosion to the current image.
apply_dilation(kernel_size): Applies dilation to the current image.
