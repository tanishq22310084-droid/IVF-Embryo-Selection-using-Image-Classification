# IVF Embryo Quality CNN (Research Prototype)

## Overview

This repository contains a **convolutional neural network (CNN) model** trained to perform **binary embryo quality classification** (*Good quality vs Poor quality*) from microscope images.

The model is intended strictly for **research, educational, and demonstration purposes**.

⚠️ **This model is NOT clinically validated and must NOT be used for real medical decision-making.**

---

## Model Description

- **Task**: Binary image classification
- **Domain**: IVF embryo image assessment
- **Analysis Type**: Single-timepoint image analysis
- **Output**:
  - Predicted class: *Good* / *Poor* quality
  - Confidence score (probability)

The model was trained offline and is provided as a **frozen inference artifact**.

---

## Technical Details

- **Framework**: TensorFlow 2 / Keras
- **File Format**: `.h5`
- **Input Shape**: `224 × 224 × 3` (RGB image)
- **Model Type**: Convolutional Neural Network (CNN)
- **Inference Only**: Yes (weights frozen)

---

## Training Data

- Trained on **publicly available, de-identified IVF embryo image datasets**
- Sources include:
  - Open academic research repositories
  - Public Kaggle datasets
- **No proprietary or patient-identifiable data** was used

Dataset size was limited and intended for **prototype demonstration**, not clinical performance benchmarking.

---

## Intended Use

✅ Research demonstrations

✅ Educational purposes

✅ ML workflow illustration

✅ Prototype decision-support systems

❌ Clinical diagnosis

❌ IVF treatment decisions

❌ Medical deployment

❌ Commercial use

---

## Ethical & Safety Disclaimer

This model:

- Is **not clinically validated**
- Has **not undergone regulatory approval**
- Should **not influence real-world IVF decisions**
- Is provided to demonstrate **AI-assisted decision-support concepts only**

Final medical decisions must always remain with qualified embryologists and clinicians.

---

## License

This model is released under the **Creative Commons Attribution–NonCommercial 4.0 (CC BY-NC 4.0)** license.

- ✔ Free for research and educational use
- ❌ Not permitted for commercial or clinical deployment

---

## Associated Project

The full project—including:

- Training pipeline
- Model evaluation
- Streamlit-based prototype application
- Documentation and ethics statements

is available in the linked **GitHub repository**.

---

## Citation

If you reference or reuse this model in academic or educational work, please cite the associated project repository.

---

## Author

**Meenal Sinha**

AI & Machine Learning Enthusiast

Focus: Responsible AI, Medical Decision-Support Systems

---

## Version

**v1.0 – Research Prototype**

---

## Contact & Feedback

For questions, suggestions, or collaboration opportunities related to this research prototype, please open an issue in the GitHub repository or reach out via the contact information provided in the repository.

---

## Acknowledgments

This project was developed as an educational exploration of AI applications in medical imaging. Special thanks to the open-source community and publicly available datasets that made this research possible. Public datasets were used in accordance with their respective licenses.