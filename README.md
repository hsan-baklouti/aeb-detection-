# aeb-detection-
# Pedestrian and Cyclist Detection for AEB

Computer Vision & Deep Learning project (ENISo, ASE).

## Plan
- KITTI (main) + BDD100K subset (night/rain robustness test)
- YOLO (Ultralytics) detector, recall-oriented threshold

## Progress
- [x] Dataset preparation: KITTI-YOLO, pedestrian/cyclist only
- [x] Block-based train/val/test split (seed 42)
- [x] Annotation check
- [ ] Preprocessing (CLAHE) and augmentation
- [ ] Baseline YOLO
- [ ] Training, evaluation, failure analysis

## Run
Notebook `dataset preparation.ipynb` (Kaggle, dataset: xavierlermusieaux/kitti-yolo).
