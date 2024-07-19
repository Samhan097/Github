# Push Local Repository Directly to GitHub 
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

## Create a repository in GitHub same name as the local repository
Don't add readme file in your github repository if the readme file already in the local repository.
If the name of your local repository is 'Reviews' Then create a repository in github as same name with 'Reviews'. 

## Link your local repository to the GitHub repository:

Copy the URL of your GitHub repository.

In the terminal, add the remote repository using `git remote add origin <repository_url>`. Replace <repository_url> with the URL you copied.

Eg - git remote add origin https://github.com/Samhan097/Reviews.git

## error: remote origin already exists.
If this error occurs, type `git remote remove origin` and add new repository url `git remote add origin <new-repository-url>`

## Push your code to GitHub:

Finally, push your code to GitHub using `git push -u origin master` or `git push -u origin main`. You can see the branch name in the top left corner in the vscode. If you're using a different branch instead of the main, replace main with your branch name.

## Finally
then you can see your code will uploaded to your github. if you added readme file already in the your github repo then you want to compare& pull the code to github. 
