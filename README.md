# GitHub Tutorial

_by William Molina_

---
## Git vs. GitHub
  ### Git
  * Git is where you alter your files
  * Keeps track of different versions of your files
  * Allows you to add and commit these files to github
  * Doesn't require github
  
### Github
  * Github hosts git
  * Allows you to share your git files with others 
  * Allows you to edit others files and give suggestions
  * Requires git to work


---
## Initial Setup
###Making a github account
1. go to [github](https://www.github.com) and click sign up
2. Make an appropriate username and password
3. Click "free account"
4. Click "finish sign up"

###Linking your Github to Nitrous 
1. sign into Github
2. Click on the profile icon in the top right and click on settings
3. Click ssh keys on the left sidebar
4. Add ssh key
5. Title it "nitrous.io"
6. Go to nitrous
7. Click your username in the top right corner and go to dashboard
8. Go to the ssh keys tab
9. Copy and paste ssh key into github
10. Click add key
11. Go back to nitrous, go to the container tab in the dashboard and OPEN IDE
12. In the terminal type "ssh -T git@github.com"
13. Type "yes" to the prompt
14. Type your github username
15. Type your github password   



---
## Repository Setup
1. make a directory using ```mkdir first-repo``` and ```cd``` into it
2. type ```pwd``` and you should be in ```/home/nitrous/first-repo```
3. initialize git in first-repo
4. type (use first and last name) ```git config --global user.name “First Last”```
5. enter your email (use the same email as your github account ```git config --global user.email “username@hstat.org”```
6. make a readme file using ```touch README.md```
7. open your readme file and write soemthing in it
8. save your text
9. add your file
10. commit it to github (use a commit message that'll tell you what you last did on it)
11. go back to your github tab, click theplus sign in the top right and click "new repository"
12. Name it "first repo" (the name of your repo and directory must *ALWAYS* be the same)
13. create repository
14. There should be two boxes at the top, pick ```ssh```
15. In the second gray text box,copy each line of text into the command line one at a time
16. You can edit your README.md file
17. add and commit your file
18. type ```git push``` 
19. go to github and refresh your page




---
## Workflow & Commands
Status: Used to see of a file needs to be added or committed
Add: Add a file to the stage
Commit: Takes a screenshot of all files on the stage 
Push: Push all committed files to the cloud (github)  