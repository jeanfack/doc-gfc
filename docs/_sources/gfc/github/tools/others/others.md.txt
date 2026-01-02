# Others

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

## Github CLI

::::{grid}
:::{grid-item-card}
Which command is used to create an issue with GitHub CLI ?
:::

:::{grid-item-card}
`gh issue create`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://cli.github.com/manual/gh_issue_create
:::
::::

## GitHub Desktop

::::{grid}
:::{grid-item-card}
What actions can you perform from GitHub Desktop ?\
*Choose TWO correct answers.*
:::

:::{grid-item-card}
* {bdg-success}`Correct` Create issues or pull requests to collaborate on projects with other people.
* {bdg-success}`Correct` Create a branch of a project and push your commits to GitHub.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop
:::
::::

::::{grid}
:::{grid-item-card}
Which tool is recommended for those who prefer a visual interface and want to work with files locally ?
:::

:::{grid-item-card}
GitHub Desktop
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop
:::
::::

### Benefit

::::{grid}
:::{grid-item-card}
What benefit does GitHub Desktop offer for users new to Git and GitHub ?
:::

:::{grid-item-card}
A simplified graphical user interface.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
https://docs.github.com/en/desktop/overview/about-github-desktop#benefits-of-github-desktop
:::
::::

### GitHub Desktop vs GitHub UI

::::{grid}
:::{grid-item-card}
What is the difference between GitHub Desktop and the GitHub UI ?
:::

:::{grid-item-card}
GitHub Desktop is a standalone desktop application.
:::

:::{grid-item-card}
GitHub Desktop is a free, open source application that helps you to work with code hosted on GitHub or other Git hosting services. With GitHub Desktop, you can perform Git commands, such as committing and pushing changes, in a graphical user interface, rather than using the command line.

```{note}
GitHub UI = `github.com`
:::

:::{grid-item-card}
* https://docs.github.com/en/desktop/overview/about-github-desktop
:::
::::

## `github.dev`

### Primary purpose

::::{grid}
:::{grid-item-card}
What is the primary advantage of using the `github.dev` editor over GitHub Codespaces ?
:::

:::{grid-item-card}
Faster startup time.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/the-githubdev-web-based-editor#codespaces-and-githubdev
:::
::::

### Launch

::::{grid}
:::{grid-item-card}
How can a developer open a GitHub repository in the `github.dev` editor in a new browser tab?
:::

:::{grid-item-card}
By pressing `>` while browsing the repository on GitHub.
:::

:::{grid-item-card}
You can open any GitHub repository in github.dev in either of the following ways:
* To open the repository in the same browser tab, press `.` while browsing any repository or pull request on GitHub.
* To open the repository in a new browser tab, press `>`.
* Change the URL from `github.com` to `github.dev`.
* When viewing a file, select the dropdown menu and click `github.dev`.
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/the-githubdev-web-based-editor#opening-the-githubdev-editor
:::
::::

::::{grid}
:::{grid-item-card}
Meg's keyboard layout does not allow her to use the `.` key to open `github.dev`.\
What alternative method can she use to open a GitHub repository in `github.dev` ?
:::

:::{grid-item-card}
Change the URL from `github.com` to `github.dev`.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/the-githubdev-web-based-editor#opening-the-githubdev-editor
:::
::::

### `github.dev` vs **GitHub Codespaces**

::::{grid}
:::{grid-item-card}
Which feature is NOT available in the `github.dev` editor compared to GitHub Codespaces ?\
*Choose TWO correct answers.*
:::

:::{grid-item-card}
* {bdg-success}`Correct` Terminal access.
* {bdg-success}`Correct` Dedicated VM for running and debugging applications.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/the-githubdev-web-based-editor#codespaces-and-githubdev
:::
::::

::::{grid}
:::{grid-item-card}
Which feature is NOT available in the github.dev editor compared to GitHub Codespaces?  Choose TWO correct answers.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::


### Github repositories extension

::::{grid}
:::{grid-item-card}
What does the github.dev editor use to carry out most of its functionality ?
:::

:::{grid-item-card}
GitHub Repositories extension
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/the-githubdev-web-based-editor#about-the-githubdev-editor
:::
::::

## Troubleshooting

::::{grid}
:::{grid-item-card}
What type of window should Stewie use in his browser to open `github.dev` if he's experiencing issues ?
:::

:::{grid-item-card}
Non-incognito window
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/the-githubdev-web-based-editor#troubleshooting
:::
::::


## Graph-QL API

### Athenticate

::::{grid}
:::{grid-item-card}
How can you authenticate **GitHub CLI** commands for managing projects via the **GraphQL API** ?
:::

:::{grid-item-card}
Run `gh auth login --scopes "project"`
:::

:::{grid-item-card}
To authenticate **GitHub CLI** commands for managing projects via the **GraphQL API**, users must run `gh auth login --scopes "project"` to authenticate.\
This allows access to project-related functionalities.

If you only need to read, but not edit, projects, you can provide the `read:project` scope instead of `project`.
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/using-the-api-to-manage-projects#authenticaton
:::
::::

::::{grid}
:::{grid-item-card}
What authentication method is required before running **GitHub CLI** commands to manage projects via the **GraphQL API** ?
:::

:::{grid-item-card}
* Token authentication
:::

:::{grid-item-card}
Before running **GitHub CLI** commands to manage projects via the **GraphQL API**, you must authenticate using token authentication.
This is achieved by running `"gh auth login --scopes "project"`.
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/using-the-api-to-manage-projects#authentication
:::
::::

### Mutation

::::{grid}
:::{grid-item-card}
What is the purpose of the `addProjectV2ItemById` mutation in the GitHub **GraphQL API** ?
:::

:::{grid-item-card}
To add an issue or pull request to a project.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/graphql/reference/mutations#addprojectv2itembyid
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/using-the-api-to-manage-projects?tool=cli#adding-an-item-to-a-project
:::
::::

## GitHub Mobile

::::{grid}
:::{grid-item-card}
What is a function you can execute on **GitHub Mobile** ?
:::

:::{grid-item-card}
Manage, triage, and clear notifications from `github.com`.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/using-github/github-mobile
:::
::::

## Secret scanning

::::{grid}
:::{grid-item-card}
What does GitHub's secret scanning feature do ?
:::

:::{grid-item-card}
It looks for known secrets or credentials committed within the repository.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/code-security/secret-scanning/introduction/about-secret-scanning ?
:::
::::
