# Resume Parser v0.1 (WIP)

**A developing tool for scanning and parsing resumes using NLP and regex. Currently, the application is in progress and is limited in its scanning and parsing capabilities.** 🚧

## Overview

Resume Parser v0.1 is in its initial development phase. While the application is intended to help analyze resume content by extracting contact information, skills, work experience, education, and other relevant details, its scanning and parsing features are still under active development. This means that **certain detailed extractions may not be fully supported or accurate yet**.

### Current Capabilities

- **Basic Contact Information**: Extracts common contact details, such as name, email, and phone number.
- **Preliminary Skills Identification**: Begins to recognize technical and soft skills with limited categorization.
- **Basic Section Parsing**: Detects sections like Work Experience and Education but may miss nuanced details or specific formats.
- **Export Options**: Parsed data can be saved in JSON and CSV formats, albeit with preliminary, high-level information.

### Known Limitations

- **Limited Scanning and Parsing Accuracy**: The parser's capabilities are still being expanded. It may not fully capture complex or varied resume formats.
- **Restricted ATS Compatibility Scoring**: The current scoring is basic and does not yet fully reflect real-world ATS expectations.
- **File Format Support**: Only PDF and DOCX formats are supported at this stage.

### Installation

To install and test the initial features:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/resume-parser.git
   cd resume-parser
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download NLTK Data**
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   nltk.download('averaged_perceptron_tagger')
   ```

4. **Install the SpaCy model**
   ```bash
   python -m spacy download en_core_web_sm
   ```

### Usage

1. **Run the main script**
   ```python
   python resume_parser.py
   ```

2. **Upload a PDF or DOCX file** using the widget in the UI, and view the high-level parsed results.

3. **Export Parsed Data** to JSON or CSV for additional analysis.

### Future Development

- **Enhanced Scanning Accuracy**: Improvement in identifying and extracting nuanced details within different resume formats.
- **Comprehensive ATS Compatibility Scoring**: A scoring system that better reflects Applicant Tracking System criteria.
- **Support for Additional Formats**: Plans to include more document types and expand language support.

### Contributing

If you’d like to contribute to the project, feel free to fork the repository and submit pull requests or raise issues with suggestions or bugs. Feedback and contributions are especially welcome as we build out the application's full functionality.

### License

This project is open-source and available under the [MIT License](LICENSE).

---

