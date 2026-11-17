# CV-Job Matching NLP

An NLP-based system that compares a CV with a job description and returns:
- Match score
- Matched and missing skills
- CV improvement suggestions

## Methods
- Bag-of-Words + Jaccard similarity
- TF-IDF + Cosine similarity
- Hybrid TF-IDF + Skill Matching
- LSTM-style sequence similarity

## Tools
Python, NumPy, NLP, TF-IDF

## Run
```bash
pip install -r requirements.txt
python train.py
python demo_app.py
```

Then open: http://localhost:8000
