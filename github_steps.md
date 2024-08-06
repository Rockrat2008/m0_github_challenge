# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.

1. In your project folder run 'git init'
2. Create the repository on Github
- NOTE: Do NOT create a README
- Make sure to select SSH instead of HTTP
3. run the commands to link the local repository and remote repository
4. On your local machine terminal:
- git remote add origin git@github.com:USERNAME/REPO_NAME.git (you can find the username and repo_name in Github)
- git branch -M main
- git push -u origin main
- After this is done successfully you can use 'git push' for future pushes