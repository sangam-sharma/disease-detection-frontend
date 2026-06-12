# MediFuse — Multimodal Disease Diagnosis & Forecasting Dashboard

MediFuse is an advanced, healthcare-focused web application designed to bridge the gap between complex artificial intelligence models and clinical/patient utility. The interface serves as a comprehensive medical dashboard that aggregates multimodal inputs—including **structured laboratory reports**, **medical imaging (X-Ray/CT/MRI)**, and **natural language symptom narratives**—to provide explainable, multi-disease risk forecasting.

Built with clean, production-ready semantics and designed for accessibility, MediFuse features complete multi-role flows (Patient, Doctor, Admin) alongside embedded eXplainable AI (XAI) visualizations.

---

## ✦ Key Features

* **Multimodal Data Fusion Interface:** Separate specialized modules to input clinical text, upload high-resolution DICOM/JPEG imaging, and log structured physiological biomarkers (Blood Pressure, Glucose, Cholesterol).
* **eXplainable AI (XAI) Integration:** Built-in semantic layouts for **SHAP Feature Importance** bar plots and **Grad-CAM Chest X-Ray heat overlays** to help clinicians confidently understand the model's decision-making pathway.
* **Multilingual Support (12 Indian Languages):** Accessible patient-friendly plain-language summaries localized into Hindi, Tamil, Bengali, Telugu, and more, complete with text-to-speech toggles.
* **Geospatial Referral System:** Integrated neighborhood mapping system that automatically references and highlights nearby tertiary hospitals or specialty clinics based on the user's diagnosed risk criteria.
* **Multi-Role Dashboards:**
    * **Patient Portal:** Track historical vitals, view simplified risk gauges, and download comprehensive PDF medical summaries.
    * **Doctor Workspace:** High-level view of patient triage queues, weekly disease distribution vectors, and diagnostic verification tools.
    * **Admin Panel:** Critical engineering monitors for model drift detection, data storage capacity, system metrics, and hot-swapping container deployments.

---

## 🎨 Design System & UI Architecture

The interface uses a highly premium, modern healthcare aesthetic optimized for high scannability and minimal cognitive load during critical clinical scenarios:
* **Typography:** Elegant pairing of `Fraunces` (Serif) for confident headers/branding and `DM Sans` (Sans-Serif) for ultra-clear data reading.
* **Color Palette:** Dominated by deeply professional Navy (`#0d2340`) and reassuring Blues/Teals, balanced against strict semantic warning tags (Low/Medium/High risk alerts).
* **Responsiveness:** Fluid grid engine (`grid-2`, `grid-3`, `grid-4`) utilizing modern CSS variables that perfectly adapt to standard desktop monitors or mobile devices for on-the-go doctors.

---

## 🛠️ Tech Stack & Code Component Overview

* **Frontend Structure:** Semantic HTML5, CSS3 Custom Properties (Variables), and Asynchronous Vanilla JavaScript.
* **Data Visualization:** Embedded vector-perfect SVG elements representing live model evaluation parameters including a **Real-time Patient Risk Gauge**, **Weekly Patient Distributions**, and a **Model ROC Curve (with calculated AUC performance metrics)**.
* **State & Navigation Simulation:** Responsive screen-toggle handling engine optimizing application state switching across 9 distinct application panels under a single micro-navigation framework.

---

## 🚀 How To Run & Test Locally

Since the frontend is entirely self-contained, lightweight, and requires no heavy external framework compilation overhead, you can spin it up instantly:

### Option 1: Live Server (Recommended)
1. Clone this repository to your local directory:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/MediFuse.git](https://github.com/YOUR_USERNAME/MediFuse.git)
