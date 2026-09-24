# 🌱 EcoSort AI - Smart Waste Companion

**EcoSort AI** is an intelligent web application that uses computer vision to classify waste items in real-time and guide users on how to properly sort them (Compost, Recycling, or Landfill). Powered by a custom-trained **Google Teachable Machine** model and TensorFlow.js, it runs entirely on-device to ensure privacy and speed.

![EcoSort AI Preview](https://img.shields.io/badge/Status-Active-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38BDF8?style=flat&logo=tailwind-css&logoColor=white) ![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=flat&logo=tensorflow&logoColor=white)

---

## 🚀 Features

- **Live Camera Feed:** Real-time object recognition directly from your webcam.
- **Image Upload Support:** Drag-and-drop or browse local images to analyze static photos.
- **On-Device Machine Learning:** Loads your custom Teachable Machine model (`eBrVMMXzt`) via TensorFlow.js for instant, private classification.
- **Dynamic Confidence Breakdown:** Visual progress bars displaying prediction confidence levels for each class.
- **Earthy Aesthetic UI:** Minimalist, high-end green-themed dashboard designed for clarity and modern user experience.

---

## 🛠️ Tech Stack

- **HTML5 / CSS3 / JavaScript (ES6+)**
- **Tailwind CSS** (via CDN for styling)
- **TensorFlow.js** (`@tensorflow/tfjs`)
- **Teachable Machine Image Model** (`@teachablemachine/image`)

---

## 📦 Local Setup & Installation

To run this project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/ecosort-ai.git](https://github.com/YOUR_USERNAME/ecosort-ai.git)
   cd ecosort-ai
