<h1>To create a folder/Repository in Github :</h1>

1) Use home terminal and config/sync with github using username and email add

git config --global user.name "Daneeja Mawren"  

git config --global user.email "daneejamawren@gmail.com"

2) Create a folder name 

mkdir resume and cd resume

3) git init

4) go into jupyter notebook and create a text file called Readme.md

5) Fill Readme.md with information and save

6) go back to terminal :

git add Readme.md

git commit -m 'new readme file'

git log 

7) go to github and create new public repository 'resume'

8) back to terminal

git remote add origin git@github.com:<your username>/resume.git
    
git branch -M main    
    
git push -u origin main 

9) to update Readme.md with more information:

git add Readme.md
    
git commit -m 'update:Readme.md'
    
git push





