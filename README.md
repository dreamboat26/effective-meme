# Quantum Machine Learning: The Superhero That Classical Machine Learning Never Knew It Needed

<div align="center">
  <img src="https://github.com/user-attachments/assets/c0cc388c-99ea-43ff-a77d-fa71d3344237" alt="snip3">
</div>

This repository contains the code, datasets, and supplementary materials associated with the paper **"Quantum Machine Learning: The Superhero That Classical Machine Learning Never Knew It Needed"** by **Mahule Roy**.

---

## Abstract

Quantum Machine Learning (QML) merges quantum mechanics with machine learning, enabling algorithms that surpass classical models in specific tasks by leveraging quantum properties such as superposition and entanglement. This paper provides a comprehensive overview of QML, its principles, and applications, focusing on supervised learning methods like Quantum Support Vector Machines (QSVM) and Quantum Convolutional Neural Networks (QCNN). Key applications include pneumonia detection using medical imaging and high-energy physics simulations for quantum chromodynamics. While QML shows transformative potential, challenges like quantum hardware limitations and algorithmic scalability remain critical.

---

## Repository Contents

### 1. **Paper**
- A PDF copy of the full research paper is available in the `docs/` folder.

### 2. **Code**
- Implementations of QML techniques, including:
  - **QSVM**: For classification tasks in high-energy physics simulations.
  - **QCNN**: For pneumonia detection using chest X-ray images.
  - Kernel and variational approaches for quantum-enhanced classification.

### 3. **Data**
- Links to datasets used:
  - [Pneumonia Detection Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) for medical imaging.
  - Synthetic datasets for quantum chromodynamics simulations.

### 4. **Results**
- Visualizations of metrics such as loss, accuracy, and scalability for QSVM, QCNN, and classical models.
- Figures and plots illustrating quantum circuit implementations and performance comparisons.

---

## Key Features

1. **Quantum Support Vector Machines (QSVM)**:
   - Leverages quantum kernels for high-dimensional feature space representation.
   - Demonstrates enhanced classification accuracy in quantum chromodynamics simulations.

2. **Quantum Convolutional Neural Networks (QCNN)**:
   - Extends classical CNNs using quantum circuits for feature extraction.
   - Achieves competitive performance in pneumonia detection tasks.

3. **Hybrid Quantum-Classical Approaches**:
   - Combines quantum computational power with classical optimization for scalable QML models.

---

## How to Use

### Prerequisites
- Python 3.8+ and a compatible quantum simulator (e.g., [TensorFlow Quantum](https://www.tensorflow.org/quantum)).
- Clone the repository:
  ```bash
  git clone https://github.com/dreamboat26/effective-meme.git
  cd effective-meme
  ```
- Run the script provided as .ipynb format
- Visualize the results

## Citation

If you use this repository or reference this work, please cite it as follows:

```bibtex
@article{mahule2024qml,
  title={Quantum Machine Learning: The Superhero That Classical Machine Learning Never Knew It Needed},
  author={Mahule, Roy},
  journal={International Journal for Multidisciplinary Research (IJFMR)},
  volume={6},
  number={3},
  pages={23062},
  year={2024},
  month={May-June},
  doi={10.36948/ijfmr.2024.v06i03.23062}
  url={"https://www.ijfmr.com/research-paper.php?id=23062"}
}
```

## Acknowledgments

I would like to thank the open-source quantum computing community. Special thanks to the developers of TensorFlow Quantum and related tools.

## License

This project is licensed under the MIT License.
