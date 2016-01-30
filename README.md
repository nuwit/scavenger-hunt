# Programming Tools Scavenger Hunt Workshop

Set Up
===

1. In your terminal, cd into the folder you want this project to be in

  ```sh
  cd <parentDirectory>
  ```

2. Clone this repository (copy git url from github)

  ```sh
  git clone https://github.com/nuwit/scavenger-hunt.git
  ```

3. cd into the project

  ```sh
  cd scavenger-hunt
  ```


Your quest to the holy grail:
===
1. Create your own branch using the terminal (Hint: 'git checkout -b <yourbranchname>')
2. Remove the removeMe.txt file from the main directory using the 'rm' command in your terminal
2. **Commit** this change with git in the terminal with the commit message "First commit"
3. Open the index.html file in your browser
4. **Home page:** The nuWiT Logo in the top left hand corner is gone! Figure out how to get it back.
5. **Home page:** The 'Join Us' section is all screwed up. Find where there's a missing closing tag and fix it!
6. **Home page:** The subscribe box has turned purple! Find the corresponding styles in css/main.css and change the color back to the way it was
7. Try navigating to the **officers page** -- where did it go? Use the terminal to find where 'officers.html' has gone and put it back where it belongs. (Hint: use 'ls' and 'mv' commands)
8. **Events page:** What happened to the event list arrows? They're way too tall. Find the corresponding styles in css/main.css and fix it.
9. **Gallery page:** A container is too wide, causing the photos to be distorted and enabling horizontal scroll. Find the corresponding styles in css/main.css and fix it.
10. **Commit** your changes using the commit message "fixed some bugs"
11. Use the terminal to cd into the blog directory and make a new file by copying 'blogpost-template.html'. (Hint: use the 'cp' command). name this file YourLastName-YourFirstName.html. It will be your own blog post!
12. Add whatever message or text you want to your blog post file (with HTML)
12. Use the terminal to find the secret folder! (Hint: Use the command 'ls -as' to see hidden files). 
13. cd into the secret folder
14. Find the secret file
15. Find out what the final commit message will be by reading what's in the secret file (Use the 'more' command)
16. When you are satisfied with your changes, commit and push to your branch on github. Make sure you add the new blog post file to the files git is tracking. (git push origin YourBranchName)
17. Go the github repo on your browser and create a **pull request** to merge your branch with the master branch.
