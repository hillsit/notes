
# After Creating a New Gitlab Repo
## Ref https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

git config --global user.name "John"
git config --global user.email some@email.com
git init
git remote add origin <repo url>
git pull origin master
git add .
git commit -m "Initial Checkin"
git push origin master


