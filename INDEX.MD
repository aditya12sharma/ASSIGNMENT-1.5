Assignment 1.5 — GitHub Essentials II
Task: Upload a local project to GitHub and practice pushing updates to a remote repository.

Follow these steps on your Windows laptop to complete the assignment and obtain your public GitHub repository link.
1. Objective
To learn how to create a GitHub repository, connect it to a local Git repository, upload files using git push, and verify the commit history on GitHub.
2. Create a GitHub account and repository
1. Visit GitHub and sign in or create an account.
2. Click the + icon in the top-right corner and select New repository.
3. Enter the repository name:
   
   web-development-practice
4. Select Public.
5. Do not initialize the repository with a README, .gitignore, or license, because your local project already exists.
6. Click Create repository.
Keep the new repository page open.
3. Connect your local repository to GitHub
Open VS Code and open your existing web-development-practice project folder.

Open the terminal and run:
git remote add origin https://github.com/YOUR-USERNAME/web-development-practice.git


Replace YOUR-USERNAME with your actual GitHub username.

Verify the remote connection:
git remote -v


4. Upload your project to GitHub
Run:
git branch -M main
git push -u origin main


If GitHub asks you to authenticate, follow the sign-in instructions in your browser.

Your project files and existing commit history will now be uploaded to GitHub.
5. Add a new file and push the second commit
Create a new file named README.md in the main project folder.

Add the following content:
# Web Development Practice

This repository contains my web development practice files.

## Project Structure

- week-1: Basic HTML practice
- week-2: Git and version control practice
- week-3: Future web development practice

## Technologies Used

- HTML
- Git
- GitHub


Save the file and run:
git status
git add README.md
git commit -m "Add project README"
git push


This creates a new commit and uploads it to GitHub.
6. Verify your commit history
Open your GitHub repository in your browser.

Check that:
- The project files are visible.
- The README.md file is present.
- The repository is public.
- The commit history shows the previous commits and the new README commit.
Click the Commits link on the repository page to view the commit history.
7. Final submission
Submit your public GitHub repository link in the assignment.

Your link will look like this:

https://github.com/YOUR-USERNAME/web-development-practice

Replace YOUR-USERNAME with your actual GitHub username.

Conclusion: The local project was successfully connected to GitHub, uploaded using git push, and updated with a second commit. The repository's files and commit history were verified on GitHub.