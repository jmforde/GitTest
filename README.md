## Welcome to a sample Android Studio application.  

For today, your task is to create a pull request to add file in the `student_files`  
folder with your name in the title     

First, create a branch using `git branch NewBranchName` (substitute your own branch name!)  
You can check which branch you are on at any time using `git branch -v`  

Next, switch to that branch with `git checkout NewBranchName`  

Now add your new file in `student_files`     
You can create a text file with `touch student_files/your_name.txt` in git bash or  
`echo.> student_files\your_name.txt` in Windows CMD Prompt  

Next, use `git add .` to stage the file for commit  

Next, use `git commit -m "<your message here"` to commit the changes  

Finally, use `git push` to push to the repository on GitHub!  
You will probably have to use `git push --set-upstream origin JadenFordeBranch`   
to tell git where you want the branch to go...  

Now you can create a pull request to merge your changes into main  
