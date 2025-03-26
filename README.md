# Somesh-s-Work
Dataset Overview

- **Purpose**: Object detection for balls in various sports settings
- **Size**: 20 images
- **Source**: [Roboflow Universe - OP3 Dataset](https://universe.roboflow.com/your-project-link-here)


## Steps for Dataset Creation

1. **Project Creation**
    - Created a new project named "Ball Detection"
    - Selected "Object Detection" as the project type
    - Chose "Bounding Box" as the annotation format
2. **Image Selection and Import**
    - Navigated to the [OP3 Dataset](https://universe.roboflow.com/your-project-link-here) on Roboflow Universe
    - Manually selected 20 diverse images containing balls
    - Used the "Clone" or "Add to Workspace" feature to import selected images
3. **Dataset Verification**
    - Ensured exactly 20 images were imported into the project
    - Reviewed existing annotations for accuracy
4. **Annotation Refinement**
    - Used Roboflow's annotation tools to adjust or add bounding boxes where necessary
    - Ensured all balls were correctly labeled as "ball"
5. **Preprocessing Configuration**
    - Applied "Auto-Orient" to standardize image orientation
    - Resized images to 640x640 pixels while maintaining aspect ratio
    - Implemented "2x2 Tile Split" to enhance small object detection
6. **Dataset Versioning**
    - Generated Version 1 of the dataset
    - Split data:
        - 16 images (80%) for training
        - 2 images (10%) for validation
        - 2 images (10%) for testing
7. **Export Configuration**
    - Selected YOLOv8 PyTorch TXT as the export format
    - Generated and saved the dataset export code for future use

## Next Steps

- Train a YOLOv8 model using this dataset
- Evaluate model performance and iterate on the dataset as needed
