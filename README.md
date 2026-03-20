# AI Resume Matcher & Job Analyzer

AI tool that compares your resume to a job description and gives a match score + basic insights.

Built with:
- Streamlit (UI)
- sentence-transformers (semantic similarity via embeddings)
- Local processing — no API keys needed

## Demo (coming soon)
Live app → [Deployed on Streamlit Cloud / Hugging Face]

## How to run locally
```bash
git clone https://github.com/karh/ai-resume-matcher.git
cd ai-resume-matcher
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
streamlit run app.py
