# mapd713project

npm i
npm install swagger-ui-express

npm run dev

http://localhost:5000/api-docs/

git --version     , if so ...
----- Create github localy and push to github -----
git init
git add .
git commit -m "Initial commit"

git remote add origin https://github.com/MaziarCenCol/mapd713project
git branch -M main
git push -u origin main

-------- if error ----------
git pull origin main --rebase
git add .
git rebase --continue
git push origin main
or 
git push origin main --force
=============================
-------- After any changing on codes ----------
git add .                          # Stage all changes
OR: git add file1.js file2.js
git commit -m "Updated feature X"  # Commit with a message
git pull origin main --rebase      # Pull latest changes (optional)
git push origin main               # Push changes to GitHub
================================================
