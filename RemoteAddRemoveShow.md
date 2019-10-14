Removing a remote

Use the git remote rm command to remove a remote URL from your repository.

The git remote rm command takes one argument:

	A remote name, for example, destination


Adding a remote

To add a new remote, use the git remote add command on the terminal, in the directory your repository is stored at.

The git remote add command takes two arguments:

	A remote name, for example, origin
	A remote URL, for example, https://github.com/user/repo.git


Showing Remotes

To see which remote servers you have configured, you can run the git remote command. It lists the shortnames of each remote handle you’ve specified. If you’ve cloned your repository, you should at least see origin?—?that is the default name Git gives to the server you cloned from:

	$ git clone https://github.com/schacon/ticgit
	Cloning into 'ticgit'...
	remote: Reusing existing pack: 1857, done.
	remote: Total 1857 (delta 0), reused 0 (delta 0)
	Receiving objects: 100% (1857/1857), 374.35 KiB | 268.00 KiB/s, done.
	Resolving deltas: 100% (772/772), done.
	Checking connectivity... done.

	$ cd ticgit
	$ git remote
	origin