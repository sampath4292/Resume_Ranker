AI Resume Screening & Candidate Ranking System

Live link : https://rank-resume.streamlit.app/

Overview

The AI Resume Screening & Candidate Ranking System is a Streamlit-based web application that helps recruiters automatically screen and rank resumes based on a given job description. It leverages TF-IDF vectorization and cosine similarity to evaluate and rank resumes based on their relevance to the job description.

Features

Upload multiple resumes in PDF format.

Input a job description.

Extracts text from resumes using PyPDF2.

Calculates cosine similarity between the job description and resumes.

Ranks resumes based on their relevance to the job description.

Displays the ranking results in a structured table.

Technologies Used

Python

Streamlit (for building the web application)

PyPDF2 (for extracting text from PDFs)

pandas (for handling data)

scikit-learn (for text processing and similarity computation)

Installation

To run this project locally, follow these steps:

Prerequisites

Ensure you have Python 3.x installed on your system.

Steps

Clone the repository:

git clone https://github.com/your-username/resume-screening.git
cd resume-screening

Create a virtual environment (optional but recommended):

python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app.py

Usage

Open the application in your browser.

Enter the job description in the provided text area.

Upload one or more resumes in PDF format.

Click to process and view the ranked results.

Example Output

Resume Name

Score

Resume_1.pdf

0.85

Resume_2.pdf

0.78

Resume_3.pdf

0.65

Future Enhancements

Improve text extraction for complex PDF formats.

Support additional file formats (e.g., DOCX, TXT).

Implement more advanced NLP techniques (e.g., BERT-based similarity).

Add visualizations for ranking results.
