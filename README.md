# YOLOv26-nano on KIIT-MiTA Dataset

🚀 **Testing YOLOv26-nano on Military Drone Imagery**

This repository contains the experiments and results of running the newly released **YOLOv26-nano** model on my custom dataset **KIIT-MiTA (KIIT Military Target Archive)**.

---

## 🧪 Experiment Overview

- **Model:** YOLOv26-nano  
- **Dataset:** KIIT-MiTA (1,700 High-Resolution Drone Images)  
- **Classes (7):** Missile, Tank, Radar, Rocket Launcher, Soldier, Vehicle, Artillery  
- **Task:** Real-time Object Detection on Edge  

The goal was to benchmark YOLOv26-nano on challenging aerial defense imagery and validate its performance on small and distant targets.

---

## 📊 Results

- The Nano model is capable of detecting small objects such as soldiers and artillery units with impressive confidence scores.
- Real-time inference was achieved on edge devices, demonstrating efficiency and accuracy.

![Example Detection](path_to_your_image.png)  
*Figure 1: Example validation batch from KIIT-MiTA dataset*

---

## 🔗 Links

- **Dataset:** [Insert Dataset Link Here]  
- **Code:** [Insert Code Link Here]  
- **Paper / Reference:** [Insert Paper Link Here]  

---

## ⚡ How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/YOLOv26-KIIT-MiTA.git
    ```
2. Download the dataset from the link above.
3. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run inference:
    ```bash
    python run_inference.py --model yolov26-nano --data path_to_dataset
    ```

---

## 📢 Notes

- This repository is intended for **research and benchmarking purposes**.
- Please cite the dataset and this repository if you use it in your work.
- Contributions and feedback are welcome!

---

