# DAMAGED-IMAGE-RESTORER-USING-COMPUTER-VISION

I have employed the OpenCV's inpaint function, a classical computer vision technique, to restore old damaged images. After loading the damaged image and a marked image highlighting the damages, I utilized thresholding to simplify the analysis process. Next, I increased the pixels of the marked image using dilation before using the inpaint function of OpenCV to restore the image.


## Run Using Google Colab

Firstly Open Google Colab
1.  Please upload your damaged image to the designated directory.
2.  Subsequently, load the image with damaged marks and utilize the paint tool in your system to draw damages using the eraser tool on the original image.
3.  Execute the code provided in the .ipynb file to restore your image.

## Run Locally
1.   Employ Jupyter Notebook to restore the image, following the same steps mentioned earlier. Ensure to execute the command mentioned below in your command prompt, as it may not be included in the notebook.
```bash
  pip install opencv-python
```


### Thank You
