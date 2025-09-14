# 🐶 Dog Breed Classification using CNNs (AlexNet, ResNet, VGG16)

This project implements **dog breed classification** using **Convolutional Neural Networks (CNNs)** with transfer learning.  
The goal is to classify whether an input image is:  

- 🐕 A dog or not a dog  
- 🏷️ If it is a dog, correctly identify its **breed**  

We evaluated and compared three popular CNN architectures:  
- **AlexNet**  
- **ResNet**  
- **VGG16**  

---

## 📊 Dataset
- **Total Images:** 40  
- **Dog Images:** 30  
- **Not-a-Dog Images:** 10  

---

## 🚀 Results
The models were tested on uploaded images and a small dataset.  
Performance metrics include correct identification of dogs, non-dogs, breeds, and label matches.  

### 🔎 Classification Results Table
<img width="944" height="341" alt="Screenshot 2025-09-14 180344" src="https://github.com/user-attachments/assets/53f855ed-200a-4be7-b9bb-29f6f6fc385d" />


---
## ▶️ How to Run

To test the uploaded images with all three CNN models, run the provided shell script:  


## 📝 Questions & Answers  

**1. Did the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed?**  
✔️ Yes, all three classified **Basenji_01.jpg** correctly as **Basenji**.  

**2. Did the three model architectures classify Dog_02.jpg as the same breed?**  
✔️ Yes, all three classified **Basenji_02.jpg** correctly as **Basenji**.  

**3. Did the three model architectures correctly classify Animal_Name_01.jpg and Object_Name_01.jpg as not dogs?**  
✔️ Yes, all three correctly classified **Black Bear** and **Coffee Mug** as **not dogs**.  

**4. Which model performed the best?**  
🔹 All models performed equally well on uploaded images.  
🔹 Based on overall architecture strength and performance on larger datasets, **ResNet** is chosen as the best.  

---

## 🛠️ Tech Stack
- 🐍 Python  
- 🔥 PyTorch / TensorFlow  
- 📦 Pre-trained CNN models (AlexNet, ResNet, VGG16)  

---

✨ Developed by [**Chakkasandeep**](https://github.com/Chakkasandeep)  
## ▶️ How to Run

To test the uploaded images with all three CNN models, run the provided shell script:  

```bash
# Open a terminal window inside the Project Workspace - Uploaded Images
sh run_models_batch_uploaded.sh
