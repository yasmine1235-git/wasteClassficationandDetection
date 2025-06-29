♻️ WasteAI System - Real-Time Waste Detection with YOLOv11s
This project presents a real-time waste classification and detection system using YOLOv11s, developed under limited computational resources yet delivering promising and actionable results. The goal is to support sustainable efforts by empowering waste-monitoring initiatives, particularly those protecting natural environments.

🚀 Project Highlights
✅ Model: YOLOv11s (Ultralytics 8.3.x)

🧠 Classes Detected: 12 types of waste including plastic bottles, bags, metal, paper, cigarette butts, glass, and more.

📊 Performance:

Overall mAP50: up to 76.5%

Strong precision/recall on critical waste types like:

glass → mAP50: 82.6%

pile_of_trash → mAP50: 70.2%

trash_can → mAP50: 99.5%

paper → mAP50: 49.4%

⚡ Runs in real time on GPU (Tesla T4), suitable for deployment in low-resource settings.

🌍 Real-World Impact
This model was successfully integrated into the operations of the Second Life NGO, a non-profit based in Valencia, Spain, focused on beach cleaning and environmental conservation. While the model detects a wide range of waste categories, it excelled in the classes that mattered most to the NGO's needs—making it an effective and targeted solution despite modest resources and few training epochs.

By using this model:

Volunteers can scan beaches in real time

Waste types are automatically classified

It helps prioritize clean-up actions and improve waste mapping efforts

🛠️ Technical Overview
Framework: YOLOv11s (Ultralytics)

Training epochs: ⚙️ Limited (due to compute budget)

Data: 77 images, 401–516 labeled instances

Platform: CUDA-enabled GPU (Tesla T4)

Inference: Real-time detection pipeline

💡 Why It Matters
This project demonstrates that with:

Thoughtful labeling

Efficient models like YOLOv11s

Even limited hardware

...we can still deliver meaningful AI solutions that contribute to environmental causes and serve real NGOs on the ground.
