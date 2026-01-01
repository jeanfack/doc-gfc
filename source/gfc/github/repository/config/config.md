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

# `PULL_REQUEST_TEMPLATE`

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
