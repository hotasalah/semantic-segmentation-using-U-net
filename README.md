# Implementing semantic segmentation using U-Net
This taske leverages the U-Net architecture to predict the class that corresponds to all the pixels in the image.
<br>The objective is beyond just drawing a bounding box around the object, as like in traditional object detection, but also identifying the exact pixels that contain an object

<br>There are two main aspects should be kept in mind when performing image segmentation using U-Net:
- The shape and structure of the objects in the original image remain the same in the segmented output.
- Leveraging a fully convolutional architecture (and not a structure where we flatten a certain layer) can help here since we are using one image input and another as output.
