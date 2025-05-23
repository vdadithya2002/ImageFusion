# 🌍 Image Fusion for Change Detection using Machine Learning

This mini project focuses on detecting changes between two satellite images using image processing techniques. The goal is to create a basic system that can identify land cover or land use changes over time.

---

## 🧠 Project Overview

- **Objective**: Detect and visualize changes between multi-temporal satellite images.
- **Approach**:
  - Preprocess images using histogram equalization.
  - Convert to grayscale.
  - Compute absolute difference.
  - Apply thresholding to generate a binary change map.

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## 📁 Dataset

We used real satellite images of **Visakhapatnam Port** area:
- **Image 1**: Before changes
- **Image 2**: After changes (latest Google Maps view)

---

## 🔄 Workflow

1. Load satellite images.
2. Apply histogram equalization for contrast enhancement.
3. Convert images to grayscale.
4. Compute absolute difference.
5. Apply thresholding to highlight significant changes.
6. Display and save the change map.

---

## 📸 Outputs

- Grayscale Image (Before and After)
- Difference Image
- Binary Change Map

These images clearly highlight changed regions between the two dates.

---

## 📌 Future Scope

- Integrate Machine Learning (SVM, Random Forest)
- Use Deep Learning (CNN) for advanced change classification
- Work with large-scale remote sensing datasets (e.g. Sentinel, Landsat)

---

## 📄 License

This project is for educational purposes under MIT License.
