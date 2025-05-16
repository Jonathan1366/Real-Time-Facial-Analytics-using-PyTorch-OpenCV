# Real-Time Facial Analytics with PyTorch and OpenCV

This project demonstrates a real-time facial analytics system using webcam or mobile camera (via DroidCam). It detects faces and analyzes:
- **Age**
- **Gender**
- **Facial Expression (Emotion)**
- **Skin Tone (Fitzpatrick Scale)**
- **Smile Detection**
- **Eyeglasses Detection**

All models are implemented in **PyTorch**, using **OpenCV YuNet** for face detection, and fine-tuned CNNs for classification.

---

## 🧠 Features

- ✅ Age and Gender prediction
- ✅ Emotion classification (FER2013/RAF-DB)
- ✅ Skin tone prediction (Fitzpatrick scale I–VI)
- ✅ Emotion detection
- ✅ Works with built-in or smartphone webcam via USB
- ✅ Real-time performance (CPU/GPU)

---

## 🚀 Tech Stack

- `Python 3.9+`
- `PyTorch`
- `OpenCV (YuNet)`
- `Torchvision`
- `ONNX`


---

## 📊 Model Sources
- Age/Gender: Custom CNN trained on UTKFace

- Emotion: FER2013 & RAF-DB

- Skin Tone: Simulated Fitzpatrick index regressor

- Detection: YuNet ONNX (OpenCV built-in)

---

🧑‍🎓 Author
Created by Jonathan Farrel Emanuel
Student Project (UAS) — Bunda Mulia University
Contact: jonathanfarelemanuel@gmail.com

