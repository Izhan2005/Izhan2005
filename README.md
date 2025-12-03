mkdir sample-python-app
cd sample-python-app
git init
echo "print('Hello GHAS')" > app.py
echo "" > requirements.txt
echo "# Sample Python App for GHAS" > README.md
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <YOUR-GITHUB-REPO-URL>
git push -u origin main
