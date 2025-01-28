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
