# Experiment Log

## MOB-001

Model:
MobileNetV2 Baseline

Configuration:
Frozen pretrained ImageNet layers

Epochs:
10

Results:
Train Accuracy: 84.15%
Validation Accuracy: 68.22%
Train Loss: 0.4832
Validation Loss: 1.0413
Training Time: 1024.81 seconds

Observation:
Transfer learning outperformed baseline CNN.


## MOB-002

Model:
MobileNetV2 + Data Augmentation

Configuration:
RandomFlip
RandomRotation(0.2)
RandomZoom(0.2)

Epochs:
10

Results:
Train Accuracy: 61.40%
Validation Accuracy: 59.40%
Train Loss: 1.1391
Validation Loss: 1.1824
Training Time: 1278.41 seconds

Observation:
Aggressive augmentation reduced performance.


## MOB-003

Model:
MobileNetV2 Fine-Tuning

Configuration:
Last 30 layers unfrozen
Learning Rate = 0.0001

Epochs:
10

Results:
Train Accuracy: 98.60%
Validation Accuracy: 73.64%
Train Loss: 0.0466
Validation Loss: 1.2951
Training Time: 1330.50 seconds

Observation:
Best model so far. Fine-tuning improved performance.