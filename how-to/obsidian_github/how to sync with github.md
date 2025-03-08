1. create a repository in github
2. download git (https://git-scm.com/downloads)
3. create or generate a [[personal access token]] from github
4. install "git" in community plugins inside obsidian
5. create a folder to store the repository
6. run command (ctrl + p): `git: clone an existing remote repo`
7. paste the url of the repository/forked repository in the following format: 
```
https://<yourpersonalaccesstoken>@github.com/<githubusername>/<repositoryname>.git
```
8. type your folder name you created on step 5
9. go to git in obsidian community plugin
10. go to setting under ***commit author***, make sure ***author name for commit*** and ***author email for commit*** is filled in
11. restart obsidian
12. edit your notes
13. run command (ctrl + p): `git: commit and sync with specific message`
14. run command (ctrl + p): `git: push`