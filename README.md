# Github
In here you can create a project first in laptop after the completion of project you can push it to Github. To add your project from your laptop to GitHub, you'll need to follow these general steps:

## Create a GitHub repository:

Go to GitHub and log in to your account. 

Click on the "+" icon in the top-right corner and select "New repository".

Fill in the repository name, description, choose if it's public or private, and click "Create repository".

## Initialize your local project as a Git repository:

Open a terminal or command prompt on your laptop.

Navigate to your project directory using the cd command.

Run `git init` to initialize a Git repository in your project folder.

## Add your files to the repository:

Use `git add .` to add all files to the staging area. If you only want to add specific files, replace the dot with the file names.

Commit the changes using `git commit -m "Initial commit"`.

## Link your local repository to the GitHub repository:

Copy the URL of your GitHub repository.

In the terminal, add the remote repository using `git remote add origin <repository_url>`. Replace <repository_url> with the URL you copied.

Eg - git remote add origin https://github.com/Samhan097/Github/

## Push your code to GitHub:

Finally, push your code to GitHub using `git push -u origin main`. If you're using a different branch instead of the main, replace main with your branch name.

#React 
## To Install React in specific folder. Go to terminal and type "npx create-react-app ."
