# ♻️ WasteAI System - Real-Time Waste Detection with YOLOv11s

This project presents a real-time **waste classification and detection system** using **YOLOv11s**, developed under **limited computational resources** yet delivering **promising and actionable results**. The goal is to support sustainable efforts by empowering waste-monitoring initiatives, particularly those protecting natural environments.

---

## 🚀 Project Highlights

- ✅ **Model**: YOLOv11s (Ultralytics 8.3.x)
- 🧠 **Classes Detected**: 12 types of waste including:
  - plastic bottles
  - plastic bags
  - metal
  - paper
  - cigarette butts
  - glass
  - trash cans
  - and more
- 📊 **Performance**:
  - **Overall mAP50**: up to **76.5%**
  - High performance on key classes:
    - `glass` → **mAP50: 82.6%**
    - `pile_of_trash` → **mAP50: 70.2%**
    - `trash_can` → **mAP50: 99.5%**
    - `paper` → **mAP50: 49.4%**
- ⚡ Runs in **real time** on GPU (Tesla T4), suitable for **low-resource environments**

---

## 🌍 Real-World Impact


**With this model:**
- 🧹 Volunteers can scan beaches **in real time**
- ♻️ Waste types are **automatically classified**
- 🗺️ Helps **prioritize clean-up** efforts and improve **waste mapping**

---

## 🛠️ Technical Overview

| Component        | Details                              |
|------------------|--------------------------------------|
| **Framework**    | YOLOv11s (Ultralytics)               |
| **Training Epochs** | Limited (due to compute constraints) |
| **Dataset**      | 77 images, 401–516 labeled instances |
| **Hardware**     | GPU: Tesla T4                        |
| **Inference**    | Real-time detection pipeline         |

---

## 💡 Why It Matters

This project demonstrates that with:

- ✅ **Thoughtful dataset preparation**
- ✅ **Efficient models like YOLOv11s**
- ✅ **Even limited resources**

... we can still deliver **meaningful, socially impactful AI solutions** that empower **real-world environmental action**.

---

> 📫 For more info or contributions, feel free to open an issue or fork this repo!

