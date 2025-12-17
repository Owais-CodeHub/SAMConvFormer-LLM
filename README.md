 ### SAMConvFormer+LLM: Exploring synergistic fusion of Segment Anything Model with joint convolutional transformer and large language model to advance dense agricultural crop analysis

<p align="center">
  <strong>Muhammad Owais</strong>, Israa Fahmy, Lakmal Seneviratne, Irfan Hussain  
  <br/>
  Khalifa University Center for Autonomous Robotic Systems (KUCARS), UAE
</p>

<p align="center">
  📄 <strong>Computers and Electronics in Agriculture (2025)</strong>  
  <br/>
  🔗 <a href="https://www.sciencedirect.com/science/article/pii/S0168169925012980">ScienceDirect Paper</a> ·
  📂 <a href="https://figshare.com/s/8f843d7b91a4711210dc">Dataset (Figshare)</a>
</p>


---

## 🚀 Overview

Accurate analysis of **densely fruited crops** is a cornerstone of modern **precision agriculture**, enabling reliable **yield estimation**, **ripeness assessment**, and **data-driven crop management decisions**.

However, real-world agricultural environments introduce severe challenges:
- Highly **overlapping fruit structures**
- **Irregular shapes and sizes**
- **Complex backgrounds and illumination variations**
- Limited generalization of models trained on controlled datasets

To address these challenges, we propose **SAMConvFormer+LLM**, a unified framework that combines:
- **Segment Anything Model (SAM)** for strong general-purpose segmentation priors  
- A **Joint Convolutional Transformer** for robust dense feature modeling  
- A **Large Language Model (LLM)** for high-level reasoning, yield analytics, and actionable agronomic insights  

---

## 🧠 Abstract

We introduce a **real-field dense crop dataset** and a novel **SAMConvFormer** architecture that synergistically fuses the **Segment Anything Model (SAM)** with a **joint convolutional–transformer backbone** to enhance boundary delineation in highly cluttered agricultural scenes.

The proposed framework significantly improves segmentation of **overlapping, blurred, and irregular fruits**, where conventional deep learning models often fail.  
Furthermore, we integrate a **Large Language Model (LLM)** to form a complete end-to-end pipeline that supports:

- Accurate **yield estimation**
- Multi-level **ripeness analysis**
- **Adaptive crop management recommendations**

Extensive experiments and ablation studies demonstrate consistent and substantial improvements over strong baselines, confirming the robustness and scalability of the proposed approach for real-field agricultural deployment.

---

## 🌱 Key Contributions

### 1️⃣ Field-Aware AI Design  
Direct integration of **agricultural expert knowledge** ensures practical relevance and explainability beyond purely data-driven models.

### 2️⃣ SAMConvFormer Architecture  
A novel fusion of:
- **SAM-based segmentation priors**
- **Convolutional feature extraction**
- **Transformer-based global reasoning**

This design enables reliable segmentation in **densely packed crop environments**.

### 3️⃣ LLM-Driven Decision Support  
The integration of an **LLM** enables:
- Automated yield summaries  
- Ripeness distribution analysis  
- Context-aware crop management recommendations  

### 4️⃣ Comprehensive Ablation Analysis  
Detailed experiments isolate and quantify the contribution of each architectural component, validating the effectiveness of the proposed fusion strategy.

### 5️⃣ Open Research Resource  
The **dataset, framework, and experimental materials** are released to support reproducibility and future research in agricultural AI.

---

## ⚙️ Framework Overview

**Figure:** Workflow of the proposed SAMConvFormer + LLM pipeline ![Workflow of the proposed framework](https://github.com/user-attachments/assets/f7b31d25-66a5-4a36-bcfa-5a424484d205)

**Pipeline Summary:**
1. Dense real-field image acquisition  
2. SAM-guided region proposal  
3. Joint convolutional–transformer feature fusion  
4. Fine-grained dense crop segmentation  
5. LLM-based yield, ripeness, and recommendation generation  

---

## 📊 Performance Highlights

| Metric        | Value (%) |
|---------------|-----------|
| Sensitivity   | **79.32** |
| IoU           | **62.64** |
| Dice Score    | **77.03** |

**Relative improvement over baseline:**
- Sensitivity: **+31%**
- IoU: **+18.79%**
- Dice: **+11.56%**

These results demonstrate strong robustness in complex, real-world agricultural conditions.

---

## 📦 Resources

- 📄 **Paper:**  
  https://www.sciencedirect.com/science/article/pii/S0168169925012980

- 📂 **Dataset (Figshare):**  
  https://doi.org/10.6084/m9.figshare.XXXXX *(Pending approval)*

- 🧪 **Code & Models:**  
  Will be released upon dataset activation.

---

## 🧩 Keywords

Precision Agriculture · Dense Crop Segmentation · Yield Estimation ·  
Segment Anything Model · Joint Convolutional Transformer · Large Language Models

---

## 📬 Citation

If you use this data and work in your research, please cite following:

```bibtex
@article{Owais2025SAMConvFormerLLM,
  title   = {SAMConvFormer+LLM: Exploring synergistic fusion of Segment Anything Model with joint convolutional transformer and large language model to advance dense agricultural crop analysis},
  author  = {Owais, Muhammad and Fahmy, Israa and Seneviratne, Lakmal and Hussain, Irfan},
  journal = {Computers and Electronics in Agriculture},
  year    = {2026},
  issn    = {0168-1699},
  doi     = {10.1016/j.compag.2025.111192},
  url     = {https://www.sciencedirect.com/science/article/pii/S0168169925012980}
}

@article{Owais2025AgriVision,
  title   = {AgriVision: A Benchmark Dataset for Advancing Real-World Robotic Vision in Densely Fruited Blueberry Crop},
  author  = {Owais, Muhammad and Shafay, Muhammad and Zubair, Muhammad and Mohammed, Shamal and Seneviratne, Lakmal and Hussain, Irfan},
  journal = {Scientific Data},
  year    = {2025},
  doi     = {10.1038/s41597-025-06263-3},
  url     = {https://doi.org/10.1038/s41597-025-06263-3},
  publisher = {Nature Publishing Group}
}
