# AI Resume & Cover Letter Generator

## Project Overview

AI Resume & Cover Letter Generator is an intelligent application that helps job seekers create professional resumes and personalized cover letters using Generative AI. The system collects user information such as personal details, education, skills, experience, and target job role, then generates customized documents suitable for job applications.

The project is developed using Python in Google Colab and utilizes Google's Gemini AI model to generate high-quality content.

---

## Features

* Generate professional resumes automatically
* Generate personalized cover letters
* User-friendly input interface
* AI-powered content generation
* Save generated documents as TXT or PDF
* Customizable for different job roles and industries
* Fast and accurate document creation

---

## Technologies Used

* Python
* Google Colab
* Google Generative AI (Gemini API)
* FPDF Library
* Google AI Studio API Key

---

## System Requirements

### Hardware Requirements

* Processor: Intel i3 or above
* RAM: 4 GB minimum
* Storage: 500 MB free space

### Software Requirements

* Python 3.8+
* Google Colab
* Internet Connection
* Gemini API Key

---

## Installation Steps

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/AI-Resume-CoverLetter-Generator.git
```

### Step 2: Open Google Colab

Upload the notebook or open it directly in Google Colab.

### Step 3: Install Dependencies

```python
!pip install google-generativeai
!pip install fpdf
```

### Step 4: Configure Gemini API

```python
import google.generativeai as genai

genai.configure(api_key="YOUR_API_KEY")
```

### Step 5: Run the Application

Execute all cells and provide the required information when prompted.

---

## Project Workflow

1. User enters personal information.
2. User enters skills and experience.
3. User specifies the target job role and company.
4. Gemini AI processes the input.
5. AI generates a professional resume.
6. AI generates a personalized cover letter.
7. Documents are displayed to the user.
8. Files can be downloaded as TXT or PDF.

---

## Folder Structure

```
AI-Resume-CoverLetter-Generator/
│
├── Resume_Generator.ipynb
├── Cover_Letter_Generator.ipynb
├── requirements.txt
├── README.md
├── generated_resume.pdf
├── generated_cover_letter.pdf
└── assets/
```

---

## Sample Input

Name: Harshini R Gowda

Job Role: AI Engineer

Company: ABC Technologies

Skills:
Python, Machine Learning, Deep Learning, Generative AI, Data Analysis

Experience:
Completed AI-based academic projects and internships.

---

## Sample Output

* Professional Resume
* Customized Cover Letter
* Downloadable PDF Documents

---

## Future Enhancements

* ATS Score Analysis
* Resume Ranking System
* LinkedIn Profile Integration
* Multiple Resume Templates
* Multi-language Support
* Job Recommendation System

---

## Applications

* Job Applications
* Internship Applications
* Campus Placements
* Professional Portfolio Building
* Career Development

---

## Conclusion

The AI Resume & Cover Letter Generator simplifies the job application process by automatically generating professional and personalized documents. By leveraging Generative AI, the system saves time, improves document quality, and helps candidates present themselves effectively to potential employers.

---

## Author

Harshini R Gowda

Department of Computer Science and Artificial Intelligence

Maharaja Institute of Technology Mysore

Academic Mini Project 2026
