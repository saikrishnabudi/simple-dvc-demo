created environment

```bash
conda create -n wine_quality python=3.9 -y
```
activate environment

```bash
conda activate wine_quality
```
created the requirement file

install the requirement file

```bash
pip install -r requirements.txt
```
```bash
git init
```
```bash
git dvc
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add .
```
```bash
git commit -m "first commit"
```
```bash
git add . && git commit -m "update README.md"
```
```bash
git remote add origin https://github.com/saikrishnabudi/simple-dvc-demo.git
git branch -M main
git push origin main
```