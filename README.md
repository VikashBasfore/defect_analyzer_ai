<div align="center">

# 🏗️ AI Structural Defect Analyzer

### Detect • Assess • Recommend • Report using Google Gemini Vision AI

<img src="https://img.shields.io/badge/Python-3.11-blue?logo=python">
<img src="https://img.shields.io/badge/Streamlit-Web%20Application-FF4B4B?logo=streamlit">
<img src="https://img.shields.io/badge/Google-Gemini%202.5%20Flash-blue">
<img src="https://img.shields.io/badge/Computer%20Vision-AI-success">
<img src="https://img.shields.io/badge/Civil%20Engineering-Inspection-orange">
<img src="https://img.shields.io/badge/Status-Completed-brightgreen">

---

## 🔍 AI-Powered Structural Health Assessment for Buildings & Infrastructure

*Upload a building image and receive an AI-generated structural inspection report in seconds.*

</div>

---

# 🌍 The Problem

Manual structural inspections are often:

* Time-consuming
* Expensive
* Subjective
* Dependent on expert availability
* Difficult for remote locations

This project demonstrates how **Generative AI + Computer Vision** can assist engineers by automatically analyzing structural defects from uploaded images and generating a professional inspection report.

---

# 🚀 Solution

The application uses **Google Gemini Vision AI** to inspect structural images and generate engineering recommendations.

Instead of only detecting visible defects, the system provides contextual analysis including:

* Structural damage assessment
* Severity estimation
* Risk evaluation
* Repair recommendations
* Maintenance strategy
* Estimated repair cost

---

# 🏗️ AI Inspection Workflow

```text
                     Building Image
                           │
                           ▼
                  Image Upload (Streamlit)
                           │
                           ▼
                  Google Gemini Vision
                           │
        ┌──────────────────┼──────────────────┐
        ▼                  ▼                  ▼
  Crack Detection     Damage Analysis   Severity Check
        │                  │                  │
        └──────────────────┼──────────────────┘
                           ▼
                 Engineering Assessment
                           │
                           ▼
                 Repair Recommendations
                           │
                           ▼
                  AI Inspection Report
```

---

# 📋 AI Inspection Report Includes

The AI automatically generates:

### 🧱 Structural Defect Detection

* Cracks
* Surface Damage
* Misalignment
* Structural Bending
* Visible Failure

---

### 📊 Defect Probability

Estimated probability that the detected issue is an actual structural defect.

Example

```text
Crack Probability

91%
```

---

### ⚠ Severity Classification

* 🟢 Minor
* 🟡 Moderate
* 🔴 Major

---

### 🔎 Root Cause Analysis

Possible causes include:

* Material fatigue
* Corrosion
* Moisture damage
* Environmental exposure
* Foundation settlement
* Construction defects

---

### 🔧 Repair Recommendations

AI recommends whether the defect should be:

* Repaired
* Reinforced
* Monitored
* Completely replaced

---

### 🌍 Risk Assessment

The system estimates whether the damage could affect:

* Nearby structures
* Occupant safety
* Structural stability

---

### 💰 Estimated Repair Cost

Provides an approximate repair cost range in **Indian Rupees (₹)**.

---

### 📄 Executive Summary

Generates a concise engineering report summarizing all findings and recommendations.

---

# 💻 Features

✅ Image Upload

✅ AI Vision Analysis

✅ Structural Defect Detection

✅ Severity Classification

✅ Root Cause Identification

✅ Repair Suggestions

✅ Risk Prediction

✅ Cost Estimation

✅ Maintenance Recommendations

✅ AI-Generated Summary Report

---

# 🛠 Technology Stack

| Category         | Technologies                   |
| ---------------- | ------------------------------ |
| Language         | Python                         |
| Web Framework    | Streamlit                      |
| AI Model         | Google Gemini 2.5 Flash Vision |
| Image Processing | Pillow (PIL)                   |
| Environment      | python-dotenv                  |

---

# 📂 Repository Structure

```text
AI-Structural-Defect-Analyzer
│
├── app.py
├── requirements.txt
├── .env
├── README.md
├── images/
└── sample_images/
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/AI-Structural-Defect-Analyzer.git
```

Move into the project

```bash
cd AI-Structural-Defect-Analyzer
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file

```env
GOOGLE_API_KEY=YOUR_GEMINI_API_KEY
```

Run the application

```bash
streamlit run app.py
```

---

# 📖 How to Use

### Step 1

Upload a building image (JPG, JPEG, PNG)

⬇️

### Step 2

Click **Analyze Defect**

⬇️

### Step 3

The AI generates:

* Structural Damage Report
* Defect Probability
* Severity Level
* Root Cause
* Repair Recommendation
* Risk Assessment
* Estimated Repair Cost
* Executive Summary

---

# 📸 Application Preview

```text
images/

home_page.png

upload_image.png

analysis_result.png

summary_report.png
```

*(Replace these placeholders with actual screenshots after deployment.)*

---

# 🌟 Why This Project?

Unlike traditional image classification models, this project combines **Computer Vision** with **Large Language Models** to generate detailed engineering reports instead of simple labels.

The application demonstrates how **Generative AI** can support civil engineers, inspectors, and infrastructure maintenance teams by transforming visual observations into actionable engineering insights.

---

# 🔮 Future Enhancements

* YOLO-based crack localization
* Image segmentation for defect measurement
* Multi-image inspection support
* PDF inspection report generation
* GPS & location tagging
* Drone image integration
* Bridge and road inspection
* Historical inspection comparison
* Cloud deployment
* Mobile application

---

# 👨‍💻 Developer

**Vikash Basfore**

Data Science • Machine Learning • Computer Vision • Generative AI

---

# 🙏 Acknowledgements

This project was built using:

* Google Gemini Vision AI
* Streamlit
* Pillow (PIL)
* Python-dotenv
* Python Open Source Community

Special thanks to the open-source ecosystem for enabling rapid AI application development.

---

<div align="center">

### ⭐ If you found this project useful, please consider giving it a Star!

**Building Smarter Infrastructure with AI 🏗️🤖**

</div>
