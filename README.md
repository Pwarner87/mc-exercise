# mc-exercise

Merge Conflicts Lab 15 guide:
1.	One member should create repo and call it mc-exercise.
2.	Assign each member a role.
3.	Add file FUBAR.md to master branch.
4.	All team members clone repo with FUBAR.md.
5.	Bob and Carol together on Carols laptop. Ted and Alice together on Teds laptop.
6.	Every team is on a different branch.
7.	Bob and Carol finish their feature and do ACP from Carols laptop also do a PR.
8.	Ted and Alice review the feature and deem it worthy to be merged and merge it.
9.	Ted and Alice do a git pull origin master to only Teds laptop and work of the feature.
10.	Bob and Carol switch to Bobs laptop, start a new branch, and start working on it. They don’t do a git pull origin master.
11.	Each team finishes at the same time and both do an ACP and a PR.
12.	Review each teams PR and attempt to merge them.
13.	Merge fails. Figure out what went wrong.
14.	Sync all laptops by doing a git pull origin master into master until Git stops complaining.
15.	Switch Partners. Bob and Alice, Ted and Carol.
16.	Bob and Alice work on Alice’s laptop while Ted and Carol work on Teds.
17.	All this work is done on master branch.
18.	Finish these features and attempt to do and ACP and merger/PR.
19.	Merge Conflicts occurs.
20.	Fix the errors, by reviewing the workflow of all group members and identify all the things they did wrong/ what they should have done.
21.	Put the answers from step 21 into the README of the repo.
22.	Switch roles and repeat steps 5-21.
23. What went wrong was both groups were working on the same branch with different information when they tried to merge. So it was trying to put 2 different lines of code within the same code. A way to remedy this would be for everyone to work on seperate branches. 
24. What we also found what went wrong was trying to commit from the same branch and different work stations. One wa sbehind the other. The way we fixed this was working on different branches.