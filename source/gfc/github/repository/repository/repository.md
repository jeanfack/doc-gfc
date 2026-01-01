# Repository

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

## Archive

::::{grid}
:::{grid-item-card}
Glenn is a contributor to a GitHub repository that has been archived by the repository owner.\
He wants to know what actions he can still perform on the archived repository ?
:::

:::{grid-item-card}
Contributors can only **fork** or **star** the repository, but they cannot make any other changes.
:::

:::{grid-item-card}
When a repository is archived on GitHub, contributors with access to the repository can only fork or star the project.
They cannot make any other changes to the content, such as pushing new commits or opening new issues
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/archiving-a-github-repository/archiving-repositories#about-repository-archival
:::
::::

## Branch protection

::::{grid}
:::{grid-item-card}
How can branch protection rules contribute to secure development on GitHub ?
:::

:::{grid-item-card}
By enforcing certain workflows for branches, such as requiring code reviews and passing status checks.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches
:::
::::

::::{grid}
:::{grid-item-card}
What actions are restricted when working on a protected branch ?
:::

:::{grid-item-card}
* Merging changes without CI tests passing.
* Deleting the branch.
* Force pushing to the branch.
* {bdg-success}`Correct` All of the above.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches#about-branch-protection-settings
:::
::::

## Fork

::::{grid}
:::{grid-item-card}
What is the main difference between forking a repository and creating a repository from a template on GitHub ?
:::

:::{grid-item-card}
Forking includes the entire commit history of the parent repository, while creating from a template starts with a single commit.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#about-repository-templates
:::
::::

::::{grid}
:::{grid-item-card}
What is a fork in the context of GitHub repositories ?
:::

:::{grid-item-card}
A new repository that shares code and visibility settings with the original repository.
:::

:::{grid-item-card}
In GitHub, a fork refers to creating a new repository that retains the code and visibility settings of the original or "upstream" repository.\
This allows users to make changes or additions to the code without directly altering the original repository.\
Forks are commonly used for proposing changes, experimenting with new features, or contributing to open-source projects.

```{admonition} Example
Suppose you find a bug in an open-source project hosted on GitHub.\
Instead of directly making changes to the project's codebase, you fork the repository to your GitHub account.\
Then, you can make the necessary fixes in your forked repository and later submit a pull request to propose these changes to the original project.
```
:::

:::{grid-item-card}
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo
:::
::::

## Gist

### Primary purpose

::::{grid}
:::{grid-item-card}
What are gists on GitHub ?
:::

:::{grid-item-card}
Code snippets sharing
:::

:::{grid-item-card}
Gists in GitHub serve as a simple and quick way to share bits of code with others.
Think of gists as snippets or small pieces of code that you want to share, whether it's a handy function, a specific algorithm, or just a few lines of code that others may find useful.

```{admonition} Example
Suppose you've written a small script to automate a common task or solve a particular problem.\
You can create a gist for that script, share the link with your colleagues, and they can easily view, fork, or even contribute to it.\
When you share a gist, it can be either `public` or `secret`.\
`Public` gists are visible to anyone and can be searched by others, while `secret` gists aren't searchable but can be accessed if someone has the URL.\
It's like a quick way to showcase and collaborate on code without the need for a full-blown repository.
```

```{note}
`Secret` gists are are not private.
```
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/writing-on-github/editing-and-sharing-content-with-gists/creating-gists
:::
::::

::::{grid}
:::{grid-item-card}
Which of the following is true about GitHub Gist ?
:::

:::{grid-item-card}
* {bdg-success}`Correct` You can subscribe to a gist by clicking Subscribe at the top of any gist.
* {bdg-success}`Correct` Gist can be embedded in any text field that supports JavaScript, such as a blog post.
* {bdg-success}`Correct` Gist supports mapping GeoJSON files, so you can easily share and embed maps.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
https://docs.github.com/en/get-started/writing-on-github/editing-and-sharing-content-with-gists/creating-gists
:::
::::

### Fork and clone

::::{grid}
:::{grid-item-card}
What is true about forking and cloning gists on GitHub ?
:::

:::{grid-item-card}
* {bdg-success}`Correct` Both forking and cloning gists are possible, even if you aren't the original author.
* {bdg-success}`Correct` Gists cannot be forked or cloned by anyone other than the original author.
* {bdg-success}`Correct` Forking gists is possible, but cloning gists is not.
* {bdg-success}`Correct` Only the original author can fork or clone their own gists.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
https://docs.github.com/en/get-started/writing-on-github/editing-and-sharing-content-with-gists/forking-and-cloning-gists
:::
::::


### Secret

::::{grid}
:::{grid-item-card}
What are the two types of gists you can create on GitHub ?
:::

:::{grid-item-card}
`Public` and `Secret`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::

::::{grid}
:::{grid-item-card}
What happens if someone discovers the URL of a secret gist on GitHub ?
:::

:::{grid-item-card}
They can view the gist regardless of the author's permissions.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/writing-on-github/editing-and-sharing-content-with-gists/creating-gists#about-gists
:::
::::
