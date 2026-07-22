# Processing Notes — CNN-Based Hybrid Prediction for RDH (Zhao 2025)

- **Paper:** Yi Zhao, Yi Peng, Yixiang Fang, Tianzhu Zhang, Junxiang Wang, Circuits, Systems, and Signal Processing, 2025
- **Reproduction tier:** A
- **Status:** Completed (full reproduction)

## What was reproduced
Hybrid-prediction (stand-in) rhombus PEE core, levels 1..3, 8 images, bit-exact reversibility.

## Reproduced vs reported
The hybrid-PEE mechanism and reversibility are reproduced. The **CNN predictor is NOT trained** (no weights/data) and is approximated by a fixed predictor -> reproduced capacity is a conservative lower bound. Stated openly.

## Honesty note
No fabricated results; all numbers from included code; 'reported' cells reflect the paper.
