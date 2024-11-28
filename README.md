# **introducation**
To enhance the clarity of the chest X-ray images, I implemented image enhancement
techniques in both the spatial and frequency domains

# **Spatial Domain Enhancement**
I applied two techniques:

1. **Histogram Equalization:** improves the contrast of an image by
redistributing the intensity values, enhancing the visibility of details in
darker areas of the X-rays.

2. **Gaussian Blur:** smooths the image by applying a Gaussian filter, reducing
noise while preserving the overall structure of the image.
# **Frequency Domain Enhancement**
I applied two filtering techniques:

1. **Low-Pass Filtering (Blurring):** smooth the image by attenuating the
high-frequency components, effectively reducing noise.

2. **High-Pass Filtering (Sharpening):** the edges and fine details of the image
by emphasizing high-frequency components.

# **Results and Discussion**

1. **Spatial Domain Results**
The spatial domain techniques produced notable improvements in image clarity.
• Histogram Equalization: improved contrast in the chest X-rays, particularly
in darker areas where details were initially harder to distinguish.
• Image Smoothing: reduce the noise, also slightly blurred fine details, which
is typical when applying smoothing techniques.
Example Visualization:
![output](https://github.com/user-attachments/assets/2ea89b0e-b11e-435d-9c83-b663b9e113a5)


2. **Frequency Domain Results**
The frequency domain enhancements also led to distinct changes in image quality.
• Low-Pass Filtering: effectively smoothed the image, reducing noise, but also
caused some loss of fine detail.
• High-Pass Filtering: emphasized the edges and fine details, sharpening the
image, but at the cost of amplifying noise in certain areas.

Example Visualization:
![output2](https://github.com/user-attachments/assets/57ecbd90-425e-4e78-907d-c80382ae71f7)



# **Analysis and Conclusion**

From the applied techniques, I found that:
• Histogram Equalization was highly effective for enhancing contrast in the
chest X-ray images, making it easier to detect subtle features in darker regions.
• Image Smoothing was useful for reducing noise but had the drawback of
slightly blurring the image.
• Low-Pass Filtering offered similar results to Gaussian blur in reducing noise
but with some loss of detail.
• High-Pass Filtering, while enhancing the edges and making details more
pronounced, also increased noise, which may not be desirable in medical
imaging.

# **Conclusion**
In conclusion, histogram equalization proved to be the most effective technique for
chest X-rays in this dataset. It improved the contrast and visibility of important
features without significantly degrading the quality of the image, which is crucial for
medical diagnostics. The combination of spatial and frequency domain techniques
offers a robust approach to enhancing different aspects of an image, though care must
be taken to balance noise reduction and detail preservation.
