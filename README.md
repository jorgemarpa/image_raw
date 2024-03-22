# Image Tools

This repo has a few implementations of image alignment, pattern recognition algorithms, and example of how to work with RAW images
It uses OpenCV and Scikit-Image packages to open and analyze images as matrices.
It uses `rawpy` to open RAW images and work as matrices.
It uses ffmpeg-python to make time-lapse videso from a set of images.


* **Houghs Transform** finds edges in the image via gradient computation to then fit circles or lines. Is good to find lines and cirles in a image. I used to find the Sun disk in eclipse images and cut square stamps to center the sun and make a time-lapse. See [tutorial](https://scikit-image.org/docs/stable/auto_examples/edges/plot_circular_elliptical_hough_transform.html#sphx-glr-auto-examples-edges-plot-circular-elliptical-hough-transform-py).
* **Feature Alignment** first find features in the image to then find the transformation metween then with RANSAC algorthm.
* **Enhanced Correlation Coeafficeint Maximization** finds the transofrmation by maximizing the correlation coeafficient between the images.
* **Rotation Alignment** fing the best agle that minimizes resiuals in an image and applies the transformation.
* **FFT phase correlation** finds the best tranlation in the FFT space.

