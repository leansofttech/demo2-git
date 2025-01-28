# demo git 2 : Local repository to github

1- Create your folder in your computer  
2-in cmd navigate to that folder using CD  
3-enter >git init to enable the folder to be track by git  
4-add and commit files you needed  
5-How to push from local to you github  
5.1- in github create an empty repository with the same name as your local folder  
5.2-copy the url of that repository  
5.3- type > git remote add origin <your copied github repository url>  
to display the remote repository > git remote -v  
5.4- now type >git push origin master  
to avoid using "origin master" everytime you push ,
type instead >>git push -u origin master (u for upstream)

#create a feature branch and merge request

> git checkout -b <new banch or feature name> // -B will reset if the same name or new one if otherwise  
> git diff <feature name> //will compare change with the main branch  
> git merge <feature name> //to merge with local chages but if preferable to create merge request on github first  
> After git add and git commit use the following
> git push -u origin <feature name> // to push your feature change into github, -u allow to skip everything after u later.  
> On github create a merge request and assign a reviewer for the the changes you want to be merge into main branch
