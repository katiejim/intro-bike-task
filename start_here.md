# Bikeshare Task

## Setting up your coding environment
### GitHub
Create a GitHub account for yourself

Get MFA

Follow these steps to get added to EDF GitHub:
https://edfuk.atlassian.net/wiki/spaces/WMO/pages/293442385/Setting+up+GitHub+Accounts

### Python
Install Python into your machine and set up your machine for development by following the guidance in these two links: 
https://edfuk.atlassian.net/wiki/spaces/WMO/pages/293441456/Configuring+your+machine+for+VS+Code+Python+and+GitHub+development

https://edfuk.atlassian.net/wiki/spaces/WMO/pages/312358451/Installing+and+using+Python+3.9

### Git Client
Raise this MyIT request for Git: https://edfenergy.service-now.com/myit?id=sc_cat_item&sys_id=0f9cb12b1bdb7f00f875a64c2e4bcb4c

Request the TGDC version

### VSCode + Extensions
You will need the Python and Jupyter VSCode extensions to complete this task

You might also want to get GitHub Copilot access 
- Ask your team member to raise a PR to add you to GitHub copilot in EDF via a PR in the eit-env-init repo
- Install the GitHub copilot extension for VSCode
- Once your copilot access has been approved, log in to your GitHub account within VSCode

### This repo
Open Windows File explorer and create a directory path called 'SafeDownloads/Development' in your User location on the C: drive

Open a Git Bash terminal and navigate to the SafeDownloads/Development folder using "cd C:" then "cd Users/%USERPROFILE%/SafeDownloads/Development"

Clone this repository with "git clone https://github.com/katiejim/intro-bike-task.git"

Move into the cloned repository with "cd intro-bike-task"

### Virtual Envs
The Pipfile and Pipfile.lock found in this repo will help you set up your environment

When you first clone this repository, open a Git Bash terminal and run "python -m pipenv install" ; this will create a virtual environment for you to run your code within. Close the Git Bash terminal and open a new one - if you see (intro-bike-task) in brackets, the virtual environment has been created and the terminal is running inside of it

When you want to install a new package into the virtual environment, run "python -m pipenv install PACKAGE-NAME"

The package you want to install must be available in the WMS package registry

### Branches
Run the line "git checkout -b YOURNAME" to checkout a personal branch of this project

Create a new folder in this branch, and copy in the project_template_YOURNAME.ipynb file

### Committing code
Save changes to your open files (a white dot next to the file name will show it is not yet saved)

Run "git status" to see what files have been modified since the last commit

Run "git add -A" to stage all changes (or "git add FILENAME1 FILENAME2" to add specific files to the stage)

Run "git commit -m 'MESSAGE DETAILING CHANGES'" to package your staged changes into a commit

Run "git push" to push your committed changes up to the remote GitHub repository (backing the changes up online)

NOTE: the first time you push a commit on a branch up to the remote, it will error and say that no remote branch of that name exists. Run the suggested code ("git push --set-upstream origin BRANCHNAME")



