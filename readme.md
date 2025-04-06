# How to run this code 
conda create -p venv python==3.9 -y
conda activate venv/
pip install -r requirements.txt
bentoml models list
bentoml serve service.py:svs --reload
pip install bentoml
bentoml --version
bentoml list 
# How to push the code?
       git init
       git remote add origin https://github.com/YourUsername/YourRepo.git
       git status              # to see changes
       git add .               # add all files
       git commit -m "your message"   # commit the changes
       git pull origin main --rebase
       git push -u origin main
