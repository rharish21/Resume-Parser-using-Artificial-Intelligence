## AI Resume Analyzer

An AI-powered tool to analyze resumes and extract key information such as skills, experience, and education.

---

## Features

- **Resume Parsing**: Extracts key details like skills, experience, and education from resumes.
- **AI-Powered Analysis**: Uses natural language processing (NLP) to analyze and categorize resume content.
- **User-Friendly Interface**: Simple and intuitive interface for uploading and analyzing resumes.
- **Enhanced Accuracy**: Improved parsing and analysis algorithms for better results.

---

## Technologies Used

- **Python**: Core programming language.
- **Flask**: For building the web application.
- **spaCy**: For natural language processing (NLP).
- **Pandas**: For data handling and analysis.
- **Bootstrap**: For frontend design.

---

## Installation

### Prerequisites

1. **Python 3.8+**: Ensure Python is installed on your system.
2. **Git**: To clone the repository.

### Steps

1. Clone the repository: 

```bash
   git clone (https://github.com/rharish21/Resume-Parser-using-Artificial-Intelligence.git)
```
2. Navigate to the project directory:

```bash
cd AI-Resume-Analyzer
```
3. Install the required dependencies:

```bash
pip install -r requirements.txt
```
4. Download the spaCy model:

```bash
python -m spacy download en_core_web_sm
```
---

## Usage

- Start the Flask application:

```bash
python app.py
```
-Open your browser and visit:

```bash
http://localhost:5000
```
- Upload a resume (PDF or DOCX format) and click "Analyze".

- View the extracted information, including skills, experience, and education.

---

## Future Enhancements

- Multi-Language Support: Add support for resumes in multiple languages.

- AI Recommendations: Provide suggestions for improving resumes based on industry standards.

- Integration with Job Portals: Enable direct integration with job portals for automated resume submissions.

- Export Options: Allow users to export analyzed data in various formats (e.g., CSV, JSON).
