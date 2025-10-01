#  Fracture Detection in X-rays  
### Fracture Detection In X-rays Using Custom Convolutional Neural Network (CNN) And Transfer Learning Models  
## 🏆 Featured in Conferences

<table>
   <tr>
      <th>Event Logo</th>
      <th>Event Name</th>
      <th>Event Description</th>
   </tr>
   <tr>
      <td><img src="https://github.com/user-attachments/assets/9b2a64d5-1e47-4437-b4e4-e8101ce59ac0" width="450" height="auto" loading="lazy" alt="ICHPER 2025"/></td>
      <td>ICHPER 2025 – International Conference on Health Professions Education and Research</td>
      <td>
         Our paper <b>“AI-Based Applied Innovation for Fracture Detection in X-rays”</b> 
         was <b>selected for poster presentation</b> at the <b>International Conference on Health Professions Education and Research (ICHPER) 2025</b> 
         under the <b>AI & Health-Tech Innovation Submissions</b>.  
         The work introduces a lightweight CNN framework and benchmarks with transfer learning models 
         (EfficientNetB0, MobileNetV2, ResNet50) on the <a href="https://www.kaggle.com/datasets/tommyngx/fracatlas">FracAtlas dataset</a>, 
         aiming to improve diagnostic accessibility in low-resource healthcare regions.  
      </td>
   </tr>
</table>

🚑 **Automated Fracture Detection for Accessible Healthcare**  

Bone fractures are a major global health challenge, especially in **low-resource regions** where radiology expertise is limited. This project introduces an **AI-based applied innovation** that leverages **deep learning** to automatically detect fractures from X-ray images.  

![WhatsApp Image 2025-08-31 at 22 53 13_1dab4d02](https://github.com/user-attachments/assets/c277408c-abc0-4827-8320-153ae329790a)

![WhatsApp Image 2025-08-31 at 23 30 09_187d9a3f](https://github.com/user-attachments/assets/44c72c00-67c1-485b-8553-016c9822683c)



## 📌 Project Overview  
- **Goal:** Improve diagnostic accessibility & efficiency in fracture detection.  
- **Approach:** Custom Convolutional Neural Network (CNN) + Benchmarking with Transfer Learning models (EfficientNetB0, MobileNetV2, ResNet50).  
- **Dataset:** [FracAtlas](https://www.kaggle.com/datasets/tommyngx/fracatlas) – 4,083 anonymized musculoskeletal X-rays (hand, leg, hip).  
- **Innovation:** A lightweight CNN architecture trained from scratch that outperforms transfer learning models.  
---
## ⚙️ Methodology / Workflow  
1. **Data Preprocessing**  
   - Image resizing (128×128 → 224×224)  
   - Normalization (0–1 scaling)  
   - Handling class imbalance  

2. **Model Development**  
   - Custom CNN with convolutional blocks (ReLU, BatchNorm, MaxPooling, Dropout)  
   - Dense layers with sigmoid output for binary classification  
   - Optimized using **Adam + Binary Cross Entropy**  

3. **Transfer Learning Benchmarks**  
   - EfficientNetB0  
   - MobileNetV2  
   - ResNet50  

4. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-score
   - ![WhatsApp Image 2025-08-31 at 22 53 01_3f0cd767](https://github.com/user-attachments/assets/5430c9c7-679f-4ae2-8ae7-edc6fbc3bd66)
   - ![WhatsApp Image 2025-08-31 at 22 53 22_a047d4c6](https://github.com/user-attachments/assets/48120a5a-627c-493a-ae98-3781bd0d3760)

---

## 📊 Results  
| Model          | Accuracy | Precision | Recall | F1-Score |  
|----------------|----------|-----------|--------|----------|  
| **Custom CNN** | **95.96%** | **0.94** | **0.88** | **0.91** |  
| EfficientNetB0 | 66%      | 0.23–0.85 | 0.38–0.73 | 0.28–0.78 |  
| MobileNetV2    | 65%      | 0.24–0.86 | 0.53–0.71 | 0.33–0.78 |  
| ResNet50       | 67%      | 0.27–0.88 | 0.53–0.71 | 0.36–0.79 |  

✅ Custom CNN **outperformed** all transfer learning baselines.  
✅ Lightweight design → scalable to **portable devices & healthcare systems**.  
---
## 🚀 Expected Impact  
- Reduce reliance on radiologists in **resource-constrained settings**.  
- Speed up workflows, enable **early detection**, and cut costs.  
- Deployable on modest hardware → scalable for hospitals, clinics, and mobile health solutions.  
---
## ⚠️ Challenges & Future Work  
- Dataset imbalance (fracture vs. non-fracture).  
- Limited demographic diversity.  
- Underrepresentation of rare fracture types.  

🔮 **Future Directions:**  
- Expand datasets with diverse patient demographics.  
- Move beyond binary classification → fracture **localization, type, and severity grading**.  
- Explore **Graph Neural Networks (GNNs)** and multi-scale feature extraction.  
- Clinical validation and workflow integration.  
---
## 🔐 Ethics  
- All data sourced from **public, anonymized datasets**.
- No identifiable patient information used.  
- Complies with **ethical standards** for AI in healthcare.  

## Contributors
This project is developed by a dedicated team of contributors, including:

- Amna Hassan 
- Ilsa Afzaal
- Nouman Munib
- Aniqa Batool
- Hamail Noor
---


