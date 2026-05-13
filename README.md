# 🌿 EnviroVision – Species Identification Software

EnviroVision is a deep learning–powered software designed to **automate species identification** in biodiversity research and ecological fieldwork. Developed as part of a B.Tech dissertation at **Dr. B. R. Ambedkar Institute of Technology, Pondicherry University**, this project addresses the challenges faced by researchers at the **Zoological Survey of India (ZSI)** in rapid and accurate species classification.

---

## 📌 Abstract

Traditionally, species identification is a **time-consuming, expertise-driven task** requiring manual verification. EnviroVision leverages **Convolutional Neural Networks (CNNs)** to streamline this process, enabling **real-time, image-based species classification**.

- **Main CNN (XceptionNet)** – Performs high-level classification (e.g., bird, butterfly, insect).
- **Sub CNNs (EfficientNetV2-Large)** – Provide fine-grained classification within each category to identify the exact species.
- **Result** – High accuracy, scalable architecture, and reduced dependency on manual verification.

This project demonstrates the potential of **AI in biodiversity studies**, contributing to the digitization and automation of ecological fieldwork.

---

## 🎯 Objectives

- Develop a robust system to classify and identify species from field images.
- Provide a **user-friendly interface** for researchers to upload images and receive instant results.
- Enhance efficiency and accuracy of biodiversity documentation for ZSI.

---

## 🔬 System Architecture

### Two-Stage CNN Workflow
1. **Stage 1 – Main CNN (XceptionNet)**  
   - Broad-level classification into categories (bird, butterfly, insect, etc.).
2. **Stage 2 – Sub CNNs (EfficientNetV2-Large)**  
   - Fine-grained classification for exact species identification.

![Architecture Diagram Placeholder](https://via.placeholder.com/600x300?text=System+Architecture)

---

## ⚙️ System Requirements

### Hardware
| Component   | Minimum | Recommended |
|-------------|---------|-------------|
| RAM         | 8 GB    | 16 GB+      |
| CPU         | Intel i5 / AMD Ryzen 5 | Intel i7+ |
| GPU         | Not required | NVIDIA GPU (CUDA support) |
| Storage     | 500 MB  | 1 GB+ |
| Display     | 720p    | 1080p+ |

### Software
- **OS**: Windows 10/11 (64-bit).
- **Backend**: Python, TensorFlow/Keras.
- **Frontend**: Desktop application with image upload support
- **Database (optional)**: SQLite / Firebase

---

## 🖥️ Features

- 📸 **Image Upload & Cropping** – Upload field images directly from mobile/camera.
- ⚡ **Real-Time Prediction** – Instant classification results.
- 🐦 **Species Categories Supported** – Birds, butterflies, snakes, frogs, lizards, moths, odonata (dragonflies/damselflies).
- 💾 **Offline Capability** – Works without internet connectivity.
- 🔄 **Scalable Design** – Easily extendable to new species categories.

---

## 🚀 Implementation Highlights

- **XceptionNet** chosen for its efficiency in broad classification.
- **EfficientNetV2-Large** selected for fine-grained accuracy in subcategories.
- Modular design ensures **easy scalability** and **future enhancements**.
- Built as a **standalone executable (.exe)** for ease of deployment.

---

## 🧪 Testing & Results

- Manual testing conducted across multiple species categories.
- High accuracy achieved under diverse field conditions.
- Interfaces tested for usability and researcher-friendly workflows.

---

## 🔮 Future Enhancements

- Expand dataset to include **rare and untrained species**.
- Integrate **multimodal inputs** (audio + image for bird calls).
- Mobile app version for **on-the-go identification**.
- Cloud-based logging for **collaborative biodiversity databases**.

---

## 📚 References

- iNaturalist, Pl@ntNet, Merlin Bird ID – Existing tools studied for comparison.
- CNN architectures: XceptionNet (Chollet, 2017), EfficientNetV2 (Tan & Le, 2021).
- Related research projects: BirdNET (Cornell Lab), VGG-based insect classifiers (Oxford University).

---

## 👨‍💻 Authors

- **T Naresh**
- **Swasti Ranjan Biswas**  
- **K Vijay Kumar**  
- **Dimpy Sarkar**

Under the guidance of **Mr. Harsabardhan Barik (Associate Professor, CSE)**  
Dr. B. R. Ambedkar Institute of Technology, Port Blair

---

## 🏷️ License

This project is developed for academic purposes. For reuse or collaboration, please contact the authors.

---

## 🌍 Acknowledgements

Special thanks to:
- **Zoological Survey of India (ZSI)** for fieldwork insights.  
- Faculty and staff of **Dr. B. R. Ambedkar Institute of Technology** for guidance and support.  

