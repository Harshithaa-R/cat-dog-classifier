# cat-dog-classifier
# 🐶🐱 Cat vs Dog Classifier (FastAI + ResNet34)

This project uses [FastAI](https://docs.fast.ai/) and a pretrained **ResNet34** model to classify cats vs dogs.  
Dataset: [Oxford-IIIT Pets](https://www.robots.ox.ac.uk/~vgg/data/pets/) (subset used: cats & dogs).  

---

## 🚀 Project Overview
- Built an image classifier with **transfer learning** (ResNet34 backbone).  
- Achieved **~90%+ validation accuracy**.  
- Performed error analysis with **confusion matrix** and **top losses** visualization.  
- Packaged into a reproducible Jupyter notebook.  

---

## 📊 Results
Validation Accuracy: ~90%+  

**Confusion Matrix**  
![Confusion Matrix](results/confusion_matrix.png)  

**Top Losses (Misclassified Examples)**  
![Top Losses](results/top_losses.png)  

**Sample Prediction**  
![Sample Prediction](results/sample_prediction.png)  

---

## 📂 Files
- `cat_dog_classifier.ipynb` → Training & evaluation notebook  
- `results/` → Visualizations (confusion matrix, top losses, sample prediction)  

---

## ⚙️ How to Run
```bash
pip install fastai torch torchvision matplotlib pillow
