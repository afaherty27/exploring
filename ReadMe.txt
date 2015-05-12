This read me was created through the Git shell client while learning how to use Github

To create the "HelloWorld.java" file, I ran

  git touch HelloWorld.java -->touch is a keyword for "create" and is followed by the name of the file you want to create
  
  git status -->to show if git is finding the file(s) created
  
  git add HelloWorld.java -->ques file up for commit
  
  git commit -m "Add HelloWorld.java" --> commits file change to git
  
  git remote add origin https://github.com/afaherty27/exploring --> remote refers to the origin of the file not being on computer
  
  git remote -v --> confirm changes
  
  git push --> final call to upload file to github. Final message is "everything is up to date"
  
After editing the .java file, the commands to upload the file with the changes are
  
  git add HelloWorld.java
  
  git commit -m "Add HelloWorld.java"
  
  git push
