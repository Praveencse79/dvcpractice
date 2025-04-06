## How to run this project?
conda create -p venv python==3.9 -y
pip install -r requirements.txt {to install the .dvc files}
git dvc
dvc add data/data.txt
git add data/data.txt.dvc
git add data/.gitignore
git status
git commit -m "dvc"
git log
dvc checkout
