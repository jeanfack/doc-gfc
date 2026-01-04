# Git Command

::::{grid}
:::{grid-item-card} Question
:::

:::{grid-item-card} Réponse
:::

:::{grid-item-card} Explication
:::

:::{grid-item-card} Source
:::
::::

## `git add`

::::{grid}
:::{grid-item-card}
Chris Griffin wants to add an existing file to his GitHub repository using the command line.\
He has already cloned the repository locally on his computer. What command should he use to stage the file for commit ?
:::

:::{grid-item-card}
`git add .`
:::

:::{grid-item-card}
Chris Griffin should use the command `git add .` to stage the file for commit in his local repository.\
This command stages all changes in the current directory for the next commit.
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository?platform=linux#adding-a-file-to-a-repository-using-the-command-line
:::
::::

::::{grid}
:::{grid-item-card}
What is the purpose of the `git add` command in the context of committing changes ?
:::

:::{grid-item-card}
It stages changes to be included in the next commit.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories?tool=cli#commit-your-first-change
:::
::::

## `git commit`

::::{grid}
:::{grid-item-card}
Chris Griffin just pushed his latest changes to GitHub but realizes that one of the commits contains a critical error.\
He wants to undo that specific commit.\
 What should Chris do to undo the mistaken commit while keeping the commit history intact ?
:::

:::{grid-item-card}
`git revert <SHA>`
:::

:::{grid-item-card}

```{note}
Commit sans push => `git commit --amend` \
Commit avec push => `git revert <SHA>`
```
:::

:::{grid-item-card}
* https://github.blog/open-source/git/how-to-undo-almost-anything-with-git/#undo-a-public-change
:::
::::

::::{grid}
:::{grid-item-card}
Chris Griffin wants to include all the changes made to tracked files in his next commit without explicitly staging them using `git add`.\
Which command should he use to achieve this ?
:::

:::{grid-item-card}
`git commit -a`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://git-scm.com/docs/git-commit/fr#git-commit-spanclasssynopsiscode-acodespan
:::
::::

::::{grid}
:::{grid-item-card}
Stewie wants to push his changes to his repository on GitHub.
How can he skip checks for an individual commit when pushing it to his GitHub repository ?
:::

:::{grid-item-card}
Add the line `skip-checks: true` after commit description, before the closing quotation, and after two empty lines.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/collaborating-on-repositories-with-code-quality-features/about-status-checks#skipping-and-requesting-checks-for-individual-commits
:::
::::

### `--message`

::::{grid}
:::{grid-item-card}
What is a recommended practice for writing a Git commit message subject line ?
:::

:::{grid-item-card}
Start with a capital letter and use the imperative, present tense.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/contribute-open-source/4-exercise-create-pr
:::
::::

::::{grid}
:::{grid-item-card}
Which of the following is **NOT** a recommended practice for writing a Git commit message ?
:::

:::{grid-item-card}
* Including a detailed explanation of the change in the subject line.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/contribute-open-source/4-exercise-create-pr
:::
::::

::::{grid}
:::{grid-item-card}
What is the recommended character limit for the subject line of a Git commit message ?
:::

:::{grid-item-card}
50 characters
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/contribute-open-source/4-exercise-create-pr
:::
::::

## `git checkout`

### Syntax

::::{grid}
:::{grid-item-card}
How can you create a new branch in Git using the terminal ?
:::

:::{grid-item-card}
`git checkout -b <branch-name>`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::

::::{grid}
:::{grid-item-card}
Stewie Griffin was working on a project when his dog unexpectedly jumped on his keyboard, causing some unintended changes to be saved in a file.\
Fortunately, he hadn't committed those changes yet.\
Now, Stewie wants to revert the file back to its state as it was in the last commit.\
Which Git command should Stewie use to accomplish this ?
:::

:::{grid-item-card}
`git checkout -- <filename>`
:::

:::{grid-item-card}
Stewie Griffin should use the `git checkout -- <filename>` command to undo the local changes in the file.\
This command reverts the file back to its state as it was in the last commit.\
By using `--` followed by the filename, Stewie instructs Git to discard the changes made to that specific file.\
:::

:::{grid-item-card}
* https://github.blog/open-source/git/how-to-undo-almost-anything-with-git/#undo-local-changes
:::
::::

### Error "Remote HEAD..."

::::{grid}
:::{grid-item-card}
How can you fix the error "Remote HEAD refers to nonexistent ref, unable to checkout" ?
:::

:::{grid-item-card}
Change the default branch of the repository on GitHub.com.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/creating-and-managing-repositories/troubleshooting-cloning-errors#error-remote-head-refers-to-nonexistent-ref-unable-to-checkout
:::
::::

## `git rm`

::::{grid}
:::{grid-item-card}
Peter Griffin wants to ignore a file that is already checked into his Git repository.\
What command should he use to untrack the file before adding a rule to ignore it ?
:::

:::{grid-item-card}
`git rm --cached <FILENAME>`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://git-scm.com/docs/git-rm#Documentation/git-rm.txt---cached
:::
::::

::::{grid}
:::{grid-item-card}
Peter Griffin accidentally added `application.log` to the Git repository. Now, every time he runs the application, Git reports unstaged changes in `application.log`. Although he added `*.log` to the `.gitignore` file, the issue persists.\
How can Peter undo tracking changes in this file ?
:::

:::{grid-item-card}
`git rm --cached application.log`
:::

:::{grid-item-card}
Peter should use the `git rm --cached <file>` command to remove `application.log` from Git's tracking without deleting it from the filesystem.\
This command updates the index to stop tracking changes in the specified file while leaving the file untouched on disk. Since it's now being ignored according to the `.gitignore` file, Git won't report unstaged changes in `application.log` anymore.

```{admonition} Example
If Peter wants to stop tracking changes in `application.log`, he would run `git rm --cached application.log`.
```
:::

:::{grid-item-card}
* https://git-scm.com/docs/git-rm#Documentation/git-rm.txt---cached
:::
::::

::::{grid}
:::{grid-item-card}
What is the process for deleting a file that was added in the most recent unpushed commit ?
:::

:::{grid-item-card}
`git rm --cached <FILE-NAME>`\
`git commit --amend -CHEAD`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://git-scm.com/docs/git-rm#Documentation/git-rm.txt---cached
* https://git-scm.com/docs/git-commit#Documentation/git-commit.txt---amend
:::
::::

## `git reset`

::::{grid}
:::{grid-item-card}
Meg Griffin has been working on a coding project and has made several commits locally.\
However, she realizes that the last three commits she made have introduced significant errors, and she wants to undo them entirely, as if they never happened.\
Which Git command should Meg use to achieve this ?
:::

:::{grid-item-card}
`git reset --hard HEAD~3`
:::

:::{grid-item-card}
Meg Griffin should use the `git reset --hard <last good SHA>` command, specifying the SHA of the commit before the first of the three commits she wants to undo.\
This command rewinds the repository's history all the way back to the specified SHA, effectively removing the last three commits and their changes entirely.\
The `--hard` option ensures that both the commit history and the working directory are reset, effectively undoing the commits and their changes in one move.
:::

:::{grid-item-card}
* https://git-scm.com/docs/git-reset/fr#git-reset-spanclasssynopsiscode--hardcodespan
:::
::::

## `git push`

### rename remote branch

::::{grid}
:::{grid-item-card}
Peter wants to rename his local branch named `feature-1` to `new-feature` on the remote repository named `origin`.\
Which Git command should he use?
:::

:::{grid-item-card}
`git push origin feature-1:new-feature`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository#renaming-branches
:::
::::

### delete remote branch

::::{grid}
:::{grid-item-card}
Meg wants to delete a branch named `feature-x` from the remote repository named `origin`.\
Which Git command should she use ?
:::

:::{grid-item-card}
`git push origin :feature-x`
:::

:::{grid-item-card}
To delete a branch from the remote repository, Meg should use the command `git push origin :feature-x`. The syntax includes a space before the colon `:`, which tells Git to push nothing into `feature-x` on the `origin` remote. This action effectively deletes the branch from the remote repository.
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository#deleting-a-remote-branch-or-tag
:::
::::

## `git filter-repo`

::::{grid}
:::{grid-item-card}
What tool can be used to remove files from a repository's history if they were added in earlier commits ?
:::

:::{grid-item-card}
**BFG Repo-Cleaner** or `git filter-repo` command.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github?platform=windows#removing-a-file-that-was-added-in-an-earlier-commit
* https://git-scm.com/docs/git-filter-branch
:::
::::

## Remove sensitive data

::::{grid}
:::{grid-item-card}
In the event that someone accidentally commits a sensitive API key that is stored in the `.secrets` folder.\
What is the appropriate method to remove that information from GitHub ?
:::

:::{grid-item-card}
Use `git` to remove the unwanted commit and update historical references.\
Then contact GitHub support to run garbage collection and invalidate the Git cache.
:::

:::{grid-item-card}
Use git to remove the unwanted commit and update historical references. Then contact GitHub support to run garbage collection and invalidate the Git cache. This approach is the correct process to remove the data moving forward. However, if you feel someone can access the key when it's available, you should replace the key with a new one. As a best practice, consider the sensitive data compromised and replace the key.

Deleting the sensitive file from GitHub and then committing an empty file to the same location to overwrite it doesn't remove the sensitive data from your commit history.
:::

:::{grid-item-card}
* https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository
:::
::::

## status

::::{grid}
:::{grid-item-card}
What does git status do in Git ?
:::

:::{grid-item-card}
Shows the state of the working tree and staging area.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::

::::{grid}
:::{grid-item-card}
Which of the following describes the primary states a file can be in within a Git repository ?\
*Choose TWO correct answers*.
:::

:::{grid-item-card}
* `Unstracked`.
* `Tracked`.
:::

:::{grid-item-card}
The primary states for a file in a Git repository are:
* `Untracked`: An initial state of a file when it isn't yet part of the Git repository. Git is unaware of its existence.
* `Tracked`: A tracked file is one that Git is actively monitoring. It can be in one of the following substates:
  - `Unmodified`: The file is tracked, but it hasn't been modified since the last commit.
  - `Modified`: The file has been changed since the last commit, but these changes aren't yet staged for the next commit.- 
  - `Staged`: The file has been modified, and the changes have been added to the staging area (also known as the index). These changes are ready to be committed.

![](../../../_include/gfc/git/command/img/lifecycle.png)
:::

:::{grid-item-card}
* https://git-scm.com/book/ms/v2/Git-Basics-Recording-Changes-to-the-Repository
* https://learn.microsoft.com/en-us/training/modules/introduction-to-github/3-components-of-github-flow
:::
::::

::::{grid}
:::{grid-item-card}
What is the name of the most recent commit on the current Git branch ?
:::

:::{grid-item-card}
`HEAD`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/intro-to-git/1-what-is-vc
:::
::::

::::{grid}
:::{grid-item-card}
By default, what is the initial branch called in a freshly created GitHub repository ?
:::

:::{grid-item-card}
`main`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches#about-the-default-branch
:::
::::

## `remote`

::::{grid}
:::{grid-item-card}
What is the purpose of a `remote` in Git?
:::

:::{grid-item-card}
* A local working directory.
* {bdg-success}`Correct` A reference to another Git repository.
* A command-line option.
* A specific commit version.
:::

:::{grid-item-card}
**Remote:**\
A remote is a named reference to another Git repository. When you create a repo, Git creates a remote named `origin` that is the default remote for push and pull operations.

In Git, a "remote" is like a nickname or reference to another Git repository. It allows you to interact with and keep track of repositories on other servers or even in different locations. Remotes are useful for collaborative work, enabling multiple developers to contribute to a shared project.

**More Details:**

1. **Named Reference:** A remote is typically given a name, often "origin" by default when you clone a repository. This name helps you refer to the remote repository in various Git commands.

2. **Default Remote:** When you create a new repository, Git often sets up a default remote named "origin." This is the remote repository from which you cloned your project.\
For example:

`$ git clone https://github.com/example/repo.git`

Here, "origin" becomes your default remote.

3. **Push and Pull Operations:** Remotes are crucial for pushing your local changes to a remote repository or pulling changes made by others into your local repository.\
For instance:

`$ git push origin main`
This command pushes changes from your local "main" branch to the "main" branch on the remote repository named "origin."

4. **Collaboration:** In team scenarios, developers can work on their local copies, make changes, and then push those changes to a common remote repository. This facilitates collaboration and ensures everyone is working on the latest version of the project.

**Examples:**

Suppose you have a repository with a remote named "origin":

* To push changes to the remote repository:\
`$ git push origin main`
* To fetch changes from the remote repository:\
`$ git pull origin main`

In these examples, "origin" is the remote, and "main" is the branch being pushed or pulled.

In summary, a remote in Git serves as a convenient link to external repositories, facilitating seamless collaboration and the exchange of changes between local and remote copies of a project.
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/git-basics/about-remote-repositories#about-remote-repositories
:::
::::

<!--
::::{grid}
:::{grid-item-card}
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::
-->
