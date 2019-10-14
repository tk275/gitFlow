To fetch a branch, you simply need to:

	git fetch origin

This will fetch all of the remote branches for you. With the remote branches  in hand, you now need to check out the branch you are interested in, giving  you a local working copy:

	git checkout -b test origin/test

Or

	git branch test origin/test