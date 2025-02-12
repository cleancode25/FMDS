# Advanced Face Mask Detection System 🎭

## 📌 Overview  
The **Advanced Face Mask Detection System** is an AI-based project that automatically detects whether a person is wearing a mask or not in real-time. This system is built using **Python, OpenCV, TensorFlow, and Deep Learning** to enhance public safety by ensuring compliance with mask-wearing policies.

## 🚀 Features  
✅ Real-time face mask detection using webcam  
✅ Supports multiple mask types (cloth masks, scarves, hijabs, niqabs, traditional beard coverings)  
✅ Deep learning-based CNN model for high accuracy  
✅ Lightweight and efficient for real-time applications  
✅ Works with images, live video streams, and recorded video  
✅ Displays detection results on-screen  

## 📂 Project Structure  
```
📦 Face-Mask-Detection
│-- 📁 dataset          # Dataset containing masked and unmasked images
│-- 📁 models           # Trained deep learning models
│-- 📁 utils            # Helper scripts for preprocessing
│-- 📁 results          # Output results & logs
│-- 📜 app.py           # Main application script
│-- 📜 train.py         # Model training script
│-- 📜 detect.py        # Face mask detection script
│-- 📜 requirements.txt # Dependencies
│-- 📜 README.md        # Project documentation
```

## 🛠️ Tech Stack Used  
- **Python** 🐍  
- **OpenCV** 👀 (Image Processing)  
- **TensorFlow / Keras** 🤖 (Deep Learning)  
- **CNN (Convolutional Neural Network)** 🔥  
- **Matplotlib & NumPy** 📊  

## 🔄 Project Workflow  
1️⃣ **Data Preprocessing Phase**  
   - Collected images of masked and unmasked faces  
   - Augmented dataset to improve model generalization  
   - Resized and normalized images  

2️⃣ **Model Development Phase**  
   - Designed a CNN model for classification  
   - Trained the model with labeled dataset  
   - Optimized accuracy and reduced false detections  

3️⃣ **Testing & Implementation Phase**  
   - Deployed the model for real-time detection  
   - Evaluated performance with different lighting conditions  
   - Improved detection for various mask types  

## 🖥️ Installation Guide  
1️⃣ **Clone the repository**  
```bash
git clone https://github.com/yourusername/Face-Mask-Detection.git
cd Face-Mask-Detection
```

2️⃣ **Install dependencies**  
```bash
pip install -r requirements.txt
```

3️⃣ **Run the detection script**  
```bash
python detect.py
```

## 📌 How It Works  
1. The system captures live video from the webcam  
2. It detects faces using OpenCV’s face detection algorithm  
3. The trained CNN model classifies whether a mask is present or not  
4. The result is displayed on the screen with a bounding box  

## 🎯 Applications  
📌 Public places like airports, malls, and hospitals  
📌 Offices and workplaces for safety compliance  
📌 Integration with CCTV for automated surveillance  
📌 Can be extended for other PPE detection (helmets, gloves)  

## 🚀 Future Scope  
📌 **Enhanced Mask Detection** – Recognizing different types of face coverings  
📌 **Mobile App Integration** – Deploying the model on mobile devices  
📌 **Edge AI Implementation** – Running on low-power devices (Raspberry Pi)  

## 🛑 Limitations  
❌ May struggle with poor lighting conditions  
❌ Limited dataset might affect accuracy in rare cases  
❌ Works best with frontal face orientation  
  

## 📜 License  
This project is **open-source** under the [MIT License](LICENSE).  

## 🤝 Contributing  
Pull requests are welcome! If you find issues, feel free to raise an **issue** in the repository.  

## ⭐ Acknowledgments  
Special thanks to **TensorFlow, OpenCV, and Kaggle datasets** for enabling this project!  

---  
🚀 **Like this project? Give it a ⭐ on GitHub!**  

```
