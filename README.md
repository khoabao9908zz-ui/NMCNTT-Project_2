# ♻️ AI Waste Classifier - Smart Waste Sorting Application

> Introduction to Information Technology Project - HCMUS

## Introduction
This application utilizes Google Gemini 1.5 Flash API combined with a Streamlit web interface to assist users in classifying waste (Organic, Inorganic, Recyclable) through photos taken directly via Webcam or uploaded from a computer.

## Key Features
- **Recognition via Camera / Image:** Capture photos directly or upload waste images to the system.
- **Automated Classification:** AI analyzes images and accurately classifies waste categories.
- **Disposal Instructions:** Suggests corresponding trash bin colors and provides safe waste disposal guidelines.

## Tech Stack & Repository Structure
- **Language:** Python 3.15.
- **Frontend / UI:** Streamlit (`WASTE_CLASSIFICATION.py`).
- **AI Model:** Google Gemini Vision API (`gemini-1.5-flash`).
- **Dataset:** `test_dataset` folder for model evaluation.

## Team Members & Contributions

1. **Le Thien Dung Huy** - Team Leader & Core UI (20%)
   - **Tasks:** Managed timeline, built Streamlit layout/tabs, and integrated all modules.
   - **Presentation (1-1.5 mins):** Introduced team/topic, student pain points, and product overview.

2. **[Tên Thành viên 2]** - Backend & PDF Data Pipeline (20%)
   - **Tasks:** Built PDF text extractor (`pypdf`), text cleaner, and Quizlet/Anki CSV exporter.
   - **Presentation (2 mins):** Explained data processing, PDF cleaning, and CSV structure.

3. **[Tên Thành viên 3]** - AI Engineer & Prompt Specialist (20%)
   - **Tasks:** Connected Gemini/Hugging Face API, designed prompts, and formatted JSON output.
   - **Presentation (2 mins):** Explained AI model, prompt engineering, and JSON error handling.

4. **Tran Duong Khoa** - Tester & Live Demo Presenter (20%)
   - **Tasks:** Tested UI/AI with real slides (C++, Math), reported bugs, and recorded demo video.
   - **Presentation (2.5 mins):** Conducted live product demo and presented AI accuracy/speed results.

5. **Luu Nhien Huy** - Documentation, Slide & Summary (20%)
   - **Tasks:** Authored Progress/Final Reports, designed slides, and created `README.md`.
   - **Presentation (2 mins):** Summarized achievements, future improvements, and hosted Q&A..

## Installation & Execution Guide

### 1. Clone the repository
```bash
git clone [https://github.com/khoabao9908zz-ui/NMCNTT-Project_2.git](https://github.com/khoabao9908zz-ui/NMCNTT-Project_2.git)
cd NMCNTT-Project_2
