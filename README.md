# HelmetML-Dataset
HelmetML: A balanced dataset of 27,560 images featuring Full-Face, Half-Face, Modular, and Off-Road helmets in correct and incorrect configurations. Captured via iPhone 13 across diverse climatic conditions to support ML tasks like image classification, object detection, and pose estimation for motorcycle safety.

# HelmetML: A Dataset of Helmet Images for Machine Learning Applications

**HelmetML** is a comprehensive dataset of **27,560 images** designed to improve motorcycle safety through automated helmet detection.The dataset features diverse helmet types, orientations, and environmental conditions to support tasks such as image classification, object detection, and pose estimation.
The primary motivation for this dataset is to address the significant issue of fatal motorcycle accidents caused by improper or absent helmet usage.The envisioned application is a system that could potentially automate enforcement or actuate motorcycle ignition only when a helmet is correctly worn.

## 📂 Data Access
* **Repository Name:** Mendeley Data 
* **DOI:** 10.17632/tm72fkfxd5.2 
* **Direct Download:** [Helmet Wearing Image Dataset](https://data.mendeley.com/datasets/tm72fkfxd5/2) 

## 👥 Authors and Affiliations
* **Vishwakarma University, Pune, India**: Kailas Patil, Yogesh Suryawanshi, Gaurav Khare, Tanishk Shinde 
* **Kasetsart University, Sriracha, Thailand**: Prawit Chumchu 
* **Corresponding Author**: Dr. Kailas Patil (`kailas.patil@vupune.ac.in`)

## 📊 Dataset Specifications
* **Total Images**: 27,560 
* **Resolution**: Standardized to **768 x 576** pixels 
* **Format**: Raw Images (.jpg) 
* **Classes**: 2 main categories (**Correct way** and **Incorrect way**) 
* **Capture Device**: iPhone 13 mobile application 
* **Location**: Captured at Vishwakarma University, Pune, India (18°27'37.8"N 73°53'00.9"E) 
* **Lighting Conditions**: Diverse scenarios including daytime and night-time 
* **Perspectives**: Images cover 180-degree perspectives of the subjects.

## 🪖 Helmet Categories
The dataset includes four distinct helmet types widely used by riders:

1. **Full-Face Helmet**: Provides the most protection for the head, face, and neck. typically used by motorcycle riders and race car drivers.
2. **Half-Face Helmet**: Protects the head but not the face. Common among scooter and moped riders.
3. **Modular Helmet (Flip-up)**: Can be opened to expose the face. Useful for riders who need to speak or eat without removing the helmet.
4. **Off-Road Helmet**: Designed for dirt bikes/motocross. Features a visor for debris protection and a peak to block sunlight.

## 📁 Directory Structure
The dataset is hierarchically organized to ensure a perfectly balanced distribution, with **3,445 images per subfolder**.

```text
dataset/
[cite_start]├── Correct way/ (13,780 images) [cite: 115]
│   ├── Full-Face Helmet/
│   ├── Half-Face Helmet/
│   ├── Modular Helmet/
│   └── Off-Road Helmet/
[cite_start]└── Incorrect way/ (13,780 images) [cite: 115]
    ├── Full-Face Helmet/
    ├── Half-Face Helmet/
    ├── Modular Helmet/
    └── Off-Road Helmet/
