Learning DevOps
Author 
Md Asraful Islam Rafi
Development and Operations Engineer
The University Of Ulster,London,England

## 📁File & Directory Management

ls            # List files
ls -l         # Detailed file list
ls -a         # Show hidden files

cd foldername # Change directory
cd ..         # Go back one directory
cd ~          # Go to home directory

mkdir project # Create directory
rm file.txt   # Delete file
rm -r folder  # Delete folder (recursive)

## 📄File Commands
touch file.txt   # Create file
nano file.txt    # Open file in editor
cat file.txt     # Show file content
## 🔐File permission command
chmod +x app.py  # Make file executable
ls -l            # Check permissions

-rwxr-xr-x
r → Read
w → Write
x → Execute

## 🌿Git Commands

git init                  # Initialize repository
git status                # Check status

git add .                 # Add all files
git add app.py            # Add specific file

git commit -m "message"   # Commit changes

git log                   # View commit history
git log --oneline         # One-line history

git diff                  # Check changes
git show                  # Show commit details

git rm file.txt           # Remove tracked file

🌐 GitHub Commands

git clone URL                     # Clone repository
git remote add origin URL        # Connect remote repo

git push                         # Push code
git pull                         # Pull latest code
git pull origin main --rebase    # Pull with rebase

git push -u origin feature1      # Push new branch

git switch -c branch_name        # Create & switch branch


🐳 Docker (Nginx Server)

docker run -d -p 8081:80 nginx   # Run nginx server
docker ps                        # Check running containers

docker stop <ID>                 # Stop container
docker start <ID>                # Start container

docker exec -it <ID> sh          # Access container shell


🐳 Ubuntu Container Commands

docker run -it ubuntu bash       # Start Ubuntu container

docker ps -a                     # Show all containers
docker start <ID>                # Start container

docker exec -it <ID> bash        # Enter container











``
