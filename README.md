# Object Detection and Evaluation

This repository contains code for performing object detection using the YOLO (You Only Look Once) model and evaluating predictions against ground truth annotations.

## Tasks Completed:

1. **Dataset Loading:**
   - The Supervisely library is used to load the dataset.
   - Ground truth annotations are obtained for each image.

2. **Visualization:**
   - Ground truth annotations are visualized using Supervisely's plotting functions.

3. **YOLO Model Prediction:**
   - The YOLO model is utilized to make predictions on the dataset.
   - Post-processing filters predictions for specific classes and confidence levels.

4. **Result Visualization:**
   - Annotated images with YOLO predictions are created and visualized.

5. **Comparison with Ground Truth:**
   - Predictions are compared with ground truth annotations to identify false positives and false negatives.

6. **Results Saving:**
   - Annotated images with YOLO predictions are saved to the "predict" folder.
   - False positives and false negatives are saved to respective folders.

## Instructions:

1. Open the provided Colab notebook.
2. Run each cell in the notebook sequentially to execute the code.
3. After running the notebook:
   - Navigate to the "Files" tab on the left sidebar in Colab.
   - Locate the "output" folder.
   - Right-click on the "output" folder and select "Download" to get it as a zip file.

## Important Notes:

- Ensure all required dependencies are installed as per the notebook instructions.
- Adjust file paths, model paths, and parameters based on your dataset and model.

Feel free to reach out if you have any questions or encounter issues.

Happy coding!

