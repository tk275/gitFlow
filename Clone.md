Cloning a repository

When you create a repository on GitHub, it exists as a remote repository. You can clone your repository to create a local copy on your computer and sync between the two locations.

This procedure assumes you have already created a repository on GitHub, or have an existing repository owned by someone else you'd like to contribute to.

*On GitHub, navigate to the main page of the repository.

	Note: If the repository is empty, you can manually copy the repository page's URL from your browser and skip to step four.

*Under the repository name, click Clone or download.

*To clone the repository using HTTPS, under "Clone with HTTPS", click . To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click.

*Open Git Bash.

*Change the current working directory to the location where you want the cloned directory to be made.

*Type git clone, and then paste the URL you copied in Step 2.

	$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

*Press Enter. Your local clone will be created.

