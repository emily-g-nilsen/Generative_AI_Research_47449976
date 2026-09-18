# Generative AI Research

Research project on generative AI, combining a literature review, survey and interview data collection, and written outputs (proposal and report).

## Structure

- `data/interviews/` — participant interview transcripts (.docx)
- `data/survey/` — raw + processed survey CSVs, cleaning script (`survey_data_processing.py`), summary plot
- `literature_review/` — source PDFs
- `misc/` — supporting diagrams/images
- `publications/proposal/` and `publications/report/` — drafts and final submissions

## Usage

- Clone: `git clone https://github.com/emily-g-nilsen/Generative_AI_Research_47449976.git`
- Regenerate processed survey data: `cd data/survey && python survey_data_processing.py` (requires pandas)
- Interview transcripts and survey questions are `.docx` — open in Word/Docs/LibreOffice
- Don't overwrite raw data (`data/interviews/`, `*_raw_*` CSVs) or `*_submission` files — edit drafts and cleaning scripts instead

## Collaboration

Feature-branch workflow:
git checkout -b new-feature main
git add <file>
git commit -m "Describe the change"
git checkout main
git merge new-feature
git branch -d new-feature

Note: Generative AI assisted in creating this README.