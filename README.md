## git configuration Part

git config --global user.name "AbidShaikh86"

git config --global user.email "abidshaikh.86@gmail.com"

## git initialization

git init 

### checking status of repository
git status

### Stage index.html and about.txt, then commit them with a meaningful commit message.
### adding file to staging area
git add index.html

git add about.txt

git commit -m "Initial first commit"

## Stage and commit notes.md separately with another meaningful commit message.
git add notes.md

git commit -m "Notes for project"

## View your commit history.
git log

## Connect your local repository to the GitHub repository.
### adding online github repo link:
git remote add origin https://github.com/AbidShaikh86/intern-portfolio.git

## Create a new branch called feature-update and switch to it.
git checkout -b feature-update
git switch -c feature-update

## Stage and commit these changes on the feature-update branch.
git add index.html
git add about.txt

git commit -m "Feature-Update 1.1" 

## Push the feature-update branch to GitHub.
git push -u origin feature-update

## Switch back to the main branch locally and confirm your changes are not present there.
git switch main

## Create another branch called feature-contact.
git checkout -b feature-contact

git switch -c feature-contact

## Add a new file, contact.txt, with sample contact details.
git add .

## Commit and push this branch to GitHub.
git commit -m "adding new feature contact"

git push -u origin feature-contact  

![alt text](<Screenshot (10).png>)
![alt text](<Screenshot (11).png>) 
![alt text](<Screenshot (12).png>) 
![alt text](<Screenshot (13).png>) 
![alt text](<Screenshot (14).png>) 
![alt text](<Screenshot (15).png>) 
![alt text](<Screenshot (16).png>) 
![alt text](<Screenshot (17).png>) 
![alt text](<Screenshot (18).png>)
![alt text](<Screenshot (19).png>) 
![alt text](<Screenshot (20).png>) 
![alt text](<Screenshot (21).png>) 
![alt text](<Screenshot (22).png>) 
![alt text](<Screenshot (23).png>) 
![alt text](<Screenshot (24).png>) 
![alt text](<Screenshot (25).png>)
