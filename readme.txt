

GitHub information copied from Programming Assignment # 2
1) Fork the instructor's assignment repository at GitHub to you account.
2) Clone that forked copy (not the instructor original) to your local computer with the following Git command (on command line interface):
git clone url_to_your_forked_copy.git
This will create a folder in your current location with all the files like in the instructor original.
3) Edit the stubs provided in RStudio or in your text editor of choice.
4) Commit your work to version control:
git add names_of_the_edited_files_here
git commit -m "your commit message here"
5) Push your local copy to GitHub for others to see:
git push origin master
Provide your user name and password as requested.
6) Submit the URL to your repository and the SHA-1 corresponding to your chosen (usually latest) commit to Coursera according to instructions.


Some useful comments copied from discussion forums.

> So from your command line you want to make sure you are in the directory where the file is so when you enter "ls" it should look something like this:
  git remote -v

>From here you can add your changes and check your status:
 git status

>Then just commit and push (change "initial commit" to something informative about your code changes):
commit -m "initial commit"
git push


