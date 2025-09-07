# 📌 Introduction
This project, **Nail Shape Classification using Deep Learning**, aims to automatically classify different nail shapes from images. The motivation comes from both the **beauty & fashion industry** and the **challenge of applying computer vision** to fine-grained visual tasks.

The dataset consists of **6 classes** (Square, Oval, Almond, Round, Stiletto, Coffin) with around **300 images per class (~1800 total)**. Images were collected from **personal captures** and **Pinterest**, then preprocessed with resizing, normalization, and augmentation techniques.

A total of **8 models** were trained and compared:
* **Pretrained models:** VGG16, VGG19, ResNet50, ResNet101, ViT-B16
* **Custom CNNs:** 3-layer, 5-layer, and 7-layer CNN architectures
The results demonstrated that **ResNet50 achieved the best performance**, while custom CNNs showed limitations when trained from scratch.

# 📂 Code & Training Files
You can find the **training and evaluation** codes in the Python files included in this repository.

# ✅ Conclusion
This project successfully built a **deep learning-based** **system** for nail shape classification. Among the 8 models trained, **ResNet50** achieved the highest performance, reaching perfect accuracy and precision on the validation set.

The results highlight the effectiveness of **transfer learning** when working with relatively small datasets compared to training custom CNNs from scratch. Preprocessing and augmentation also played a crucial role in boosting model performance and reducing overfitting.

In the future, the project can be extended by:
* Collecting a **larger and more diverse dataset**.
* Improving generalization with advanced augmentation techniques.
Deploying the model as a **mobile or web application** for real-world use.
