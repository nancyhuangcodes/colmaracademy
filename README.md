# Setting up my Git Respository

1. Instructions to set up my local folder to point to Github

```BASH
echo "# colmaracademy" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nancyhuangcodes/colmaracademy.git
git remote -v
git push -u origin main

2. In the event that URL repo i sset wrongly, use the following command to set the correct url:

git remote set-url origin https://github.com/nancyhuangcodes/colmaracademy.git
git remote -v
git push


```
