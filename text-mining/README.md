# README

- Install this project with
```bash
# Global env
conda env create -f environment.yml
# Wait until it finishes

conda activate env-text-mining-ort

# Install language models from spaCy
python -m spacy download en_core_web_sm
python -m spacy download es_core_news_sm

# Add it to Jupyter Lab
python -m ipykernel install --user --name=env-text-mining-ort
```