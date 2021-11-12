# Meeting Git
Today I was introduced to Git, not to be confused with GitHub. Git is a version control system that takes snap shots of your code. This is nice because it allows you to track changes and modifications that have been made and also acts as a safety system in case a back up is need if the code is lost. The **MOST** important thing I learned from class though, was A-C-P. I wonder if a spoof song could be made for ACP using the music from Naughty By Nature's O.P.P. song... I digress
## What is ACP?
A-C-P stands for Add-Commit-Push. These three actions will allow changes in code the to be saved, stored, and sent back into GitHub so a "snapshot" of the most recent version can be taken. To do this, you'll need to follow a few steps:
1. Copy your repository (repo) url from GitHub
2. Open the terminal and locate the file you want to work in
3. Clone the repo to the file by typing `git clone url`
4. Open your code editor by typing `code .`
5. Now you're ready to work on your code!
6. To A-C-P your work, first save changes in your code editor
7. In the terminal, type `code a .` 
    + This will add all the files that have been modified
8. To commit, type `git commit -m "description"`
    + The description is where you would put a simple comment on what changes were made
9. Now you're ready to push. You do this by typing `git push origin main`
    + This will send your modified code to GitHub where the newest version can be saved and stored
10. If you want to make sure that everything ran smoothly, you can check the git status by simply typing `git status`