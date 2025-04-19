learn pytorch synatx - apply pytorch syntax - tablular data classicfication  - data classification - audio classificaiton - video classification


# 🧠 5 PyTorch Projects

A collection of 5 progressive projects to master **PyTorch**, starting from basic syntax to handling real-world data across **tabular**, **image**, **audio**, and **video** domains.

---

## 📁 Project Overview

| Stage | Project | Description |
|-------|---------|-------------|
| 1️⃣ | Learn PyTorch Syntax | Understand basic PyTorch tensors, operations, and model building blocks. |
| 2️⃣ | Apply PyTorch Syntax | Implement a simple neural network on synthetic data to reinforce core concepts. |
| 3️⃣ | Tabular Data Classification | Use PyTorch for real-world structured/tabular data classification (e.g., Titanic dataset). |
| 4️⃣ | Audio Classification | Work with spectrograms or waveforms to classify audio using CNNs or RNNs. |
| 5️⃣ | Video Classification | Build a model to classify videos using frame sampling or 3D CNNs. |

---

## 🔧 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/your-username/5_pytorch_projects.git
cd 5_pytorch_projects

# (Recommended) Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

---

## 📚 Project Details

### 1️⃣ Learn PyTorch Syntax
- ✅ Tensors, broadcasting, GPU support
- ✅ Autograd and gradients
- ✅ Simple linear regression with manual updates

📄 `1_learn_pytorch_syntax/`

---

### 2️⃣ Apply PyTorch Syntax
- ✅ Define `Dataset` and `DataLoader`
- ✅ Create a custom `nn.Module`
- ✅ Train & evaluate model using MSELoss or CrossEntropyLoss

📄 `2_apply_pytorch_syntax/`

---

### 3️⃣ Tabular Data Classification
- ✅ Preprocess CSV dataset
- ✅ Handle missing values & categorical encoding
- ✅ Train MLP model on tabular data
- ✅ Evaluate with accuracy, confusion matrix

📄 `3_tabular_data_classification/`

---

### 4️⃣ Audio Classification
- ✅ Convert raw audio to spectrograms (e.g., Mel, MFCC)
- ✅ CNN model for sound event classification
- ✅ Use torchaudio or librosa
- ✅ Augmentations like noise, time masking

📄 `4_audio_classification/`

---

### 5️⃣ Video Classification
- ✅ Extract frames from videos
- ✅ Sample frame sequences for model input
- ✅ Use pretrained CNN or 3D ConvNet
- ✅ Handle variable video lengths

📄 `5_video_classification/`

---

## 📦 Dependencies

Add these to your `requirements.txt`:

```text
torch
torchvision
torchaudio
pandas
numpy
matplotlib
scikit-learn
opencv-python
tqdm
librosa
```

---

## 🤝 Contributions

Feel free to fork and contribute via pull requests!

---

## 📜 License

MIT License © 2025 Your Name

---
