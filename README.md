Learning DevOps
Author 
Md Asraful Islam Rafi
Development and Operations Engineer
The University Of Ulster,London,England

##Linux leaering journey

The repository contains my Linux,Git,Github and DevOps practice notes

-List files
->ls

-Details file list
->ls -l

-Hidden files show
->ls -a

-Change Directory
->cd foldername 

-Go back directory
->cd ..

-Go home directory
->cd ~

-Create directory
->mkdir project

-Remove file
->rm file.txt

-Remove folder
->rm -r foldername

##File commands


-Create file
->touch file.txt

-Open file
->nano file.txt

-Show file content
->cat file.txt

## File permission commands

-Make file executable
->chmod +x app.py

-Check file permissions
->ls -l

-Permission example
->-rwxr-xr-x

Meaning
~Read
~Write
~Execute

[Git commands I learned]

-Initialized Git
->git init

-Check Git Status
->git status

-Add all files
->git add.

-Add specific file
->git add app.py

-commit changes
->git commit -m "massage"

-Check commit history
->git.log

-One line log
->git log -oneline

-Check file changes
->git diff

-Show commit details
->git show

-Remove git tract files
->git rm file.txt

[GitHub I learned]

-Clone Repository
-> git clone REPOSITORY_LINK

-Connect GitHub Repository
->git remote add origin URL

-Push code
->git push

-Pull code
->git pull

-> git pull origin main --rebase

->for connected git with github-->git push -u origin feature1
-> new branch in git-- git switch-c branch name


##nginx server

docker run -d -p 8081:80 nginx   # new server
docker ps                        # running check
docker stop ID                   # stop
docker start ID                  # start again
docker exec -it ID sh            # inside go

##ubuntu terminal

docker run -it ubuntu bash
docker ps -a
docker start <ID>
docker exec -it <ID> bash











``
