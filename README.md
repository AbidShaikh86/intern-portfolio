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

<img width="463" height="205" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/b5aa19ea-1b0f-4982-8330-4a8a11ead5c1" />

<img width="487" height="388" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/ca150d25-4be1-49a4-b6d4-cc36719f368a" />

<img width="716" height="322" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/c7cb7cae-a7d8-48da-a200-d1b7c4be4e3e" />

<img width="953" height="406" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/e0992b71-e86f-4e38-91ae-1ddb4e267134" />

<img width="937" height="387" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/37bbe9b5-1233-4876-b21c-d42460d54313" />

<img width="924" height="516" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/e7b6c3bc-beeb-4021-b0f6-72f2de3bdd69" />

<img width="890" height="183" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/cef11c09-13d0-446f-a97e-297bc4adb4b0" />

<img width="901" height="401" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/ed5f19d6-a41d-4023-b14b-4d253a427cef" />

<img width="887" height="123" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/c9e6d5ea-4132-404c-9249-7d14b6b13cd5" />

<img width="630" height="447" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/cdc28dbe-aaa9-4dd1-86fb-863e21fb13f8" />

<img width="946" height="377" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/5e413dd1-8183-43eb-9d1f-fd682c8ea11c" />

