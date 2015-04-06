mkdir Github_KokonoHealth
cp -R Github_ChangeofMind/. Github_KokonoHealth
cd Github_KokonoHealth
mv ChangeofMind.github.io KokonoHealth.github.io
cd KokonoHealth.github.io
rm CNAME
sudo rm -r .git
git init
git status
git add .
git remote add origin https://github.com/KokonoHealth/KokonoHealth.github.io.git
git commit -am "Initial commit"
git push -u origin master
