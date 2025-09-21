# 📊 Mgaze-US: Multi-center Gaze Ultrasound Dataset

**Mgaze-US** is a large-scale **multi-center, multi-organ ultrasound dataset with gaze annotations**.  
It is designed to support research on **gaze-driven human–robot interaction, visual prompting, medical image segmentation, and robotic ultrasound systems (RUSS)**.  
This dataset has been curated and preprocessed to remove scanner-specific artifacts and metadata, enabling broad usability across domains.  

---

## 📂 Dataset Overview

- **Total Images**: **15,649**  
- **Centers**: 8 countries 🌍 across 5 continents  
- **Modalities**: Standard **B-mode ultrasound**  
- **Annotations**:  
  - ✅ Manual segmentation labels **Y**  
  - 👁️ Gaze fixation positions  
  - 🔥 Gaze heatmaps  

---

## 🏥 Anatomical Coverage

The dataset spans a wide variety of anatomical structures to encourage **cross-organ generalization**:

-  **Thyroid** — Colombia  
-  **Breast** — Egypt, Brazil  
-  **Liver** — China  
-  **Kidney** — Canada  
-  **Muscle** — Netherlands
-  **Carotid Artery** — Poland  
-  **Brachial Plexus** — Unknown 
<img width="2000" height="1332" alt="image" src="https://github.com/user-attachments/assets/3c11a1f0-78e5-455c-b62e-34c9fc7b9165" />

---

## ⚙️ Preprocessing

- All ultrasound images were preprocessed using **EchoLocator** to ensure removal of **scanner-specific artifacts and metadata**.  
- Images are aligned and normalized for cross-domain comparison.  

---

## 📢 Note on Data Availability
Due to size limitations on GitHub, we only provide partial subsets of Mgaze-US, including Kidney, Thyroid, and Liver.
For access to the complete dataset, please visit our release on HuggingFace Datasets: 👉 [HAN4BME/MGaze-US
](https://huggingface.co/datasets/HAN4BME/MGaze-US)

For any questions, you can reach me at [taiyuhan4bme@tsinghua.email.cn].
---

## 📑 Citation

If you use Mgaze-US in your research, please acknowledge this dataset. The associated paper has been submitted to ICRA 2026 and should be cited once it is accepted.

