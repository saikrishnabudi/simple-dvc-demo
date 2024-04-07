created environment

'''bash

conda create -n wine_quality python=3.9 -y
'''

activate environment

'''bash
conda activate wine_quality
'''

created the requirement file

install the requirement file
''' bash
pip install -r requirements.txt
'''
git init

git dvc

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

git add . && git commit -m "update README.md"

git remote add origin https://github.com/saikrishnabudi/simple-dvc-demo.git

git branch -M main

git push origin main