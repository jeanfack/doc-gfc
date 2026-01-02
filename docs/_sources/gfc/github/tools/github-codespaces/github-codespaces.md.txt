# GitHub Codespaces

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

## GitHub Codespaces vs GitHub.dev

::::{grid}
:::{grid-item-card}
When should you use `GitHub Codespaces` over `GitHub.dev`?
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

## Create

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

## About

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

## Operating Systems

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

## Lifecycle

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

## Customize

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

## Limit

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
