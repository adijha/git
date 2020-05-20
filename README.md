# git
Personal git cheat Sheet

##Delete all merged local branches
``git branch | grep -v "master" | xargs git branch -D`` 

##Delete all local branches except development branch
``git branch | grep -v "development" | xargs git branch -D`` 


##clone single branch
``git clone -b branch-name --single-branch https://github.com/adijha/portfolio.git`` 
