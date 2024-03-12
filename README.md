# ATS Tracking System

## Overview
This ATS Tracking System utilizes the Gemini Pro model and Google's generative AI to analyze resumes against job descriptions. It provides insightful feedback, highlighting how well a candidate's profile aligns with the job role.

## Features
- **PDF Resume Upload**: Allows users to upload resumes in PDF format.
- **Resume Analysis**: Evaluates the resume against a provided job description.
- **Insightful Feedback**: Offers professional evaluations, emphasizing the strengths and weaknesses of the applicant.
- **Match Percentage**: Calculates how closely the resume matches the job description, identifying missing keywords and providing final thoughts.

## Technology Stack
- Python
- Streamlit
- Google Generative AI API
- pdf2image
- PIL (Python Imaging Library)

## Setup

### Prerequisites
- Python 3.10
- Pip (Python package installer)

### Installation
1. **Clone the Repository**:
   ```bash
   git clone [repository URL]

   pip install -r requirements.txt

2. **Create a .env file in the root directory of your project. Add your Google API key as follows:**:
   ```bash
   
   GOOGLE_API_KEY=your_api_key_here

**Replace your_api_key_here with your actual Google API key**

3. **To start the Streamlit application, execute:**
   ```bash
   streamlit run [your main app file].py
**Make sure to replace [your main app file].py with the path to your Streamlit application's Python file.**




## Usage

To effectively use the ATS Tracking System, follow these steps:

1. **Open the Streamlit App**:
   - Launch the Streamlit application. It should open in your default web browser.

2. **Enter Job Description**:
   - Locate the text area labeled "Job Description:" on the application interface.
   - Enter the job description details you want to evaluate the resume against.

3. **Upload Your Resume**:
   - Use the file uploader to upload your resume. Ensure the resume is in PDF format.
  
   - Once uploaded, the file name should be visible indicating successful upload.

4. **Analyze and Get Insights**:
   - Click on the button provided (e.g., "Tell Me About the Resume" or "Percentage Match") to initiate the analysis.
   - The system will process the resume and compare it against the job description.
   - Upon completion, the analysis results, including insights or a match percentage, will be displayed on the screen.
  
1. **1st Screenshot**:
  

![1](https://github.com/Akashpaul2030/LLM-model/assets/87844847/b6fe6889-89c8-41e4-b491-f8bc60f308d5)

1. **2nd Screenshot**:


![2](https://github.com/Akashpaul2030/LLM-model/assets/87844847/0db29af6-54b3-4800-945f-e45eacd7e389)
