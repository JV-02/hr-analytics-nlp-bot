# Resume Samples

This folder contains sample resume files used for NLP experimentation, resume parsing, skills extraction, and chatbot testing. These files are strictly for development and demonstration purposes.

## 1. Source of Data
The resume data used in this project comes from two sources:

1. **Publicly Available Dataset (Kaggle Resume Dataset)**
   - File: `Resume.csv`
   - Contains anonymized resume text and broad job categories.
   - No personal identifying information (PII) is included.

2. **Synthetic Resumes (Optional)**
   - These are manually created or AI-generated for testing.
   - They mimic standard resume structures but do not represent real individuals.

## 2. Data Privacy & GDPR Compliance
To comply with GDPR and general privacy guidelines:

- **No real personal data (PII)** such as names, phone numbers, emails, addresses, photos, or company names are uploaded here.
- If real resumes are ever used locally, they must **not be committed to GitHub**.
- All raw resume files should remain stored **locally only**, unless anonymized.
- Only anonymized text or synthetically generated resume content should be pushed to the public repository.
- Resumes used for training or demo purposes must:
  - Not contain real identities  
  - Not contain traceable contact information  
  - Not contain confidential company details  

## 3. File Structure
data/
└── resumes/
├── Resume.csv # Anonymized Kaggle dataset (text)
├── synthetic_resume_1.txt # Example synthetic resume
├── synthetic_resume_2.txt # Optional additional samples
└── README.md # This file

## 4. Usage Guidelines
You may use these resume samples for:

- NLP preprocessing experiments
- Skills extraction pipelines
- Classification or similarity models
- Resume screening simulation
- HR assistant chatbot testing

You must **not** use this dataset for:
- Real hiring decisions  
- Identifying or tracking individuals  
- Uploading or sharing real confidential resumes  

## 5. Notes for Contributors
If you add new resume samples:

- Ensure all personally identifiable information (PII) is removed.
- Prefer synthetic or AI-generated resumes.
- Confirm that the content does not violate any copyright or confidentiality rules.
- Update this README with a short description of new files.