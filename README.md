This is a git log grahp

$ git log --graph --oneline --all
* a6b55b9 (HEAD -> master, origin/master, feature-login) Add TODO for cre
dential validation
* 5939221 Add basic login information
* 549803e Change app.js in master
* d632e7b Initial commit

This is a git reflog history

a6b55b9 (HEAD -> master, origin/master, feature-login) HEAD@{0}: merge feature-login: Fast-forward
549803e HEAD@{1}: checkout: moving from feature-login to master
a6b55b9 (HEAD -> master, origin/master, feature-login) HEAD@{2}: rebase (finish): returning to refs/heads/feature-login
a6b55b9 (HEAD -> master, origin/master, feature-login) HEAD@{3}: rebase (continue): Add TODO for credential validation
5939221 HEAD@{4}: rebase (continue): Add basic login information
549803e HEAD@{5}: rebase (start): checkout master
16630be HEAD@{6}: checkout: moving from master to feature-login
549803e HEAD@{7}: commit: Change app.js in master
d632e7b HEAD@{8}: checkout: moving from feature-login to master
16630be HEAD@{9}: commit: Add TODO for credential validation
8c61b1c HEAD@{10}: commit: Add basic login information
d632e7b HEAD@{11}: checkout: moving from master to feature-login
d632e7b HEAD@{12}: commit (initial): Initial commit
