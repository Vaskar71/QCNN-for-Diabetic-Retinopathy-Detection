# QCNN for Diabetic Retinopathy Detection (Experimental)

## 🏥 Project Overview
Quantum Convolutional Neural Networks (QCNN) for detecting Diabetic Retinopathy using quantum computing techniques. This project integrates **Qiskit**, **TensorFlow Quantum**, and **image processing libraries** to enhance medical imaging analysis with quantum-based AI models.

---

## 📖 Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## ⚙️ Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Qiskit
- TensorFlow Quantum
- Cirq
- NumPy, Matplotlib, OpenCV, PIL, and scikit-image

### Setup
Run the following commands:
```sh
pip install qiskit tensorflow tensorflow-quantum cirq numpy matplotlib opencv-python pillow scikit-image
```

---

## 🚀 Usage
### Running the Model
1. Clone the repository:
   ```sh
   git clone https://github.com/Vaskar71/Diabetic-Retinography.git
   cd qcnn-diabetic-retinopathy
   ```
2. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
3. Open `QCNN for Diabetic Retinopathy.ipynb` and execute the cells step-by-step.

---

## 🌟 Features
| Feature | Description |
|---------|-------------|
| 🧠 **Quantum CNN** | Uses quantum computing to enhance image classification. |
| 📊 **Medical Imaging** | Processes and analyzes diabetic retinopathy images. |
| 🏎 **Efficient Computation** | Leverages quantum circuits for improved performance. |
| 🔍 **TensorFlow & Qiskit** | Integrates quantum and classical AI frameworks. |

---

## 🔧 Configuration
Modify hyperparameters and dataset paths inside the notebook:
```python
IMAGE_SIZE = (128, 128)
DATASET_PATH = "./data"
EPOCHS = 50
BATCH_SIZE = 32
```

---

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit changes (`git commit -m "Add new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.


## 🎖 Acknowledgments
Special thanks to:
- OpenAI & IBM Qiskit Team
- TensorFlow Quantum Community
- Medical professionals contributing datasets

