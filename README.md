\# HR Analytics + NLP + Chatbot

\*\*Project goal:\*\* Build an end-to-end HR Analytics suite:

\- Employee attrition prediction (ML)

\- Resume screening (NLP)

\- HR chatbot integration (Rasa / FastAPI)

&nbsp; 

\## Project structure

\- `data/` - raw and processed datasets (excluded from git)

\- `notebooks/` - EDA and modeling notebooks

\- `src/` - reusable code (data, features, models)

\- `app/` - demo apps (Streamlit / FastAPI)

\- `models/` - saved model artifacts (excluded from git)

\- `reports/` - PDF and notes



\## How to run (local)

1\. Create environment: `conda env create -f environment.yml`

2\. Activate: `conda activate hr-analytics`

3\. Start Jupyter: `jupyter lab`

4\. Run Streamlit demo: `streamlit run app/streamlit\_demo.py`



\## Dataset

\- IBM HR Attrition dataset (store in `data/raw/`)

\- Resume samples (anonymized) (store in `data/resumes/`)



\## License

This project is MIT licensed — see `LICENSE`.



