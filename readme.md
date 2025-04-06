# How to run this code 
conda create -p venv python==3.9 -y
conda activate venv/
pip install -r requirements.txt
bentoml models list
bentoml serve service.py:svs --reload
pip install bentoml
bentoml --version
bentoml list 
