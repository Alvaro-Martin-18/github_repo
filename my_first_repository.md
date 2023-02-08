# my_first_repository

Git is a timeline, which allows you to go back in time and refer to a single porject

github backs up the timelines

if you go to a certain folder (inside git) and type "git init" you will start your tmieline
Git will also make a repository of the subfolders where you initiated the timeline

## 4 conceptual areas

- Development area

- staging area

- local repository

To initialise a repository, you first need to open git.

then cd to your folder/directory where your repository is

to make this folder a repository, type:

```
git init
```

you can check that the repository has been made by looking at it visualy in ungit

if you want to add a file from elsewhere into the repository, you do this by:

```
git add FILE1
```

this will add FILE1 into the respository made



to commit chaging the file inside, you then write 

```
git commit -m"meaningful_message"
```

here, m is an additional message which explains why there has been changes, what is expected of the changes, what has to be done after the changes....

```
git status
```

this will show the status of the repository, if the files inside have been commited, what files are inside.

this is useful to see the timeline of the project





you can make local changes into a file by "saving it"

only when you add it into the staging area (using git add) the changes will be saved into the timeline

you can "save the changes" as many times as you want, but these will only be saved as a single file - you update the file in the timeline but you do not change the timeline

only when you commit the file, the new changes will be added



if a file has not been added to the git (haven done git add FILE1), then you can save the file as many times as you want, but the changes will not be recorded in git. there will be no timeline recorded

only after you add, the changes in the file will be saved and updated in git. 





lets add this
