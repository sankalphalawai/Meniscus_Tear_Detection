# Meniscus_Tear_Detection
Deep learning-based system for automatic segmentation of the knee meniscus using Nested U-Net with attention, and tear detection using a CNN-GRU model on MRI images. Designed to assist in accurate and automated diagnosis in orthopedic imaging.


---

## 🔧 Technologies Used

- Python, NumPy, OpenCV, Matplotlib
- TensorFlow / Keras (for modeling)
- Scikit-learn (for metrics)
- Pydicom (for handling DICOM MRI images)
- Seaborn (for visualization)

---

## 📊 Results

| Task                | Model Used               | Accuracy / Score |
|---------------------|--------------------------|------------------|
| Meniscus Segmentation | Nested U-Net + Attention | Dice: **0.98** |
| Tear Detection        | CNN-GRU                  | Accuracy: **98.8%** |

---



---

## 📚 References

- MRNet Dataset: https://stanfordmlgroup.github.io/competitions/mrnet/
- U-Net Paper: [Ronneberger et al. (2015)](https://arxiv.org/abs/1505.04597)
- Nested U-Net: [Zhou et al. (2018)](https://arxiv.org/abs/1805.04366)
- Complete Project: [Click Here](https://drive.google.com/drive/folders/1btel0osrMEvESIuL0W_s-ameWWUUUHCk?usp=drive_link)
- For More details: sankalp.halawai@gmail.com
---

## 🚀 Future Work

- Integrate 3D MRI volume segmentation  
- Deploy as a web-based diagnostic tool  
- Extend to multi-label classification (ACL, PCL injuries)

---



