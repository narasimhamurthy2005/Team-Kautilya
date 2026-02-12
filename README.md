# Team-Kautilya

# SEFS | Semantic Entropy File System
### *Neural Intelligence Interface & Dynamic Security Engine*

**SEFS** is a next-generation file management system that transforms a static directory into a "Living Brain." By leveraging deep semantic analysis, it automatically organizes files based on context, generates AI-driven summaries, and implements a dynamic security layer for sensitive data.

---

## 🚀 Unique Features

### 🧠 Semantic Intelligence Engine
* **Contextual Clustering:** Uses **MPNet** (`all-mpnet-base-v2`) to understand the meaning of files, grouping them using **K-Means Clustering**.
* **Smart Folder Naming:** Automatically generates descriptive folder names in the OS based on cluster themes.
* **Multi-Modal OCR:** Extracts and clusters text from images (PNG, JPG) using **Tesseract OCR**.
* **AI Summarization:** Instant 2-sentence semantic insights for every file powered by **Sumy**.

### 🔒 Dynamic Security Registry
* **Right-Click Privacy:** Toggle "Locked" status on any node directly from the UI.
* **Neural Handshake:** Persistent security via `security_registry.json`. Locked files block AI summaries and OS access until the correct key is provided.
* **Visual Status:** Real-time color coding—Red for Locked (🔒), Green for Public nodes.

### 🌐 Advanced Visualization
* **Neural Flow Animation:** Moving pulses of light visualize data flow from the core to file clusters.
* **Interactive HUD:** A high-tech HUD-style sidebar displaying file paths, metadata, and AI analysis.
* **Real-Time Watcher:** The UI updates instantly as you drop or remove files from your computer.

---

## 🛠️ Technical Stack
* **Backend:** Python (Flask), Watchdog
* **AI/ML:** Sentence-Transformers (MPNet), Scikit-Learn (K-Means), Tesseract OCR, Sumy
* **Frontend:** Cytoscape.js, HTML5/CSS3 (Neon HUD Theme)
* **Database:** JSON-based Security Registry

---
## 💻 Installation & Setup

### 1. Prerequisites
* **Python 3.8+**
* **Tesseract OCR Engine:** Ensure Tesseract is installed on your machine and added to your System PATH.

## 🚀 Getting Started

Follow these steps to initialize the SEFS Neural Engine and access the interface:

### 1. Initialize the System
Open your terminal or command prompt, navigate to the project directory, and execute the main controller:
python main.py

### 2. Install Dependencies
```bash
pip install flask watchdog sentence-transformers scikit-learn PyPDF2 python-docx python-pptx sumy pytesseract opencv-python tqdm

### 3.Run the System:
pythob main.py
