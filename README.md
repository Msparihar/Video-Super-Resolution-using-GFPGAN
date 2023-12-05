# Video Upscaling with GFPGAN

This project utilizes the GFPGAN model to upscale videos, enhancing their visual quality. The process involves providing a video input, upscaling the video frame by frame using GFPGAN, and allowing users to download the enhanced videos.

## Task

The primary goal of this assignment is to showcase your proficiency in developing an
advanced AI model capable of enhancing the quality of a video by upscaling its
resolution and reducing noise. Your task entails harnessing the capabilities of any
suitable and available model to achieve significant improvements in video quality,
particularly by increasing its resolution and eliminating unwanted noise.

## Steps to Use the Colab Notebook

1. **Upload Video:**

   - Open the provided Colab notebook in your Google Colab environment.
   - Run the notebook cell that handles video uploads.

2. **GFPGAN Video Upscaling:**

   - Run the cell that uses GFPGAN to upscale the video frames.
   - The script extracts frames from the uploaded video, upscales each frame using GFPGAN, and saves the enhanced frames.

3. **Download Enhanced Video:**

   - After GFPGAN processing is complete, the enhanced video frames are available in the specified output directory.
   - Download the upscaled video directly from the Colab environment.

4. **Compare Sample Images:**
   - The `comparison` folder contains two sample images: one before GFPGAN upscaling and the other after.
   - View and compare these images to observe the enhancement achieved by GFPGAN.

### Comparision of enhenced videos:

1. ![image](comparision\sample_output_1.png)

2. ![image](comparision\sample_output_2.png)
