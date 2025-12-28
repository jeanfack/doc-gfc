# Pull Request

::::{grid}
:::{grid-item-card}
What happens to draft pull requests in terms of merging ?
:::

:::{grid-item-card}
They cannot be merged.
:::

:::{grid-item-card}
Draft pull requests cannot be merged until they are converted to regular pull requests.
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/changing-the-stage-of-a-pull-request#converting-a-pull-request-to-a-draft
:::
::::

::::{grid}
:::{grid-item-card}
What happens if you delete a branch after its pull request has been merged into the main branch ?
:::

:::{grid-item-card}
GitHub automatically updates pull requests targeting the deleted branch.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches#working-with-branches
:::
::::

::::{grid}
:::{grid-item-card}
What option allows a contributor to receive notifications only for events they select in a pull request ?
:::

:::{grid-item-card}
Custom
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/contribute-open-source/4-exercise-create-pr
:::
::::

::::{grid}
:::{grid-item-card}
What is the purpose of linking a pull request to an issue ?
:::

:::{grid-item-card}
To show that someone is working on the issue.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue#about-linked-issues-and-pull-requests
:::
::::

::::{grid}
:::{grid-item-card}
What options are available for merging a pull request ?
:::

:::{grid-item-card}
* `Create a merge commit`,
* `Squash and merge`,
* `Rebase and merge`.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request?tool=webui#merging-a-pull-request
:::
::::

::::{grid}
:::{grid-item-card}
Which of the following accurately describes the different statuses of a pull request ?\
*Choose THREE correct answers.*
:::

:::{grid-item-card}
* `Draft`
* `Merged`
* `Closed`
:::

:::{grid-item-card}
Pull request statuses

Now let’s review the different statuses of a pull request:
* `Draft pull request` - When you create a pull request, you can choose to either create a pull request that’s ready for review or a draft pull request. A pull request with a draft status can’t be merged, and code owners aren’t automatically requested to review draft pull requests.
* `Open pull request` - An open status means the pull request is active and not yet merged to the base branch. You can still make commits and discuss and review potential changes with collaborators.
* `Closed pull request` - You can choose to close a pull request without merging it into the base/main branch. This option can be handy if the changes proposed in the branch are no longer needed, or if another solution is proposed in another branch.
* `Merged pull request` - The merged pull request status means that the updates and commits from the compare branch were combined with the base branch. Anyone with push access to the repository can complete the merge.

```{note}
This question is important for the exam, and you may see a similar question on the exam.
```
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/manage-changes-pull-requests-github/2-what-are-pull-requests
:::
::::

::::{grid}
:::{grid-item-card}
Why is deleting a branch in the GitHub flow considered a good practice ?
:::

:::{grid-item-card}
To prevent accidental use of old branches.
:::

:::{grid-item-card}
Deleting a branch in the GitHub flow signals that the work on the branch is completed. It helps prevent accidental use of old branches and keeps the repository clean.

Deleting a branch in GitHub is like cleaning up after finishing a specific task. Imagine you're done painting a room, and you no longer need the extra paint cans and brushes lying around. Deleting a branch is a bit like putting away your tools – it signals that you've completed your work on that branch, and everything is now part of the main project.

Let's say you were working on a feature branch to add a new login system to your app. After successfully merging that feature into the main project, you can safely delete the feature branch. This helps avoid confusion, ensuring you don't accidentally make changes to the old, completed work.

```{admonition} Example
You've just completed a major update to the shopping cart functionality in your e-commerce website. You've tested it thoroughly, merged it into the main project, and confirmed everything is working smoothly. Now, you delete the branch associated with this update to keep things tidy and avoid any accidental mix-ups with future work.
```

```{admonition} Use Case
Consider a scenario where you're collaborating on a project with multiple team members. If everyone keeps their feature branches after merging changes, it could lead to confusion and the possibility of accidentally using outdated code. Deleting branches helps prevent such mix-ups.
```
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/using-github/github-flow#delete-your-branch
:::
::::

::::{grid}
:::{grid-item-card}
What happens regarding code owner review when a pull request is marked as a draft ?
:::

:::{grid-item-card}
Code owners are not automatically requested to review the draft pull request.
:::

:::{grid-item-card}
Draft pull requests cannot be merged, and code owners are not automatically requested to review draft pull requests.
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests#draft-pull-requests
:::
::::

::::{grid}
:::{grid-item-card}
Peter is working on a project and has created a pull request (PR) to fix an issue.
However, the PR is on a feature branch and not the default branch.
What will happen to the special keywords in the PR description in this case ?
:::

:::{grid-item-card}
The special keywords will be ignored, and no links will be created.
:::

:::{grid-item-card}
When a PR targets a repository's default branch, special keywords in the PR description are interpreted to create links to relevant issues.\
However, if the PR's base is any other branch, the keywords are ignored, and no links are created.
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue#about-linked-issues-and-pull-requests
:::
::::

::::{grid}
:::{grid-item-card}
Peter is reviewing a pull request for a project on GitHub. He notices a section of code in one of the files that he has a question about.\
Which of the following actions can Peter take to address his question?
:::

:::{grid-item-card}
Peter can comment on specific files or sections of a file in the pull request's Files changed tab.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/commenting-on-a-pull-request#adding-comments-to-a-pull-request
:::
::::
