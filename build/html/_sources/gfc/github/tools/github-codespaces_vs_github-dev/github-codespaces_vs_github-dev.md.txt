# GitHub Codespaces vs `github.dev`

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

## GitHub Codespaces

### Primary purpose

::::{grid}
:::{grid-item-card}
What is a GitHub Codespace ?
:::

:::{grid-item-card}
Remote development environment
:::

:::{grid-item-card}
:::

:::{grid-item-card}
https://docs.github.com/en/codespaces/about-codespaces/what-are-codespaces
:::
::::


### Create

::::{grid}
:::{grid-item-card}
What are the four ways to create a Codespace in GitHub ?
:::

:::{grid-item-card}
* {bdg-success}`Correct` From a GitHub template, from a branch, from a pull request, from a commit in a repository's history.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/about-codespaces/deep-dive#creating-your-codespace
:::
::::

::::{grid}
:::{grid-item-card}
Peter wants to continue his work in a **GitHub Codespace** from `github.dev`.\
What option should he choose ?
:::

:::{grid-item-card}
Click on "Continue Working On…" and select "Create New Codespace".
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/the-githubdev-web-based-editor#continue-working-on-codespaces
:::
::::

### Delete

::::{grid}
:::{grid-item-card}
What happens when you delete a Codespace with unpushed git commits ?
:::

:::{grid-item-card}
A warning notifies you of unpushed changes, allowing you to push changes before deletion.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/about-codespaces/understanding-the-codespace-lifecycle#deleting-a-codespace
:::
::::

### About

::::{grid}
:::{grid-item-card}
How does GitHub Codespaces work ?
:::

:::{grid-item-card}
It uses containers to provide a cloud-based development environment.
:::

:::{grid-item-card}
GitHub Codespaces uses containers to provide an instant and consistent development environment with common languages, tools, and utilities without relying on local machine installation.
:::

:::{grid-item-card}
https://docs.github.com/en/codespaces/about-codespaces/deep-dive
:::
::::

### Operating Systems

::::{grid}
:::{grid-item-card}
Which operating systems are supported for a codespace development environment ?
:::

:::{grid-item-card}
Linux only
:::

:::{grid-item-card}
By default, the codespace development environment is created from an Ubuntu Linux image that includes a selection of popular languages and tools, 
but you can use an image based on a Linux distribution of your choice and configure it for your particular requirements.\
Regardless of your local operating system, your codespace will run in a Linux environment.\
Windows and macOS are not supported operating systems for the remote development container.
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/about-codespaces/what-are-codespaces
:::
::::

::::{grid}
:::{grid-item-card}
What is the default operating system for a codespace development environment ?
:::

:::{grid-item-card}
Ubuntu Linux
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/overview#what-is-a-codespace
:::
::::

### Lifecycle

::::{grid}
:::{grid-item-card}
Which of the following stages is not part of the Codespace's lifecycle ?
:::

:::{grid-item-card}
* {bdg-success}`Correct` Run
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/code-with-github-codespaces/2-codespace-lifecycle
:::
::::

### Customize

::::{grid}
:::{grid-item-card}
What customization can you do for codespaces ?
*Choose FOUR correct answers.*
:::

:::{grid-item-card}
* {bdg-success}`Correct` Change the name.
* {bdg-success}`Correct` Change the IDE.
* {bdg-success}`Correct` Change the shell.
* {bdg-success}`Correct` Change the virtual machine.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/customizing-your-codespace
:::
::::

### Lost internet connectivity

::::{grid}
:::{grid-item-card}
What happens when Codespace loses internet connectivity ?
:::

:::{grid-item-card}
If the connection to the internet is lost while working in a Codespace, you aren't able to access your Codespace.
:::

:::{grid-item-card}
A Codespace requires an internet connection. If the connection to the internet is lost while working in a Codespace, you won't be able to access your Codespace. However, any uncommitted changes are saved. When you reestablish the internet connection, you can access the Codespace in the same state that it was left in when the connection was lost.

If you have an unstable internet connection, you should frequently commit and push your changes.
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/about-codespaces/understanding-the-codespace-lifecycle#losing-the-connection-while-using-github-codespaces
* https://learn.microsoft.com/en-us/training/modules/code-with-github-codespaces/2-codespace-lifecycle
:::
::::

### Limit

::::{grid}
:::{grid-item-card}
What is the maximum number of Codespaces that you can create per repository or branch ?
:::

:::{grid-item-card}
You can create an unlimited number of Codespaces.
:::

:::{grid-item-card}
You can create an unlimited number of Codespaces per repository or branch, depending upon available space. When you reach an upper amount of resources, a message displays that an existing Codespace needs to removed/deleted before a new Codespace can be created.

You can have an unlimited number of Codespaces per repository or even per branch. However, there are limits on the resources that Codespaces use.
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/managing-codespaces-for-your-organization/managing-the-cost-of-github-codespaces-in-your-organization
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

::::{grid}
:::{grid-item-card}
How can you open an existing pull request in `github.dev` for further editing ?
:::

:::{grid-item-card}
Press `.` while viewing the pull request on GitHub.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/the-githubdev-web-based-editor#opening-the-githubdev-editor
:::
::::

### Github repositories extension

::::{grid}
:::{grid-item-card}
What does the `github.dev` editor use to carry out most of its functionality ?
:::

:::{grid-item-card}
**GitHub Repositories extension**
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/the-githubdev-web-based-editor#about-the-githubdev-editor
:::
::::

### Troubleshooting

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

## GitHub Codespaces vs `github.dev`

::::{grid}
:::{grid-item-card}
When should you use `GitHub Codespaces` over `github.dev`?
:::

:::{grid-item-card}
Use `GitHub Codespaces` for heavy lifting, testing code, and terminal access.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/code-with-github-codespaces/4-codespaces-versus-github-dev-editor
:::
::::

::::{grid}
:::{grid-item-card}
What is the main difference in terms of compute between `github.dev` and **GitHub Codespaces** ?
:::

:::{grid-item-card}
GitHub Codespaces has dedicated VM for running and debugging applications.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/code-with-github-codespaces/4-codespaces-versus-github-dev-editor
:::
::::

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
