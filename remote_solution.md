# Git Practice Assignment
<u>From</u>: Sam Arshad
<br>
<u>To</u>:  Dr. Xiaomin Lee

---

### Practice 2 : Practicing with Remote GitHub Repositories

```bash
#1. Created a Remote Repository `RemotePractice`

#Navigated to local directory
git clone https://github.com/samcursive/RemotePractice

nano notes.txt 
# added some content.
#staged
git add note.txt 
#added, relevant message and pushed.
git commit -m "Honestly I forgot the message left here for this commit. Should be in my commit history though"
git push --set-upstream origin main #set to remote origin:main 
git status
git log


git checkout -b feature-branch
nano notes.txt 
# added some content.
git add .
git commit -m "[PlaceHolder Message]"
git push --set-upstream origin feature-branch #set to remote origin:main 

# Made changes online via GitHub.
`README.md` changed on GitHub
git branch
git checkout main
git pull  #observed new changes

# Merged
git merge feature-branch main
git push
```