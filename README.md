# Demo for Github integration

Development information about the branch and commit for this update will appear in the linked Jira issue.

Tips for linking Jira issues during development:
* Checkout and work out of a branch that includes the Jira issue key at the beginning of the branch name. For example, `KEY-123-name-of-branch`.
* Include the issue key in the beginning of your commit messages. For example, `git commit -m "KEY-123 information about the commit"`.
* Include the issue key in the beginning of your pull request titles. For example, if you use the GitHub CLI, `gh pr create --title "KEY-123 summary of the pull request" --body "Description of the pull request"`.

You need to push *something* to the branch for GitHub to recognize and sync with Jira. Sometimes, it may take a few minutes for a "full" sync to happen. Your Jira admin can force a complete sync at any time in the **GitHub configuration** page in Jira's app settings.