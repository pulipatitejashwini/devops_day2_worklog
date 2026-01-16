# Git & GitHub Commands Reference

# Git Installation & Configuration
sudo apt install git         
git --version             

# Set global username and email for commits.
git config --global user.name "Your Name"             
git config --global user.email "yourmail@gmail.com"                
git config --list            

# Initialize git 
git init            

# Track Files and Commit Changes
git status                
git add                 
git commit -m "message"                 

# Connect Local Repo to GitHub
git remote add origin https://github.com/username/.git              
git remote -v                

# Push Code to GitHub
git branch -M main            
git push -u origin main       

# Branching and Merging
git branch feature1              
git branch            
git checkout feature1                   
git checkout -b feature1                    
echo "Feature work" >> file.txt                
git add .              
git commit -m "Added feature1 changes"              
git checkout main               
git merge feature1                   

# View commit history and rollback
git log          
git checkout <commit-id>                  
git checkout main              





















