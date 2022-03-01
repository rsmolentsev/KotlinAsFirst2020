1. git clone https://github.com/rsmolentsev/KotlinAsFirst2020.git  
2. cd KotlinAsFirst2020  
3. git remote add upstream-my https://github.com/rsmolentsev/KotlinAsFirst2021.git  
4. git fetch upstream-my  
5. git branch backport  
6. git checkout backport  
7. git cherry-pick d535f359...FETCH_HEAD  
8. git remote add upstream-theirs https://github.com/skiterskater/KotlinAsFirst2021.git  
9. git fetch upstream-theirs  
10. git checkout master  
11. git merge backport upstream-theirs/master  
/ all conflicts solved /  
12. git add *  
13. git merge --continue  
14. type nul > remotes  
15. git remote -v  
16. git add *  
17. git commit -m "cmmt"  
18. git push  
19. type nul > howto.md  
20. git add *  
21. git commit -m "howto added"  
22. git push  
