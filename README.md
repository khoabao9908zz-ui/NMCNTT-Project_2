# ♻️ AI Waste Classifier - Smart Waste Sorting Application


## Introduction
This application utilizes Google Gemini 3.8 Flash API combined with a Streamlit web interface to assist users in classifying waste (Organic, Inorganic, Recyclable) through photos taken directly via Webcam or uploaded from a computer.

## Key Features
- **Recognition via Camera / Image:** Capture photos directly or upload waste images to the system.
- **Automated Classification:** AI analyzes images and accurately classifies waste categories.
- **Disposal Instructions:** Suggests corresponding trash bin colors and provides safe waste disposal guidelines.

## Tech Stack & Repository Structure
- **Language:** Python 3.15.
- **Frontend / UI:** Streamlit (`WASTE_CLASSIFICATION.py`).
- **AI Model:** Google Gemini Vision API (`gemini-3.8-flash`).
- **Dataset:** `test_dataset` folder for model evaluation.

##  Team Members & Contribution Split (20% per member)

1. **Thien Le Dung Huy** - Team Leader & AI Lead (20%)
   - **Tasks:** Managed project timeline on GitHub, selected AI vision model, and reviewed final reports.
   - **Presentation (1.5 mins):** Introduced team/topic, project goals, and high-level architecture.

2. **Le Duy Tan** - AI & Data Engineer (20%)
   - **Tasks:** Tested and optimized image classification model, collected test datasets, and wrote image processing scripts.
   - **Presentation (2 mins):** Explained AI model selection, dataset preparation, and image prediction pipeline.

3. **Tran Nhat Nam** - Full-stack / UI Developer (20%)
   - **Tasks:** Built Streamlit web interface, integrated model backend with UI, and handled image upload/capture features.
   - **Presentation (2 mins):** Demonstrated UI design, frontend-backend integration, and real-time result rendering.

4. **Tran Duong Khoa** - Tester & Documentation Lead (20%)
   - **Tasks:** Tested app across various conditions, logged bugs, and managed GitHub `README.md`.
   - **Presentation (2.5 mins):** Conducted live app testing, evaluated accuracy/response speed, and presented test results.

5. **Luu Nhien Huy** - Design & Media Lead (20%)
   - **Tasks:** Designed presentation slides (`Slide.pdf`), produced demo videos/screenshots, and prepared Q&A script.
   - **Presentation (2 mins):** Summarized achievements, outlined future improvements, and hosted Q&A session.

## 🚀 Installation & Getting Started

### 1. Clone or Download the Project (Choose one option)

* **Option 1: Using Git (Recommended)**
  ```bash
  git clone [https://github.com/khoabao9908zz-ui/NMCNTT-Project_2.git](https://github.com/khoabao9908zz-ui/NMCNTT-Project_2.git)
  cd NMCNTT-Project_2
  ```

* **Option 2: Direct Download (For users without Git)**
  1. Click the green **Code** button at the top of this repository -> Select **Download ZIP**.
  2. Extract the downloaded `.zip` file.
  3. Open the extracted folder, click on the File Explorer address bar at the top, type `cmd`, and press **Enter** to open Command Prompt in the project directory.

---

### 2. Install Dependencies

Run the following command in your terminal or Command Prompt to install the required Python packages:

```bash
pip install streamlit google-genai pillow
```

---

### 3. Set Environment Variable & Launch Application

Replace `YOUR_API_KEY_HERE` with your actual Gemini API key before executing:

* **Windows Command Prompt (CMD):**
  ```cmd
  set VILAO_API_KEY=YOUR_API_KEY_HERE
  streamlit run WASTE_CLASSIFICATION.py
  ```

* **Windows PowerShell:**
  ```powershell
  $env:VILAO_API_KEY="YOUR_API_KEY_HERE"
  streamlit run WASTE_CLASSIFICATION.py
  ```

* **Linux / macOS / Git Bash:**
  ```bash
  export VILAO_API_KEY="YOUR_API_KEY_HERE"
  streamlit run WASTE_CLASSIFICATION.py
  ```
## Installation & Execution Guide (Windows CMD)

### 1. Clone the repository
```cmd
git clone https://github.com/khoabao9908zz-ui/NMCNTT-Project_2.git
cd NMCNTT-Project_2
```
### 2. Install required dependencies
```cmd
pip install streamlit google-genai pillow
```
### 3. Set API Key & Run Application
```cmd
set VILAO_API_KEY=sk-f60cda36048b97e53325cca24e58f122d6e34a07b6124780204a17f9f168c4f9
streamlit run WASTE_CLASSIFICATION.py
```
