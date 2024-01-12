### what is version control

Version control, also known as source control or revision control, is a system that manages changes to a project's codebase, documents, and other files over time. The primary goal of version control is to track and coordinate changes made by multiple contributors to a software project. This ensures a collaborative and organized development process while providing the ability to revert to previous states if needed.

### Explain difference between git and github

What is the difference between Git and GitHub?
what's the difference? Simply put, Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then GitHub is designed to help you better manage them.

There are several alternatives to GitHub, each with its own features and advantages. Here are three popular alternatives:

- GitLab:

Website: GitLab
Key Features:
Offers both cloud-hosted and self-hosted solutions.
Provides integrated CI/CD capabilities.
Includes built-in issue tracking, code review, and project management features.
Offers a robust free tier and additional features in paid plans.
Supports groups and subgroups for organizing projects.

- Bitbucket:

 Website: Bitbucket
Key Features:
Owned by Atlassian and integrates well with Jira and other Atlassian products.
Supports both Git and Mercurial repositories.
Offers free private repositories for small teams.
Provides built-in CI/CD capabilities.
Includes features for code collaboration, pull requests, and issue tracking.

- SourceForge:

 Website: SourceForge
Key Features:
One of the oldest version control and collaboration platforms.
Supports Git, Mercurial, Subversion, and others.
Provides tools for project hosting, bug tracking, and forums.
Offers features for collaboration on open-source projects.
Allows both cloud-hosted and self-hosted options.

## List 3 other github alternatives


These alternatives cater to different needs, and the choice between them often depends on factors such as project requirements, team preferences, and specific features offered by each platform. Additionally, some organizations choose to self-host Git repositories using solutions like Gitolite or Gitea for greater control over infrastructure and security.

## Explain the difference between git fetch and git pull

The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both.

## Explain in simple terms git rebase and the command for it

The git rebase command allows you to easily change a series of commits, modifying the history of your repository. You can reorder, edit, or squash commits together. Typically, you would use git rebase to: Edit previous commit messages.

## Explain in simple terms git cherry-pick and the command for it 

git cherry-pick in git means choosing a commit from one branch and applying it to another branch. This is in contrast with other ways such as merge and rebases which normally apply many commits into another branch. git cherry-pick is just like rebasing, an advanced concept and also a powerful command.

- In simple terms, git cherry-pick is a Git command that allows you to copy a specific commit from one branch and apply it onto another branch. It's like picking a commit from one branch and placing it onto another branch.
