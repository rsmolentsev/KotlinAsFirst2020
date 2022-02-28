git clone https://github.com/rsmolentsev/KotlinAsFirst2020.git  
cd KotlinAsFirst2020  
git remote add upstream-my https://github.com/rsmolentsev/KotlinAsFirst2021.git  
git fetch upstream-my  
git branch backport  
git checkout backport  
git cherry-pick d535f359...FETCH_HEAD  
git remote add upstream-theirs https://github.com/skiterskater/KotlinAsFirst2021.git  
git fetch upstream-theirs  
git checkout master  
git merge backport upstream-theirs/master  
* all conflicts solved *  
git add *  
git merge --continue  
type nul > remotes  
git remotes -v  
git add *  
git commit -m "cmmt"  
git push  
type nul > howto.md  
git add *  
git commit -m "howto added"  
git push  
