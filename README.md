**git init** - initialize empty Repo     
**vi name.txt** - Create text file    
**git add name.txt** - Add text fine to repo   
**git commit -m "Create name file"** - Commit changes to repo    

**git checkout -b feature1** - Create branch feature1   
**vi add.txt** - Create text file  
**git add add.txt** - Add address file to feature1  
**git commit -m "Create address file"** - Commit changes to feature1

**vi bio.txt** - Create text file  
**git add bio.txt** - Add biodata file to feature1  
**git commit -m "Create biodata file"** - Commit changes to feature1  

**git checkout -b feature2** - Create branch feature2  
**vi pg.txt** - Create text file  
**git add pg.txt** - Add PG Education file to feature2  
**git commit -m "Create PG Education file"** - Commit changes to feature1   

**vi ug.txt** - Create text file   
**git add bio.txt** - Add UG Education file to feature2   
**git commit -m "Create UG Education file"** - Commit changes to feature2   

**git log** - Display History of repo      
**git status** - Display state of staging     
**git reset --soft HEAD~1**  - Revert changes     
**git reset -- hard HEAD~1** - Discard local changes to previous commit    
**git checkout -d feature1** - Delete branch  

**git checkout master**  - change to master branch  
**git remote add origin <repolink>** -  
**git push origin master** - push master branch to remote git  
**git push origin feature1** - push feature1 branch to remote git  
**git push origin feature2** - push feature2 branch to remote git

**How to commit multiple line?**
**git commit -m "Create name file" -m "Add info"** 

**How to change commit Mesg**
**First we need to soft reset then make change in commit**

**How to get my code back if I do git stash**
**git stash apply**
**git stash pop**

