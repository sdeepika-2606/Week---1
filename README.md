# 🌱 E-Waste Generation Using ResNet50 for Sustainable Recycling Solutions

## 📌 Project Overview
This project focuses on classifying electronic waste (e-waste) into different categories using **ResNet50**, a deep convolutional neural network. The goal is to build an AI-driven system to **automate e-waste classification** from images, which helps in streamlining the recycling process and promotes sustainable waste management.

---

## 🗂️ Week 1 Milestone

### ✅ Improvisations Done
- Selected **ResNet50** for better accuracy with lower complexity over heavier models like EfficientNet.
- Designed a **flowchart** representing the workflow of the project using Canva.
- Collected the e-waste dataset from Kaggle and identified 10 specific classes.
- Performed image **resizing, normalization**, and **data augmentation** as preprocessing steps.
- Understood and applied **transfer learning concepts** to integrate a custom classification head on top of ResNet50.

---

## 🧠 Project Workflow

1. **Dataset Acquisition** – 10-class e-waste dataset from Kaggle  
2. **Data Preprocessing** – Image resizing (128x128), normalization, and augmentation  
3. **Model Selection** – Used ResNet50 pre-trained on ImageNet  
4. **Model Development** – Added custom classification layers  
5. **Model Training** – Used Adam optimizer with early stopping  
6. **Model Evaluation** – Assessed accuracy, precision, recall, and F1-score  
7. **Visualization** – Generated a process flowchart  
8. *(Deployment will be added in later weeks)*

---

## 🧾 Dataset Used
- [Kaggle: E-Waste Image Dataset](https://www.kaggle.com/datasets/akshat103/e-waste-image-dataset)  
- Categories: `PCB`, `Battery`, `Player`, `Microwave`, `Mobile`, `Mouse`, `Printer`, `Television`, `Washing Machine`, `Keyboard`

---

## 🛠️ Tools & Technologies

- **Language:** Python  
- **Frameworks:** TensorFlow, Keras  
- **Libraries:** NumPy, Matplotlib, OpenCV, PIL  
- **Interface (Upcoming):** Gradio  
- **Design:** Canva (for flowchart and architecture)

---

## 📊 Output (Planned)
- Test Accuracy ~96%
- Model able to classify new e-waste images correctly
- Will be deployed with Gradio UI in later weeks

---

## 🔗 GitHub Repository Link for Week 1 Milestone
`https://github.com/your-username/e-waste-resnet50`  
(Replace with your actual repo URL)

---

## 📌 Next Steps
- Improve model performance with hyperparameter tuning  
- Prepare UI for real-time testing  
- Deploy model using Gradio or Streamlit  
- Add confusion matrix and per-class visualizations

---

> 👩‍💻 Developed by Deepika S | B.E. Cybersecurity | Week 1 Project Submission
