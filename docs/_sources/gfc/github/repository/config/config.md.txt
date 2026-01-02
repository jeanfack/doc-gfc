# Config

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

## `CODEOWNERS`

### Primary purpose

::::{grid}
:::{grid-item-card}
What is the purpose of a `CODEOWNERS` file in a GitHub repository ?
:::

:::{grid-item-card}
To assign code owners for specific files or paths.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners
:::
::::

::::{grid}
:::{grid-item-card}
How can you ensure that pull requests for a specific repository area are not merged unless approved by certain users or teams ?
:::

:::{grid-item-card}
Use a `CODEOWNERS` file and enable required reviews.
:::

:::{grid-item-card}
A `CODEOWNERS` file enables you to assign users or teams as required reviewers using the same syntax as `.gitingore` files.

`CONTRIBUTING.md` explains your contribution policy, `SECURITY.md` explains your security policy and `README.md` provides general information about your project but none of these automatically enforce anything.
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners
:::
::::

::::{grid}
:::{grid-item-card}
How can you ensure that the `CODEOWNERS` file itself is protected against unauthorized changes?
:::

:::{grid-item-card}
Define the repository owner as the owner of the `CODEOWNERS` file.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/fr/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners
:::
::::

### File location

::::{grid}
:::{grid-item-card}
Meg wants to set up code owners in her GitHub repository.\
Where should she place the `CODEOWNERS` file to ensure that it assigns the code owners for a specific branch?
:::

:::{grid-item-card}
In the `.github/`, **root**, or `docs/` directory of the repository.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners#codeowners-file-location
:::
::::

::::{grid}
:::{grid-item-card}
Meg wants to know how GitHub determines the priority when multiple `CODEOWNERS` files exist in different directories within a repository.\
Which of the following statements accurately describes the priority order used by GitHub to search for and apply `CODEOWNERS` files ?
:::

:::{grid-item-card}
GitHub will search for the `CODEOWNERS` file in the `.github/`, **root**, or `docs/` directory of the repository and use the first one it finds.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners#codeowners-file-location
:::
::::

::::{grid}
:::{grid-item-card}
Lois is managing a repository with multiple branches on GitHub, and she wants to assign different code owners for different branches.\
How can Lois assign different code owners for different branches in her repository ?
:::

:::{grid-item-card}
By specifying different code owners for different branches within the `CODEOWNERS` file for each branch.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners#codeowners-file-location
:::
::::

### Size limit


::::{grid}
:::{grid-item-card}
Peter is managing a large repository on GitHub, and he's noticed that the `CODEOWNERS` file size is exceeding the limit.\
What approach should Peter take to address this issue effectively ?
:::

:::{grid-item-card}
Peter should use wildcard patterns to consolidate multiple entries into a single entry in the `CODEOWNERS` file.
:::

:::{grid-item-card}
When the `CODEOWNERS` file exceeds the size limit of 3 MB, GitHub won't load the file, and the code owner information won't be displayed.\
To address this issue, Peter should optimize the `CODEOWNERS` file size by consolidating multiple entries into a single entry using wildcard patterns.\
This helps reduce the overall size of the file while still ensuring that the appropriate code owners are requested to review changes in pull requests.
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners#codeowners-file-size
:::
::::

### fork

::::{grid}
:::{grid-item-card}
Peter has forked a repository on GitHub and made some changes to the code.\
He's now creating a pull request to merge his changes into the base branch within his fork repository.\
Which of the following statements regarding the `CODEOWNERS` file in this scenario is true ?
:::

:::{grid-item-card}
he pull request will use the `CODEOWNERS` file from that base branch in his fork, but it won't trigger review requests unless the code owners are added to his fork with write access.
:::

:::{grid-item-card}
When creating a pull request from a forked repository, the behavior of the CODEOWNERS file depends on whether the base branch is in the upstream repository or the fork.\
If the base branch is in Peter's fork, the pull request will use the CODEOWNERS file from that branch in his fork.\
However, review requests will only be triggered if the code owners are explicitly added to Peter's fork with write access.
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners#codeowners-and-forks
:::
::::

## `ISSUE_TEMPLATE`

::::{grid}
:::{grid-item-card}
Suppose your team has been receiving some low-quality bug reports without enough information to properly diagnose.\
Which of the following choices is the best way to address the issue ?
:::

:::{grid-item-card}
Add an `ISSUE_TEMPLATE.md` file that includes fields for reproduction steps, system properties, and instructions for generating and including important logs.
:::

:::{grid-item-card}
The `ISSUE_TEMPLATE.md` file will ensure that anyone filing a bug knows what's expected of them at the moment they're writing the report.

While using a GitHub script to add a workflow action that automatically rejects any issues with a description fewer than 200 characters long may add length to the reports,
it doesn't necessarily mean that your team will receive all the information they need to find and fix bugs.

While the `CONTRIBUTING.md` file is valuable, it assumes that everyone will read and conform to it.\
Consider a better option that is more integrated with the issue creation experience.\
Hence, an issue template that includes fields for reproduction steps, system properties, and instructions for generating and including important logs is the right way to address this issue.
:::

:::{grid-item-card}
* https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates
:::
::::

::::{grid}
:::{grid-item-card}
Peter has created an issue template, as shown below, yet users are encountering difficulty locating it while raising an issue.\
What might be the plausible explanation for this ?

```{literalinclude} ../../../../_include/gfc/github/repository/config/ISSUE_TEMPLATE/E3Q31/E3Q31.yaml
:language: yaml
:lineno-match:
```
:::

:::{grid-item-card}
* The `labels` key cannot be an empty string.
* `Line:9` is not valid  `YAML` syntax. 
* The àssignees`key cannot be an empty string.
* {bdg-success}`Correct` The `about` key is missing.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates
:::
::::

::::{grid}
:::{grid-item-card}
Which of the following is a default GitHub issue template available for repositories ?\
*Choose TWO correct answers.*
:::

:::{grid-item-card}
* {bdg-success}`Correct` Feature request
* Enhancement request
* Security report
* {bdg-success}`Correct` Bug report
* Report a security vulnerability
:::

:::{grid-item-card}
GitHub provides default issue templates for **bug reports** and **feature requests** to help streamline the process of reporting issues and requesting new features in repositories.\
These templates include predefined sections such as steps to reproduce, expected behavior, actual behavior for bug reports, and a description of the proposed feature for feature requests.

Apart from **Bug report** and **Feature request** Github also has **Custom template** for other types.
:::

:::{grid-item-card}
* https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository#creating-issue-templates
:::
::::

### `ISSUE_TEMPLATE vs `**issue forms**

::::{grid}
:::{grid-item-card}
With respect to issue templates and issue forms in GitHub, which of the following statements are true ?\
*Choose TWO correct answers.*
:::

:::{grid-item-card}
* Issue forms are predefined structures for issues, while issue templates are customizable forms for capturing specific information about issues.
* Issue forms are managed through markdown files within the repository.
* Issue templates and issue forms are two terms for the same feature in GitHub, used interchangeably.
* {bdg-success}`Correct` Issue templates are predefined structures for issues, while issue forms are customizable forms for capturing specific information about issues.
* {bdg-success}`Correct` Issue forms are currently in beta and subject to change.
:::

:::{grid-item-card}
Issue templates provide predefined structures with placeholders for information that contributors should include when opening issues, such as bug reports or feature requests.
On the other hand, issue forms allow repository maintainers to create customizable forms with specific fields to capture relevant details about issues, which can be more tailored to the needs of the project.

Issue templates are managed through markdown files within the repository, where the issue form is defined as a `YAML` configuration file.

```{note}
Issue forms are currently in beta and subject to change.
```
:::

:::{grid-item-card}
* https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository
:::
::::


## `PULL_REQUEST_TEMPLATE`

::::{grid}
:::{grid-item-card}
How can pull request templates be added to a GitHub repository ?
:::

:::{grid-item-card}
By creating a `docs` folder, or a hidden `.github` directory in the repository and adding the template file.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates#pull-request-templates
:::
::::
