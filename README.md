Deploy on Day One Project

Goal: To add yourself to the student section of the FlatironSchool.com and create your profile page.
You can use the following link as a reference [students index](http://static.001.students.flatironschool.com/index.html)  
Check out different students profiles, be creative, and don't copy exactly.
Please read/skim this whole document before starting. Here's a few helpful tips...

- You'll have ~2hrs to complete this.  
- If you feel stuck, ask for help. 
- Don't get bogged down in git!
  - During this project we'd like you to become familiar with rebase, clone, pull, fetch, push but not all are required or expected.
  - Keep in mind everyone in the class will be pushing to the same repository.  Think about using a workflow with your teammates that will minimize conflicts.
- Many of you will want to know the right way to do it.
- However your team decides they want to tackle things is the right way to do it. 
- Types of questions you'll probably want to ask that we'd like you to decide with your group.
  - Should we use our own stylesheet or work within the existing styles?
  - Should we all work on one computer or each do our own and use git to manage merging our work together?
- The most important things are getting something working and learning to work as a team. There really are no wrong answers.
- Have fun with your new best friends!

Steps:  
Note: Anywhere you see "yourname" please don't literally type this, please insert your actual name
- Clone the students website to your code directory.
  - ```git clone git@github.com:flatiron-school/003.students.flatironschool.com.git```
- cd into the directory you just cloned
- Create a feature branch for your profile
  - ```git checkout -b add-profile-yourname```
- Create your profile page within the students directory and name it yourname.html
  - ```touch students/yourname.html```
  - open the html in your favorite text editor and make your profile!
- Add it, commit, push
    - ```git add .```
    - ```git commit -m "Add profile for yourname"```
    - ```git push origin localbranchname```
    - To confirm this worked you can do ```git branch -a``` which will show the remote branch on github.com you just created when you pushed
    - Note: localbranchname should be add-profile-yourname

Create a pull request to merge your feature branch
  - Go to https://github.com/flatiron-school/003.students.flatironschool.com and click on the pull request button
  - This brings you to a screen where the left side is the place you're submitting the request to (flatironschool the master branch)
  - The right side of the screen is the branch and repo you are submitting from.  So you should select your branch which will take you to the pull request screen.  Fill in some details and submit the request.  Note you can @aviflombaum in the comment of your request to automatically let avi know you submitted the pull request.

Git workflow tutorials you can check out.  Don't get bogged down in Git!

http://scottchacon.com/2011/08/31/github-flow.html

https://github.com/diaspora/diaspora/wiki/Git-Workflow

http://mettadore.com/analysis/a-simple-git-rebase-workflow-explained/

http://zachholman.com/talk/how-github-uses-github-to-build-github

https://openshift.redhat.com/community/wiki/github-workflow-for-submitting-pull-requests
