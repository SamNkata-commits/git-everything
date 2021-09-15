# git-setup
for my git setup

• To learn how to upload your codes on GitHub.
Data: 
• None 
Steps:
1. Register a GitHub account at https://github.com/. You may want to use your email rather than JMU email if you maintain your GitHub after graduation. 
2. Create a Repository on GitHub:
2.1. Give your repository a name, like git-setup
2.2. Select public repository
2.3. Check initialize the repository with README
2.4. Choose Python in the gitignore
2.5. Choose the MIT license 
3. In the GitHub Account Settings/Developer Settings, create a Personal Access Token.
4. Create a Cloud9 project in AWS:
4.1. Log in to AWS Educate (https://aws.amazon.com/education/awse...), click Classroom, and go to the Classroom of this course. 
4.2. In the AWS Console of the Classroom, select Cloud9, create an Environment and name it IA241.
4.3. In cloud9, clone your GitHub Repository by typing the following command in the terminal:
git clone the_url_of_your_github_repository
4.4. Create a new python file in the downloaded repository, name it lab1.py. Try to print('hello world') in the lab1.py.
4.5. Use cd to go inside the downloaded repository.
4.6. Store the GitHub personal access token to the Cloud9 instance. This method stores the token into a plain text file and is not recommended in production. 
git config --global credential.helper store   
4.7. Upload the new python file to the GitHub repository by typing the following command in the terminal:
git add --all
git commit -m "write something here to explain your edit."
git push
Type your GitHub account email
Type your GitHub personal access token 
5. Go to your GitHub repository and check the changes.
