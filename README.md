"# Web" 
/****…or create a new repository on the command line ****/
echo "# Web" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/NaveenNizam/Web.git
git push -u origin main
/****…or push an existing repository from the command line ****/
git remote add origin https://github.com/NaveenNizam/Web.git
git branch -M main
git push -u origin main

/**** update work *****/
git add .
git status
git commit -m "message "
git push
