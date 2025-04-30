https://docs.google.com/document/d/1AlfFgTUaj1Pr_imN9-rWooC4GL1S0Kpoox-LN85JPxw/edit?tab=t.0

https://docs.google.com/document/d/1GUM14TJ_kfZOxV9R5XSkSQPD6Ria43NMXUUB58R6O5g/edit?tab=t.0

Paired Work Collaboration Fun Time: Work with Me! 

The central reason why GitHub exists is to make collaboration between developers easier, and every innovation, feature, update has all been geared towards the knowledge that code isn’t created in a vacuum, but as part of a team. And teams work best when they work together. So let’s show off some of the ways GitHub makes collaboration easy. 

We’re going to show this one off first, and then have you in breakout rooms to try it in your own groups. Watch me and Todd show how to collaborate in GitHub. 

We’ll put you all into breakout rooms, and you’ll follow the instructions here to work together there. 
Pick one person’s repo from the last exercise to work on as a team. All Pull Requests will be made to this person’s repo.   
The person who owns the repo should add everyone else to that repo.
In the repo, click settings. 
On the left menu, click Collaborators
Click Add People towards the bottom. 
Add people by their usernames. 
Click the Add USERNAME to this repository button. 
Each user needs to accept the invitation. 

The One Change PR
All non repo owners should do the following. 

Once inside the repo, open the web editor by hitting the period key on your keyboard. 
Create a new branch
In the bottom of the web editor, click on main. 
At the top, click create new branch. 
Name the branch after your username like so: username-edits. 
All new work will be done in your branch. 
Go to the code file and add your information to the lines where the current information is. Don’t replace anything, only add. Add your name to line 1, your school to line 2, leave line 3 empty, and in line 4 add your favorite snack. 
Push these changes to the repo!
Click on the Source control button in the left vertical tabs. 
Next to Changes, click the plus sign to `add` all changes to be staged and ready to commit.
Enter a message describing what you did. “Fixed hello world” or similar message works. Imagine someone wants to know what changed in the code based on your commit message. Short, sweet, and informative. 
Click “Commit & Push”
Go back to the repo itself (I hold down the back button in the browser and find the correct page to go back to)
Hit f5 or refresh your page. 
There should be a message about a new branch. Ignore that for now since there are likely many changes. 
Go to the tab labeled Pull Requests
Click the green New Pull Request button. 
Ensure that your PR is going into main from your created branch. 
For the description, usually the rule for big PRs is to say not just what you did, but why it needed to be done. In this case, the “why?” is because it’s for a workshop, but I figure we should at least address the normal use case. 
Assign the PR to the repo owner. 
Submit the PR.
The repo owner should merge ONLY ONE of the submitted PRs. The next one will cause a Merge Conflict. 


The merge conflict
A Merge conflict is when changes are made in two separate branches to the same line in such a way that Git can’t be sure which version is the version to be kept. Normally, Git monitors all changes made to a file, but if you go to merge and Git doesn’t recognize some of the changes in the original branch (usually main), it will stop you from merging in order to preserve the correct version, whichever that may be. 

When you added names and snacks to the original file, and merged the pull request to make those changes, the main branch changed. There is another open pull request from the third member of the group that wants to merge into Main, but it doesn’t know that the main branch now has two entries per line. 

This is where things will turn into an intentional (in this exercise) merge conflict. 

Head to the other PR made against the main branch. It should be telling you that it can’t be merged. 
Instead of the Merge Pull Request button being green, it’s now grayed out. Hit the Resolve Conflicts button instead, or click “web editor”. 
Inside the next screen, The point is to change the code to look how you want it to look in the final version. Write the code so the hello world is fixed and all three collaborators names, schools, and snacks are present on separate lines. 
Click the Merge button to the right. 

Congrats! You’re now a collaborative Coder and have managed a Merge Conflict! 










