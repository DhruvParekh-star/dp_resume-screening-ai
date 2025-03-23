# AI Resume Screening & Ranking System

## Overview

This is an AI-powered resume screening and ranking system built using Streamlit. The application allows recruiters to upload multiple resumes in PDF format and enter a job description. The system then preprocesses the text, extracts keywords, and calculates similarity scores between resumes and the job description to rank candidates accordingly.

## Features

- Upload multiple resumes in PDF format.
- Extract and preprocess text from resumes.
- Compute similarity scores between resumes and the job description using NLP techniques.
- Rank resumes based on relevance.
- Display an interactive recruiter dashboard with insights and data visualization.
- Extract and compare keywords between job descriptions and resumes.

## Technologies Used

- **Python**: Core programming language
- **Streamlit**: Web framework for UI
- **PyPDF2**: Extract text from PDFs
- **spaCy**: NLP processing
- **Sentence Transformers**: Model for semantic similarity
- **Matplotlib & Seaborn**: Data visualization
- **NumPy & Pandas**: Data processing and analysis

## Installation & Setup

### Prerequisites

Ensure you have Python installed (>=3.7). Then install the required dependencies:

```sh
pip install streamlit PyPDF2 pandas numpy spacy matplotlib seaborn sentence-transformers
```

### Download the SpaCy Model

```sh
python -m spacy download en_core_web_sm
```

### Run the Application

```sh
streamlit run app.py
```

## Usage

1. Open the Streamlit UI in your browser.
2. Upload multiple resume PDFs.
3. Enter the job description in the text area.
4. Click the **"Rank Resumes"** button to process and rank candidates.
5. View ranked resumes, recruiter insights, and keyword analysis.

## Future Improvements

- Support for additional file formats (e.g., DOCX, TXT).
- More advanced NLP models for better resume-job matching.
- Integration with applicant tracking systems (ATS).
- Enhanced AI explainability for deeper resume analysis.

## License

This project is open-source and available for modification and enhancement.

## Author

Dhruv Parekh

