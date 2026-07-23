# GraduationProject - 🩸 HemaVision AI

An automated, dual-stream deep learning decision support system for comprehensive peripheral blood cell analysis.

---

## 📌 Overview

**HemaVision AI** combines speed and precision to automate manual peripheral blood smear analysis:
* **YOLOv11m:** Fast localization for Erythrocytes (RBCs) and Platelets.
* **Mask R-CNN (ResNeXt-101):** Granular multi-class instance segmentation for Leukocytes (WBCs).
* **FastAPI & Clinical Dashboard:** Real-time analysis with automated cell counts and clinical review flagging.

---

## ⚡ Key Results

* **RBC & Platelet Detection (YOLOv11m):** `0.94 mAP@50` | `20.3 FPS`
* **WBC Segmentation (Mask R-CNN):** `82.62 AP` across 8 cell classes | `13.4 FPS`
* **End-to-End Pipeline Speed:** `~16.3 FPS` core inference (`~8.0 FPS` with UI/API integration)

---

## 🛠️ Tech Stack

* **Models:** YOLOv11m, Mask R-CNN (ResNeXt-101 + FPN)
* **Backend & API:** Python, PyTorch, Detectron2, FastAPI
* **Hardware:** NVIDIA T4 GPU (Google Colab Pro)

--------------------------------------------------------------------------


## 📌 Proje Hakkında

**HemaVision AI**, manuel mikroskobik kan analizi süreçlerini otomatize etmek amacıyla hız ve hassasiyeti bir araya getiren iki akışlı (dual-stream) bir mimari sunar:

* **YOLOv11m:** Eritrosit (RBC) ve Trombositlerin (Platelet) hızlı ve yüksek doğrulukla konumlandırılması.
* **Mask R-CNN (ResNeXt-101):** Lökositlerin (WBC) 8 farklı alt sınıfı için detaylı örnek segmentasyonu (instance segmentation).
* **FastAPI & Klinik Arayüz:** Otomatik hücre sayımı ve düşük güvenilirlikli tahminler için klinik inceleme bayrakları içeren gerçek zamanlı karar destek paneli.

---

## ⚡ Öne Çıkan Sonuçlar

* **RBC & Trombosit Tespiti (YOLOv11m):** `0.94 mAP@50` | `20.3 FPS`
* **WBC Segmentasyonu (Mask R-CNN):** 8 sınıf genelinde `82.62 AP` | `13.4 FPS`
* **Uçtan Uca Mimarinin Hızı:** `~16.3 FPS` çekirdek model tahmini (`~8.0 FPS` API ve arayüz entegrasyonu dahil)

---

## 🛠️ Teknolojiler

* **Modeller:** YOLOv11m, Mask R-CNN (ResNeXt-101 + FPN)
* **Backend & API:** Python, PyTorch, Detectron2, FastAPI
* **Donanım:** NVIDIA T4 GPU (Google Colab Pro)

<img width="1738" height="962" alt="image" src="https://github.com/user-attachments/assets/4ab192c9-af5e-4753-9b39-3b8d24999904" />

