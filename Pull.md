About pull requests

Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

About pull requests

	After initializing a pull request, you'll see a review page that shows a high-level overview of the changes between your branch (the compare branch) and the repository's base branch. You can add a summary of the proposed changes, review the changes made by commits, add labels, milestones, and assignees, and @mention individual contributors or teams. For more information, see "Creating a pull request."

	Once you've created a pull request, you can push commits from your topic branch to add them to your existing pull request. These commits will appear in chronological order within your pull request and the changes will be visible in the "Files changed" tab.

	Other contributors can review your proposed changes, add review comments, contribute to the pull request discussion, and even add commits to the pull request.

	You can see information about the branch's current deployment status and past deployment activity on the "Conversation" tab. For more information, see "Viewing deployment activity for a repository."

	After you're happy with the proposed changes, you can merge the pull request. If you're working in a shared repository model, the proposed changes will be merged from the head branch to the base branch that was specified in the pull request. For more information, see "Merging a pull request."

	If status checks are required for a repository, the required status checks must pass before you can merge your branch into the protected branch. For more information, see "About required status checks."

	You can close corresponding issues using a keyword in your pull request or commit message. For more information, see "Closing issues using keywords."

Draft pull requests

	Draft pull requests are available in public repositories with GitHub Free, GitHub Pro, and legacy per-repository billing plans, and in public and private repositories with GitHub Team and GitHub Enterprise Cloud. For more information, see "GitHub's products."

	When you create a pull request, you can choose to create a pull request that is ready for review or a draft pull request. Draft pull requests cannot be merged, and code owners are not automatically requested to review draft pull requests. For more information about creating a draft pull request, see "Creating a pull request" and "Creating a pull request from a fork."

	When you're ready to get feedback on your draft pull request, you can mark your pull request as ready for review. If the author is unavailable for any reason, anyone with write access to the repository can mark the pull request as ready for review. Then, the pull request can be merged, and code owners will be requested to review the pull request. For more information, see "Changing the stage of a pull request."