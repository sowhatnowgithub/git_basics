the readme is necessary for :) \n
github/gitignore contains the all the ignoring files
```
git diff --staged , 
```
a is previous , b is what is in stagged area , + indicates old ,- indicates current , 1,3 -> indicates taken from the file and printed 1 to 2nd lines
```
git show HEAD~3:.gitignore
git ls-tree -r HEAD
git show <options from the above command results> 
git restore --staged <option>
git restore . #this is crazy it will restore every change to thee previous commit
git log --oneline
git log 
git rm <option> #this will remove from folder and staging area
git mv <old> <new> #renaming the file and updating in the staging area
git rm --cached <option> #remove from the staging area
```
#restoring to the previous commit
```
git restore --source<option,like HEAD~1> <filename>
```
