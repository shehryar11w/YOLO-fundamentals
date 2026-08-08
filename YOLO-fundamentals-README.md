# YOLO Fundamentals

Core building blocks behind YOLO-style object detectors, implemented from scratch.

## Contents

| Notebook | Description |
|---|---|
| `iou-nms.ipynb` | Implements **Intersection over Union (IoU)**, YOLO's core localization metric/loss component, and **Non-Maximum Suppression (NMS)** for filtering overlapping bounding box predictions. Also covers converting between bounding box formats — YOLO's `(x_center, y_center, w, h)` vs. PyTorch's `(xmin, ymin, xmax, ymax)`. |

## Technologies

- Python
- PyTorch

## Getting Started

```bash
git clone https://github.com/shehryar11w/YOLO-fundamentals.git
cd YOLO-fundamentals
pip install torch
```

Open the notebook in Jupyter or VS Code and run.

## Learning Outcomes

- How IoU is computed and used as both a metric and a loss component
- How NMS removes duplicate/overlapping detections
- Converting between common bounding box coordinate formats

## License

Educational / personal use.
