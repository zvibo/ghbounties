# ghbounties
playing around with bitcoin bounties on github.

This is how the fork/pull flow works:

1) create the fork on github.com: https://help.github.com/articles/fork-a-repo/

2) Do some setup/development locally:

git clone your_repo
git remote add upstream your_repo
git fetch upstream
git checkout master
work/commit, etc.
git merge upstream/master (merge the master stuff down)
git push origin master

3) create the pull request on github.com: https://help.github.com/articles/using-pull-requests/