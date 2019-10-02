# Learning GitHub
### About GitHub 
> GitHub is a place where developers store their code and multiple versions of their code in a repository (like this one). This allows developers to go back to old versions and have a backup of their code on the cloud. GitHub also has a social aspect, developers can share their code with others and can contribute to projects they like. This helps build their GitHub profile which acts like a resume of sorts, where they can show off projects and contributions to other people’s work. A lot of the world’s code is stored on GitHub including the browser you are most likely using, Google Chrome. Its source code called the Chromium project, is stored on GitHub and is accessible by anyone. 

## About Git
> Git is an open source version control tool. It allows developers to track changes in source code during software development. It’s designed for developers, whether it be large teams or just 1 person, to back up, and coordinate work. It’s a very powerful tool and is used literally everywhere there is code, including at companies such as Google, Linux, Microsoft, etc. 

## GitHub vs Git
> Git and GitHub are not the same thing. Don’t use them interchangeably. One is a version control software (Git), the other is a place where you code is stored (Github).

## Terms You'll Need To Know
* **Repo**: Repositories where your code and its versions are stored. 
* **Commits**: Various "saves" or "snapshots" of your code.
* **HEAD**: A pointer, you can change its position between commits or branches using the `git checkout` command. 
* **Gitignore**: A git file where you declare files you don’t want to track changes of. Example files: compiled or build files. 
* **README.md**: A file that describes your repository (like this file), styled using the markdown language. [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## The Command Prompt
> The command prompt is how you access Git commands which allow you to access GitHub, but first you'll need to learn the basic commands. For more information on command prompt basics [click here](https://www.online-tech-tips.com/computer-tips/how-to-use-dos-command-prompt/). For Mac and Linux users, there is something called the terminal which uses bash (most of these commands are the same besides `dir` and `explorer .`). For information on that, [click here](https://www.unr.edu/research-computing/the-grid/using-the-grid/bash-commands).

**cd (Change Directory): Change the current file directory (file system structure) you are in.**

`cd [folder name you want to navigate to]`

`cd documents`

`cd documents/my-projects/my-code`


**cd.. : Navigate to the parent directory relative to working directory. (Go back a folder)**

`cd ..`

**dir (directory): View files and folders in your working directory.** (`ls` on bash)

`dir` 

**mkdir (make directory):  Create a new folder as a child of your working directory.**

`mkdir [folder name here]`

**del: Deletes a file or a folder *contents*.**

`del [file or folder name here]`

**rmdir: Deletes a folder.**

`rmdir [folder name here]`

**explorer . : Opens working directory in file explorer.** (`open .` on bash) 

`explorer .`

## Installing Git
> To use and access Git you will have to install Git, that allows you to use the `git` command in command prompt.
[Install Git](https://git-scm.com/)


## Initializing Git
> This is what you need to do when starting up a Git repository. 

1. Navigate to where you code is using the `cd` command. 
2. Initalize a Git repository by running `git init`. 
3. Create a new Github repository [or click here](https://github.com/new). 
4. Create a README.md file with information about the repository (this can be shown to judges).
5. Add a .gitinore file like the one located in this resposiory [here](https://github.com/Envertronics/GitHub-Tutorial/blob/master/.gitignore).
6. Type `git commit -m "first commit"`. 
7. Type the git command `git remote add origin https://github.com/{your-username}/{your-repository-name}.git`. This connects your Git repository with your Github repository. 
8. Type the command `git push -u origin master`. This "pushes" to Github servers.

## Using Git
> For most your specific use case all you need to know is how to "save" or make a commit. This is going to go through that. 

1. Before you begin coding make sure to run the command `git pull` this will fetch new changes from Github. 
2. Once you make a change, stage all your files by using the command `git add .` or replace the "." with the files that you want to commit. 
3. Make a commit using the command `git commit -m "commit message here"` (Make sure to include the quotation marks, make this as concise and descriptive as possible). 
4. Last thing to do is `git push` this will "push" the code to Github's servers!

> For more information on Git, including more advanced concepts such as branches and viewing older versions of your code (using the `git checkout` comnmand), [click here](https://git-scm.com/docs). 
