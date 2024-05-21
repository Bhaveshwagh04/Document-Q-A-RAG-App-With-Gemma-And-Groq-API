# Document-Q-A-RAG-App-With-Gemma-And-Groq-API

How to run?

STEPS:
Clone the repository
Project repo: https://github.com/


STEP 01- Create a conda environment after opening the repository

```bash
conda create -n gemma python=3.12 -y
```

```bash
conda activate gemma
```
STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

Create a .env file in the root directory and add your GOOGLE_API_KEY And GROQ_API_KEY credentials as follows:

```bash
GROQ_API_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
```bash
# Finally run the following command
streamlit run app.py
```
Techstack Used:

- python
- Google API
- Streamlit
- GROQ
- FAISS-CPU
- Langchain
- PyPDF2
- pypdf




