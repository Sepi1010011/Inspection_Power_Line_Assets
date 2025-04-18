# 🔌 Power Line Asset Inspector

**AI-powered defect detection for power line maintenance** using YOLO object detection to identify faulty components (like insulators) from drone imagery.

## 🖼️ Sample Detection
![Demo](assets/detection_example.jpg)

## ✨ Key Features
- Detects **defective components** (insulators, connectors, etc.)
- Classifies assets as `normal` or `defect`
- Processes both images and video streams

## 📦 Dataset
- **InsPlad dataset** (primary source)
- Augmented with public power line imagery
- 2-state annotation for each classes: `normal` vs `defect` like `glass_insulator` and `defect_glass_insulator`

```python
Classes:
0: glass_insulator
1: defect_glass_insulator
2: yoke_suspension
3: defect_yoke_suspension
4: vari_grip
5: defect_vari_grip
# more classes...
```
## Deployment Option:
- Using this project in Drone to inspection the tower in real time
- helping to engineer to prevent any losses
