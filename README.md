# Practice
#this a a practice file for learning gitHub

I cloned this "Practice" repository into my local machine.
Then I created a file named "practice.html" in the practice folder.
I added this file in the stagging area. _git add practice.html_
I commited this file.  _git commit -m 'practice.html'_
Now the file is present in my local version control system.
By _git push_  I pushed the file to my repository at the gitHub.
To check status , I used _git status_


If I want to push some changes to the remote repository, first I need to pull all the changes made in the remote repository into my local repository. _git pull_
After I have pulled the changes and the files are synchronized, now I can push the chnages. _git push_

We have used clone, status, add, commit, push, pull commands today.

If I made a change in file, and didn't move the new file into the stagging area (by add command), I can undo the change in the file by using _git checkout -- fileName.extension_

If I made change in more than 1 files, and didn't add in the stagging area by add command, and now I want to undo the changes, I can use _git checkout -- ._ It would undo all the changes made in all the files.

If I made a change in the file, added it to the stagging area, commited it, then the committed change can be undo by revert command   _git revert {commitID}_