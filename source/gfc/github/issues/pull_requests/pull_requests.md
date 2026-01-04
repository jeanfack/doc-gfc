# Pull Requests

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

## Primary purpose

::::{grid}
:::{grid-item-card}
What is the primary purpose of a pull request in GitHub ?
:::

:::{grid-item-card}
To request feedback on commits from collaborators.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
:::
::::

## Create/Assign

::::{grid}
:::{grid-item-card}
Who can assign issues and pull requests in a GitHub repository ?
:::

:::{grid-item-card}
Only users with write access
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/assigning-issues-and-pull-requests-to-other-github-users
:::
::::

::::{grid}
:::{grid-item-card} Question
What is **not** a valid reason to create a pull request ?
:::

:::{grid-item-card} Réponse
* {bdg-success}`Correct` Your branch can't be merged into `main` due to upstream changes made since you created it. Creating a pull request lets the other contributor know they need to pull their changes out so you can put yours in.
* You want to communicate readiness for merging into the base branch.
* You want to merge your bug fix branch into `main`, but don't have permission.
* You would like to receive feedback on prospective changes before merging your feature branch into `main`.
:::

:::{grid-item-card} Explication
Pull requests are a great way to collaborate on proposed changes. Many projects protect important branches and require changes to be reviewed via a pull request before approval.

However, creating a pull request to let the other contributor know they need to pull their changes out so you can put yours isn't how pull requests work. Also, the etiquette is for you to be sure your branch can be cleanly merged into the base before creating a pull request.
:::

:::{grid-item-card} Source
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
:::
::::

::::{grid}
:::{grid-item-card}
What is needed before you can create a pull request on GitHub ?
:::

:::{grid-item-card}
Fork a repo, clone it, commit changes, and push to your fork.
:::

:::{grid-item-card}
While you can clone any public GitHub repository, by default you don't have the right to push any modifications. Fork the repository to create your own copy first.
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/contribute-open-source/3-contribute
:::
::::

### Branch connected to an issue

::::{grid}
:::{grid-item-card}
What happens when you create a pull request for a **branch connected to an issue** ?
:::

:::{grid-item-card}
he pull request is automatically `linked` to the issue.
:::

:::{grid-item-card}
**Branches connected to an issue** are shown under the "Development" section in the sidebar of an issue.\
When you create a pull request for one of these branches, it is automatically linked to the issue.

```{note}
The ability to create a branch for an issue is currently in public beta and subject to change.
```
:::

:::{grid-item-card}
:::
::::

## Review

::::{grid}
:::{grid-item-card}
Peter Griffin has been asked to review a pull request.\
While going through it, he spots several minor coding errors and typos.\
How should he approach the review?
:::

:::{grid-item-card}
Start a review and fix obvious typos inline.\
Add comments in places that require further discussion or offer educational value.\
Complete the review with changes requested.
:::

:::{grid-item-card}
Contributors always appreciate when reviewers show an interest in getting their code merged.\
However, you should only approve a pull request when it's ready to merge.\
If the problems with a pull request are minor, it's often worth working with the contributor to fix them so the other changes can be merged.
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review
:::
::::

::::{grid}
:::{grid-item-card}
What should you do if your pull request requires some changes according to the reviewer's feedback  ?
:::

:::{grid-item-card}
Make the requested changes and push new commits to the same pull request.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/contribute-open-source/3-contribute
:::
::::

::::{grid}
:::{grid-item-card}
After reviewing the changes in a pull request on GitHub, what action can you take to collapse a file you've finished reviewing ?
:::

:::{grid-item-card}
Click the "Files changed" tab, hover over the file header, and select "Viewed".
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request#marking-a-file-as-viewed
:::
::::

## Notification

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

## File change tab

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

## Compare pages

::::{grid}
:::{grid-item-card}
What is the primary difference between the calculation of file differences on compare pages and pull request pages in GitHub ?
:::

:::{grid-item-card}
Compare pages show the diff between the tip of the head ref and the current common ancestor of the head and base ref, while pull request pages show the diff between the tip of the head ref and the common ancestor of the head and base ref at the time when the pull request was created.
:::

:::{grid-item-card}
The *compare* and *pull request pages* use different methods to calculate the diff for changed files:
* *Compare pages* show the diff between the tip of the head ref and the current common ancestor (that is, the merge base) of the head and base ref.
* *Pull request pages* show the diff between the tip of the head ref and the common ancestor of the head and base ref at the time when the pull request was created.

Consequently, the merge base used for the comparison might be different.
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests#differences-between-commits-on-compare-and-pull-request-pages
:::
::::

## Link

### Primary purpose

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

### Default branch

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
Meg wants to link a pull request to an issue using a special keyword.\
What branch should her pull request target for the keyword to be effective ?
:::

:::{grid-item-card}
The default branch.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#about-linked-issues-and-pull-requests
:::
::::

::::{grid}
:::{grid-item-card}
Lois has created a PR on the default branch of her repository to address an issue. She includes a special keyword in the PR description to link it to the issue.\
What will happen when she merges this PR ?
:::

:::{grid-item-card}
The issue linked to the PR will be closed automatically.
:::

:::{grid-item-card}
When a PR is merged and it is linked to an issue using a special keyword in the description, the linked issue will be closed automatically, assuming the PR resolves the issue.
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#about-linked-issues-and-pull-requests
:::
::::

## Permalink

::::{grid}
:::{grid-item-card}
Stewie is working on a software project hosted on GitHub and wants to share a specific line of code from a file in the project with his colleague, Meg.\
However, Stewie wants to ensure that the link he shares remains valid even if changes are made to the file in the future.\
Which of the following options should Stewie use to create a link to the specific line of code ?
:::

:::{grid-item-card}
Stewie should use the "Permalink" option provided by GitHub to create a permanent link and share it with Meg.
:::

:::{grid-item-card}
GitHub provides the option to create a permanent link to a specific line or range of lines of code in a file or pull request. This permanent link, known as a permalink, ensures that the shared link remains valid even if changes are made to the file in the future. By using the "Permalink" option, Stewie can generate a URL that directly points to the specific line of code he wants to share with Meg. This link will render as a code snippet in the original repository and as a URL in other repositories.
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-a-permanent-link-to-a-code-snippet
:::
::::

## Lifecycle

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

### `Draft`

::::{grid}
:::{grid-item-card}
What is the significance of creating a draft pull request ?
:::

:::{grid-item-card}
It allows contributors to ask for guidance or help without signaling completion.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/contribute-open-source/3-contribute
:::
::::

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
Joe Swanson is collaborating on a project on GitHub and notices that a pull request is marked as a draft.\
He wants to understand how this affects the review process.\
What is the significance of marking a pull request as a draft on GitHub ?
:::

:::{grid-item-card}
It suppresses notifications to reviewers until it's ready for review.
:::

:::{grid-item-card}
Marking a pull request as a draft on GitHub suppresses notifications to reviewers until the pull request is marked as ready for review. This allows the author to work on the changes without immediate feedback.
:::

:::{grid-item-card}
* https://github.blog/2019-02-14-introducing-draft-pull-requests/#tag-your-work-in-progress
:::
::::

::::{grid}
:::{grid-item-card}
What is a key characteristic of draft pull requests in GitHub ?
:::

:::{grid-item-card}
They cannot be merged until they are converted to regular pull requests.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests#draft-pull-requests
:::
::::

### `Open`

### `Merged`

#### Type

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

#### `Squash and merge`

::::{grid}
:::{grid-item-card}
What does the "Squash and merge" option do when merging a pull request ?
:::

:::{grid-item-card}
It combines all commits into one, helping keep the repository history readable.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/about-pull-request-merges#squash-and-merge-your-commits
:::
::::

#### Delete branch

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
When can you get rid of a branch after finishing your work ?
:::

:::{grid-item-card}
After your pull request has been merged.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches#working-with-branches
:::
::::

### Status check

::::{grid}
:::{grid-item-card}
Glenn Quagmire is a developer working on a project hosted on GitHub. he has made some changes to the codebase and created a pull request to merge your changes into the main branch. However, the status checks for his pull request are failing. He want to understand more about status checks on GitHub to troubleshoot the issue.

What are status checks on GitHub and how are they useful ?
:::

:::{grid-item-card}
They indicate if your commits meet the conditions set for the repository, such as passing continuous integration builds.
:::

:::{grid-item-card}
Status checks on GitHub are automated processes, such as continuous integration builds, that run for each push made to a repository. They inform contributors if their commits meet the conditions set for the repository, such as passing all required tests and checks. These checks help maintain code quality, prevent regressions, and ensure that the codebase remains stable.
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/collaborating-on-repositories-with-code-quality-features/about-status-checks#skipping-and-requesting-checks-for-individual-commits
:::
::::
