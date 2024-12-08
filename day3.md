## dec 6

1. regex expression used in C
2. ![an inspiring quote](https://blog.sciencenet.cn/blog-414166-562616.html)
3. git takes every commit as an obejects with a 40 character hash string. we can use **git log** to see every commit and use **git checkout [hashcode]** to quickly jump to other commits.
4. Git has a staging area. First use **git add ./file/** to upload the modified file to staging area and then use **git commit** command to create a snapshots of commit.
5. **git diff [hash] [filename]** command can check the differences of file compared to commitHash 
6. Head is the pointer points to one commit,which is your current working commit.
7. **git branch [name]** can fork and create another reference.
8. **git merge [one reference]** can merge a reference to master reference. 
9. Parallel programming can cause **merge conflict** ,we need to solve the conflicts by our own. We can directly vim the conflict file and make changes.And then use **git merge --contine** to do the merge.
10. **git push <remote> <local branch>:<remote branch>** 
11. **git clone <url> <folder name>**  **git clone --shallow** can only have lastest snapshot.Faster!
12. **git branch --set-upstream-to=origin/master** can initialize the default sending branch of remote repository from local machine.
13. **git pull** can fetch the updated message on remote repository and merge them into local repository.
14. .gitignore can skip some files to commit.
