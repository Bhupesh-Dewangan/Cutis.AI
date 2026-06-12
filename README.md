# 🩺 Cutis.AI — Intelligent Skin Condition Detector
---

## Overview

**Cutis.AI** is a premium, lightweight, responsive web application powered by artificial intelligence to analyze skin images and identify potential conditions. Built with semantic HTML5, modern vanilla CSS, and clean Javascript, the frontend provides an intuitive user experience with interactive elements, real-time feedback, and dynamic layout adjustments.

Our deep learning system analyzes close-up images of skin conditions to detect anomalies and provide preliminary insights, helping users decide when to seek professional care.

---

## Preview
<img width="980" height="638" alt="Screenshot 2026-06-12 210103" src="https://github.com/user-attachments/assets/9c75168a-14ac-417c-985c-81514f098f50" />

<img width="981" height="640" alt="Screenshot 2026-06-12 210130" src="https://github.com/user-attachments/assets/3063d6dc-752d-4e0a-85b6-8090eefc9ed8" />

<img width="1047" height="673" alt="image" src="https://github.com/user-attachments/assets/2ded96f2-2123-4f9f-9cd2-a550bd8eb416" />

## Features

- 📸 **AI Skin Image Analysis**: Analyze images of skin conditions using machine learning with confidence score feedbacks.
- 🚀 **Dynamic Drag & Drop Upload**: Interactive drag-and-drop zone with real-time upload progress bar and custom visual state transitions.
- 📱 **Fully Responsive Layout**: Built-in adaptive design that scales flawlessly from mobile screens to high-resolution desktops.
- 🔍 **Condition Timeline**: Clear, interactive cards presenting information on six distinct skin conditions we detect.
- 👥 **Meet the Team & Contact**: Integrated sections showcasing the creators with social links and fully operational frontend validation for contacts.

---

## Conditions We Detect

The deep learning model behind Cutis.AI is trained to identify the following six skin conditions:

| # | Condition | Description | Category |
|---|---|---|---|
| **1** | **Melanoma** | A serious form of skin cancer; early detection from changing moles or lesions is critical for positive outcomes. | Critical / Neoplastic |
| **2** | **Atopic Dermatitis** | Eczema characterized by dry, itchy, inflamed skin—often chronic and linked to allergy-prone skin. | Inflammatory |
| **3** | **Chickenpox** | Viral illness characterized by itchy blisters; useful to distinguish from other types of skin rashes. | Infectious |
| **4** | **Nail Fungus** | Onychomycosis, which causes thickening, discoloration, or brittleness of nails—distinct from skin-only conditions. | Fungal |
| **5** | **Normal Skin** | Healthy skin profile to help the model accurately differentiate benign textures from anomalous lesions. | Healthy Base |
| **6** | **Seborrheic Keratoses** | Common benign skin growths that resemble pigmented lesions; helps reduce false-alarm rates. | Benign Growth |

---

## 📁 Repository Structure

Below is the layout of the static assets inside this repository:

```text
Cutis.AI/
├── index.html        # Main HTML structure with semantic tags and SEO-optimized meta fields
├── style.css         # Custom layout, styling, animations, and color scheme variable declarations
├── script.js        # Core Javascript logic for Drag-and-Drop, file handling, and API integration
├── README.md         # Project documentation (this file)
└── images/           # Asset directory
    ├── logo.png              # App favicon and header logo
    ├── Hero-Image.png        # Landing banner graphic
    ├── Doctors-logo.png      # Decorative badge
    ├── upload-img-icon.png   # Drop-zone iconography
    ├── skin-conditions/      # Illustrative images of the six conditions
    ├── team/                 # Headshots of the engineering team members
    └── logos/                # Social media icons (GitHub, LinkedIn, Instagram, etc.)
```

---

## ⚙️ Getting Started

To run the frontend website locally, you have two options:

### Option 1: Simple Local Opening (No Server)
Double-click the `index.html` file or drag it directly into any modern web browser. 

*Note: Since the API upload functionality relies on sending requests to `/api/predict`, you will need a local server running a proxy or mock to test the actual upload endpoint.*

### Option 2: Live Server (Recommended)
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension.
3. Click on the **Go Live** button at the bottom-right corner of the editor.
4. The site will automatically open at `http://127.0.0.1:5500`.

### Option 3: Local HTTP Server (using Python/Node)
If you prefer terminal-based local servers:
- **Python**:
  ```bash
  python -m http.server 8000
  ```
  Then navigate to `http://localhost:8000`.
- **Node (http-server)**:
  ```bash
  npx http-server -p 8080
  ```
  Then navigate to `http://localhost:8080`.

---

## 🛠️ Development & Contributions

If you would like to edit or improve Cutis.AI:

1. **Modify UI/UX**: Customize the styling variables or components in `style.css` and structure in `index.html`.
2. **Behavioral Logic**: Make edits in `script.js` to modify how files are validated, upload metrics, or UI states are managed.
3. **Assets**: Maintain visual consistency by saving any new icons or imagery into the corresponding subdirectory under `images/`.


---

## 📄 License

This repository is currently open-source. For distribution or commercial usage, adding an **MIT License** or **Apache License 2.0** file to the root of the project is recommended.
