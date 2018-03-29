hello dayah

things practiced here
1. git remote add origin https://github.com/self/projectname.git
2. git remote add upstream  https://github.com/teamleader(upstream original)/projectname.git
3. git reset HEAD~ > very dangerous. Remove the last one.
------------
4. git checkout -b newbranchname
> the new branch will have the commits from the master and then start its own commits.
> if you force push to master, it will probably mess everything up.
> if u want to push, you should git push origin newbranchname (in this way your github will have the new branch also)
