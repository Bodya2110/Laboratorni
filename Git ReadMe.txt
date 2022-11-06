…або створіть новий репозиторій у командному рядку

echo "# Laboratorni" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git branch -M main 
git remote add origin https://github.com/Bodya2110/Laboratorni.git
 git push - u походження основне

…або надішліть наявне сховище з командного рядка

git remote add origin https://github.com/Bodya2110/Laboratorni.git
 git branch -M main 
git push -u origin main

…або імпортуйте код з іншого репозиторію
Ви можете ініціалізувати це сховище за допомогою коду з проекту Subversion, Mercurial або TFS.