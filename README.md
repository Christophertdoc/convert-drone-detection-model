# Convert YOLOv11 Drone Detection Model into Mobile-Optimized TFLite Format

This notebook shows how to take an existing YOLOv11 model and convert it into a format that is better suited for running on mobile devices. 
To demonstrate this, the notebook does the following:

1. Load, run inference, and visualize detection results with the original YOLOv11 model.
2. Export the model to a mobile-optimized TFLite format.
3. Load the new TFLite model, perform inference on the image, and visualize the detection results to ensure that it aligns with the original model.

## Credits
Doğu İlmak for creation of the initial model. 
  - Model https://huggingface.co/doguilmak/Drone-Detection-YOLOv11x/blob/main/weight/best.pt
  - Model training & Notebook: https://github.com/doguilmak/Drone-Detection-YOLOv11x/tree/main
