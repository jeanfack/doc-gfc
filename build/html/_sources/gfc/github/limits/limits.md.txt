# Limits

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

## Team synchronization

::::{grid}
:::{grid-item-card}
What is the maximum number of members allowed in a GitHub team when using team synchronization?
:::

:::{grid-item-card}
5000
:::

:::{grid-item-card}
Usage limits
* Maximum number of members in a GitHub team: 5,000
* Maximum number of members in a GitHub organization: 10,000
* Maximum number of teams in a GitHub organization: 1,500
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/authenticate-authorize-user-identities-github/5-team-synchronization
:::
::::

## Service Level Agreement (SLA)

::::{grid}
:::{grid-item-card}
What is the service level agreement (SLA) for GitHub Enterprise Cloud's monthly uptime ?
:::

:::{grid-item-card}
99,9%
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/enterprise-cloud@latest/get-started/learning-about-github/githubs-plans#github-enterprise
:::
::::


## gh-pages

::::{grid}
:::{grid-item-card}
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits
:::
::::

::::{grid}
:::{grid-item-card}
What happens if a GitHub Pages deployment takes longer than 10 minutes ?
:::

:::{grid-item-card}
The deployment fails.
:::

:::{grid-item-card}
GitHub Pages deployments will timeout if they take longer than 10 minutes.
:::

:::{grid-item-card}
* https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#usage-limits
:::
::::

::::{grid}
:::{grid-item-card}
hat is the recommended limit for GitHub Pages source repositories?
:::

:::{grid-item-card}
1 GB
:::

:::{grid-item-card}
GitHub Pages sites are subject to the following usage limits:
* GitHub Pages source repositories have a recommended limit of 1 GB.
* Published GitHub Pages sites may be no larger than 1 GB.
* GitHub Pages deployments will timeout if they take longer than 10 minutes.
* GitHub Pages sites have a *soft* bandwidth limit of 100 GB per month.
* GitHub Pages sites have a *soft* limit of 10 builds per hour. This limit does not apply if you build and publish your site with a custom GitHub Actions workflow
* In order to provide consistent quality of service for all GitHub Pages sites, rate limits may apply. These rate limits are not intended to interfere with legitimate uses of GitHub Pages. If your request triggers rate limiting, you will receive an appropriate response with an HTTP status code of `429`, along with an informative HTML body.
:::

:::{grid-item-card}
* https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits#usage-limits
:::
::::

## Polls

::::{grid}
:::{grid-item-card}
What is the maximum number of options that can be added to a poll in GitHub Discussions ?
:::

:::{grid-item-card}
8
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/discussions/collaborating-with-your-community-using-discussions/about-discussions#about-polls
:::
::::

## repository

::::{grid}
:::{grid-item-card}
What is the recommended ideal size for repositories to ensure better performance and ease of maintenance ?
:::

:::{grid-item-card}
Less than 1 GiB.
:::

:::{grid-item-card}
GitHub recommends repositories to remain small, ideally less than 1 GB, and less than 5 GB is strongly recommended for better performance and ease of maintenance.
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github?platform=windows#repository-size-limits
:::
::::

### Diff

::::{grid}
:::{grid-item-card}
How many files can be included in a single diff on GitHub ?
:::

:::{grid-item-card}
300
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/creating-and-managing-repositories/repository-limits#diff-limits
:::
::::

::::{grid}
:::{grid-item-card}
What are the limits imposed on diffs for commits, pull requests, and compare views on GitHub ?
:::

:::{grid-item-card}
No total diff may exceed 20,000 lines or 1 MB of raw diff data.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/creating-and-managing-repositories/repository-limits#diff-limits
:::
::::

## Large files

::::{grid}
:::{grid-item-card}
What is the maximum size allowed for individual binary files in GitHub releases ?
:::

:::{grid-item-card}
2Go
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github?platform=windows#distributing-large-binaries
:::
::::

::::{grid}
:::{grid-item-card}
Stewie Griffin wants to add a large file (150 MiB) to his GitHub repository.\
What should he do to ensure that the file is uploaded successfully ?
:::

:::{grid-item-card}
Use Git Large File Storage (LFS)
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository?platform=linux#adding-a-file-to-a-repository-on-github
:::
::::

::::{grid}
:::{grid-item-card}
What is the maximum size allowed for files added to a repository via a browser ?
:::

:::{grid-item-card}
25 MiB
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github
:::
::::

::::{grid}
:::{grid-item-card}
What warning does Git provide if you attempt to add or update a file larger than 50 MiB to a repository ?
:::

:::{grid-item-card}
It displays a warning but allows the changes to be successfully pushed.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github#file-size-limits
:::
::::

## Github Actions Workflows

::::{grid}
:::{grid-item-card}
What is the maximum number of reusable workflows that can be called from a single workflow file ?
:::

:::{grid-item-card}
20
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/sharing-automations/reusing-workflows#limitations
:::
::::

### Level

::::{grid}
:::{grid-item-card}
How many levels of workflows can be connected together ?
:::

:::{grid-item-card}
Up to four levels
:::

:::{grid-item-card}
A maximum of four levels of workflows can be connected, including the top-level caller workflow and up to three levels of reusable workflows.
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/using-workflows/reusing-workflows#limitations
:::
::::

## Issues/Pull Requests

::::{grid}
:::{grid-item-card}
How many people can be assigned to an issue or pull request in private repositories for a free plan ?
:::

:::{grid-item-card}
Only one person
:::

:::{grid-item-card}
Issues and pull requests in public repositories,\
and in private repositories for a paid account,\
can have up to 10 people assigned.\
Private repositories on the free plan are limited to one person per issue or pull request.
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/assigning-issues-and-pull-requests-to-other-github-users#about-issue-and-pull-request-assignees
:::
::::

::::{grid}
:::{grid-item-card}
How many people can be assigned to an issue or pull request in public repositories or private repositories for a paid account ?
:::

:::{grid-item-card}
Up to 10 people
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/assigning-issues-and-pull-requests-to-other-github-users#about-issue-and-pull-request-assignees
:::
::::

::::{grid}
:::{grid-item-card}
How many issues can be manually linked to each pull request ?
:::

:::{grid-item-card}
Up to 10
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue#manually-linking-a-pull-request-to-an-issue-using-the-pull-request-sidebar
:::
::::

### Sub-issues

::::{grid}
:::{grid-item-card}
What is the maximum nesting depth for sub-issues in GitHub ?
:::

:::{grid-item-card}
8 levels
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/adding-sub-issues
:::
::::

## Insights

### Network

::::{grid}
:::{grid-item-card}
How many of the most recently pushed-to branches does the network graph of a repository display on GitHub ?
:::

:::{grid-item-card}
100
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/viewing-activity-and-data-for-your-repository/understanding-connections-between-repositories#viewing-a-repositorys-network
:::
::::

## Codespaces

::::{grid}
:::{grid-item-card}
How does GitHub Codespaces handle inactivity timeouts ?
:::

:::{grid-item-card}
Codespaces time out after 30 minutes of inactivity.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/codespaces/setting-your-user-preferences/setting-your-timeout-period-for-github-codespaces#about-the-idle-timeout
:::
::::

## Discussions

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
:::
::::

## CODEOWNERS

::::{grid}
:::{grid-item-card}
What is CODEOWNERS file size limit ?
:::

:::{grid-item-card}
3MB
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners#codeowners-file-size
:::
::::

## Project

### auto-add workflows

::::{grid}
:::{grid-item-card}
How many auto-add workflows can you have in GitHub Enterprise Server ?
:::

:::{grid-item-card}
20
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/adding-items-automatically#about-automatically-adding-items
:::
::::

### automatically archive items

::::{grid}
:::{grid-item-card}
Why would a project manager want to automatically archive items in a GitHub project ?
:::

:::{grid-item-card}
To help stay below the limit of 1,200 items in the project and manage clutter.
:::

:::{grid-item-card}
Automatically archiving items in a GitHub project helps the project manager manage clutter and stay within the limit of 1,200 items per project. By automatically archiving items that meet specific criteria, such as being closed or not planned, the project board remains organized, and the number of active items is kept in check.
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-items-in-your-project/adding-items-to-your-project
:::
::::
