# git-setup
For git setup for Cloud9

To learn how to upload your codes on GitHub.

Data: None

Steps:

Register a GitHub account at https://github.com/.

Create a Repository on GitHub:

Give your repository a name, like git-setup

Select public repository

Check initialize the repository with README

Choose Python in the gitignore

Choose the MIT license

In the GitHub Account Settings/Developer Settings, create a Personal Access Token.

Create a Cloud9 project in AWS:

In the AWS Console, select Cloud9, create an Environment and name it git-setup.

In cloud9, clone your GitHub Repository by typing the following command in the terminal:
git clone the_url_of_your_github_repository

Create a new python file in the downloaded repository, name it lab1.py. Try to print('hello world') in the lab1.py.

Use cd to go inside the downloaded repository.

Store the GitHub personal access token to the Cloud9 instance. This method stores the token into a plain text file and is not recommended in production.

git config --global credential.helper store

Upload the new python file to the GitHub repository by typing the following command in the terminal:

git add --all

git commit -m "write something here to explain your edit."

git push

Type your GitHub account email

Type your GitHub personal access token
 
Go to your GitHub repository and check the changes.
