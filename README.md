# Dental Cavity Detection Using YOLOv5 and Detectron2

## Project Overview
Dental caries, commonly referred to as cavities, are a pervasive oral health condition affecting individuals of all age groups. This project explores the use of Artificial Intelligence (AI) for automating the detection of dental caries from bitewing radiographs, addressing limitations of manual diagnosis such as time consumption and inter-observer variability.

Our research evaluates two state-of-the-art object detection models:
- **YOLOv5**
- **Detectron2**

The study includes transfer learning techniques and establishes benchmarks for automated dental diagnostics while highlighting the challenges that need to be addressed for clinical application.

---

## Dataset
We developed the **Wits Dental Dataset**, which comprises **487 bitewing dental radiographs**. This dataset was ethically approved and curated to facilitate robust research in AI-driven dental diagnostics. Key challenges included:
- Class imbalance
- Limited representation of pathological conditions

---

## Models and Methodology
### **YOLOv5**
- Achieved an **mAP50 of 0.933** in complex-to-simple transfer learning.
- Demonstrated a **66.7% recall** for detecting caries.
- Strengths: High precision and adaptability through transfer learning.

### **Detectron2**
- Showed robust performance in identifying larger dental features.
- Struggled with smaller pathological details.
- Strengths: Effective for detecting generalized features.

### Transfer Learning
The research employed a **novel complex-to-simple knowledge transfer** approach to enhance detection capabilities.

---

## Key Findings
- **Performance**: Both YOLOv5 and Detectron2 showed promise in detecting caries, but their current capabilities fall short of clinical-grade reliability.
- **Challenges**:
  - Dataset limitations, including class imbalance.
  - Difficulty in identifying smaller pathological features.

---

## Contribution
This research:
- Establishes benchmarks for AI-based dental caries detection.
- Highlights the gap between current AI performance and clinical requirements.
- Provides insights into dataset preparation and the applicability of object detection models for healthcare.

---

## Future Work
- Address class imbalance through data augmentation or improved dataset collection.
- Improve model performance on smaller pathological conditions.
- Explore alternative AI architectures to bridge the gap toward clinical deployment.

---

## Repository Contents
- `data/`: Contains sample images and dataset description.
- `models/`: Includes YOLOv5 and Detectron2 training scripts.
- `results/`: Contains evaluation metrics and visual outputs.
- `README.md`: Project documentation.

---

## Citation
If you use this work, please cite appropriately: