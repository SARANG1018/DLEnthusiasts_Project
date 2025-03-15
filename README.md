# **DLEnthusiasts Project**
A deep learning mini-project (Deep Learning CS 6953 / ECE 7123 2025 Spring) implementing a custom **ResNet** model for **CIFAR-10 classification**, achieving **84.09% accuracy**.

## **📌 Overview**
This project explores **Residual Networks (ResNets)** to mitigate vanishing gradient problems in deep CNNs. Our architecture leverages **skip connections** and **Squeeze-and-Excitation (SE) blocks** for feature recalibration.

## **📂 Project Structure**
```
DLEnthusiasts_Project/
│── datasets/           # CIFAR-10 dataset processing
│── notebooks/          # Jupyter notebooks for training & evaluation
│── models/             # ResNet model implementation
│── src/                # Training scripts & utilities
│── results/            # Training logs & model performance reports
│── README.md           # Project documentation
│── requirements.txt    # Dependencies
```

## **🛠 Installation**
```sh
git clone https://github.com/SARANG1018/DLEnthusiasts_Project.git
cd DLEnthusiasts_Project
pip install -r requirements.txt
```

## **🚀 Usage**
Train the ResNet model:
```sh
python src/train.py --model ResNet --epochs 20
```
Evaluate the model:
```sh
python src/evaluate.py --model ResNet
```

## **📊 Results**
- **Best test accuracy**: **84.09%** on CIFAR-10
- **Best ResNet configuration**:
  - **Channels**: `[16, 32, 128, 256]`
  - **Optimizer**: Adam (`lr=0.00037`)
  - **Regularization**: Batch Normalization, Dropout, SE Blocks

## **📬 Contact**
- **Sarang Kadakia** ([sk11634@nyu.edu](mailto:sk11634@nyu.edu))
- **Vishwajeet Kulkarni** ([vk2630@nyu.edu](mailto:vk2630@nyu.edu))

---

⭐ **If you find this project useful, please give it a star!** 🚀
