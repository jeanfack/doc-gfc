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

## GitHub CLI

### Syntax

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

::::{grid}
:::{grid-item-card}
What command is used to create a new repository using GitHub CLI ?
:::

:::{grid-item-card}
`gh repo create`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories?tool=cli#create-a-repository
:::
::::

## GitHub API

::::{grid}
:::{grid-item-card}
What is GitHub API primarily used for ?
:::

:::{grid-item-card}
Automating common tasks and creating integrations.
:::

:::{grid-item-card}
GitHub API allows users to interact with GitHub programmatically. It's commonly used to automate repetitive tasks, create custom integrations, or build tools that extend GitHub's functionality.

For example, you can use the API to automate the creation of an issue when specific conditions are met or to fetch data for reporting purposes.
:::

:::{grid-item-card}
* https://docs.github.com/en/rest/about-the-rest-api/about-the-rest-api
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

::::{grid}
:::{grid-item-card}
What is an advantage of working from the desktop compared to working in the browser in terms of Github ?
:::

:::{grid-item-card}
Access to compute power.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/start-your-journey/about-github-and-git
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
What is the difference between **GitHub Desktop** and the **GitHub UI** ?
:::

:::{grid-item-card}
**GitHub Desktop** is a standalone desktop application.
:::

:::{grid-item-card}
**GitHub Desktop** is a free, open source application that helps you to work with code hosted on GitHub or other Git hosting services.\
With **GitHub Desktop**, you can perform Git commands, such as committing and pushing changes, in a graphical user interface, rather than using the command line.

```{note}
GitHub UI = `github.com`
```
:::

:::{grid-item-card}
* https://docs.github.com/en/desktop/overview/about-github-desktop
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


# default label
[](https://docs.github.com/en/enterprise-server@3.10/issues/using-labels-and-milestones-to-track-work/managing-labels#about-default-labels)

* bug
* documentation
* duplicate
* enhancement
* good first issue
* help wanted
* invalid
* question
* wontfix

# defaukt category discussions
[](https://docs.github.com/en/discussions/managing-discussions-for-your-community/managing-categories-for-discussions#default-categories)

- Announcements
- General
- Ideas
- Polls
- Q&A
- Show and tell

# default workflows
- Item added to project
- Item reopened
- Item closed
- Code changes requested
- Code review approved
- Pull request merged
- Auto-archive items
- Auto-add to project


# slash commands
https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/about-slash-commands#using-slash-commands

- `/code`
- `/details`
- `/save-replies`
- `/table`
- `/template`

# repository roles
https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-repository-roles/repository-roles-for-an-organization#permissions-for-each-role

- read
- write
- triage
- maintain
- admin

# repository visibility
- public
- private
- intern

# type of website:
- project
- user
- organization

# GitHub Actions workflow components
- jobs
- actions
- runners

# Which IDE are supported by GitHub Copilot ?
- Visual Studio
- Visual Studio Code
- Vim
- JetBrains
