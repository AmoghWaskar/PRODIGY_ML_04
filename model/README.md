# Model Files

This folder is intended to store the trained model file for the Hand Gesture Recognition project.

## Why the Model File is Not Uploaded

The trained model file (`gesture_model.h5`) exceeds GitHub's file size limit (100MB).  
Due to this limitation, the model file is not included in this repository.

---

## How to Generate the Model

To recreate the model locally:

1. Clone this repository
2. Install required dependencies:
3. Open `model_training.ipynb`
4. Run all cells to train the model
5. Save the model using:

```python
model.save("gesture_model.h5")

