# Git Workshop

Colleen Que

Welcome to the Stevens Blueprint community! This exercise is designed to help you get comfortable with using Git and GitHub, which are important tools for software development.

This tutorial will guide you through the process of using Git to edit an HTML file. By following these steps, you will learn how to create a new branch, make changes to a file, commit those changes, and push them to a remote repository.

## Step 1: Fork the Repository

The first step is to fork the repository that contains the HTML file you want to edit. This creates a copy of the repository in your own GitHub account that you can work on without affecting the original.

To fork the repository:

1. Navigate to the repository on GitHub
2. Click the "Fork" button in the top right corner of the page
3. Select your GitHub account as the destination for the fork

## Step 2: Clone the Repository

Next, you need to clone the repository to your local machine. This creates a local copy of the repository that you can make changes to.

To clone the repository:

1. Open a terminal window
2. Navigate to the directory where you want to clone the repository
3. Run the following command:
```git clone <repository-url>```
Replace `<repository-url>` with the URL of your forked repository.

## Step 3: Create a New Branch

Before you make changes to the HTML file, you should create a new branch. This allows you to make changes without affecting the main branch of the repository.

To create a new branch:

1. Navigate to the cloned repository directory in your terminal
2. Run the following command:
```git checkout -b feature/yourName```
Replace `yourName` with your first name. So your full branch name could be ```feature/shawn```.

## Step 4: Make Changes to the HTML File

Edit the H1 tag in the index.html to be your name! Simple as that.

## Step 5: Commit and Push Your Changes

Once you have made your changes to the HTML file, you need to commit them and push them to the remote repository.

To commit and push your changes:

1. Navigate to the cloned repository directory in your terminal
2. Run the following command to stage your changes:
```git add <file-name>```
Replace `<file-name>` with the name of the HTML file you edited. You can also just use `.` instead of chooseing a specific `file-name`. This adds all changed files to be staged to commit so use it wisely. 
3. Run the following command to commit your changes:
```git commit -m "<commit-message>"```
Replace `<commit-message>` with a brief description of the changes you made. Like `added my name to the html`
4. Run the following command to push your changes to the remote repository:
```git push origin <branch-name>```
Replace `<branch-name>` with the name of the branch you created in Step 3. For example, `git push origin feature/shawn`

## Step 6: Make a pull request

1. Go to the repository on the web browser and click on the "Pull requests" tab. 
2. Click make pull request


## Conclusion

Congratulations! You have successfully used Git to edit an HTML file. This tutorial covered the basics of forking a repository, cloning the repo, creating a new branch, making changes to a file, committing those changes, and pushing them to a remote repository. When working on a project with others, it will be a slightly different and easier (IMO) experience but if you understand what's going on here you're all good. Feel free to ask any questions if you get confused. 











