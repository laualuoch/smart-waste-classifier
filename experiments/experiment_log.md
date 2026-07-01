Experiment Log

Experiment ID: CNN-001

Date:

Model:
Custom CNN Baseline

Architecture:
Conv2D(32) → MaxPool
Conv2D(64) → MaxPool
Conv2D(128) → MaxPool
Flatten
Dense(128)
Dense(10)

Hyperparameters:
Image Size: 128x128
Batch Size: 32
Epochs: 10
Optimizer: Adam
Loss Function: Sparse Categorical Crossentropy

Results:
Training Accuracy:
Validation Accuracy:
Training Loss:
Validation Loss:

Files Generated:
cnn_baseline_accuracy.png
cnn_baseline_loss.png
cnn_baseline.keras

Observations:
Initial baseline model completed successfully.
