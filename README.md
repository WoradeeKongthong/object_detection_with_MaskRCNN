# Object Detection with MaskRCNN on Google Colab

## How to make the object detection on an image
**object_detection_on_image_TF1.ipynb**  
- Clone the model repository from https://github.com/matterport/Mask_RCNN which works on tensorflow 1.  
- Build the model and apply trained weights.   
- Make object detection on the given image.  
- And plot the image along with mask, bounding boxes, class id and confidence level.  
---
**object_detection_on_image_TF2.ipynb**
- Clone the model repository from https://github.com/ahmedfgad/Mask-RCNN-TF2 which works on tensorflow 2.  
- Install packages mentioned in requirements.txt.  
- Build the model and apply trained weights.  
- Make object detection on the given image.  
- And plot the image along with mask, bounding boxes, class id and confidence level.  
---
**object_detection_on_video_TF2.ipynb**
- The process of building the model is as same as the previous notebook that detect object on image.  
- Need some helper functions to create output frame (frame with detection info.)  
- Make object detection on a video.  
- Save the result video into local computer.
