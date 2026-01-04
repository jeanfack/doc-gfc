# `.gitignore` config file

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
Imagine that one of your source projects relies on secrets stored in a folder called `.secrets`. You want to make sure that the files kept in this folder on development machines are not accidentally committed to the repository.\
Which of these files is the most effective for enforcing this policy ?
:::

:::{grid-item-card}
`.gitignore`
:::

:::{grid-item-card}
`.gitignore` can be used to help enforce which files are included in commits by tools that respect it. However, the client enforces this policy and doesn't necessarily prevent users from committing files that violate policy.

`SECURITY.md` is used to explain the security policy of your project to consumers and contributors, but it doesn't automate anything, so it is not the right answer.

`CONTRIBUTING.md` is used to explain the contribution policy of your project, but it doesn't automate anything, so it is not the right answer.
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files
:::
::::

## Global ignore

::::{grid}
:::{grid-item-card}
Lois Griffin wants to configure Git to ignore certain files or directories in all repositories on her computer.\
Which approach should she use ?
:::

:::{grid-item-card}
Add the file paths to the file `~/.config/git/ignore`.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/git-basics/ignoring-files?platform=linux#configuring-ignored-files-for-all-repositories-on-your-computer
:::
::::

## Exclude

::::{grid}
:::{grid-item-card}
Peter Griffin wants to ignore certain files in his Git repository without creating a `.gitignore` file to share with others.\
What approach should he use ?
:::

:::{grid-item-card}
Edit the `.git/info/exclude` file in the root of his repository.
:::

:::{grid-item-card}
Peter Griffin should edit the `.git/info/exclude` file in the root of his repository to add rules that will not be checked in and will only ignore files for his local repository. 
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/git-basics/ignoring-files?platform=linux#excluding-local-files-without-creating-a-gitignore-file
:::
::::

## inheritence

::::{grid}
:::{grid-item-card}
How are settings in .gitignore files inherited in a Git repository ?
:::

:::{grid-item-card}
Settings are inherited from parent directories.
:::

:::{grid-item-card}
In Git repositories, settings from .gitignore files are inherited from parent directories to child directories, 
meaning that settings defined in parent directories are applicable to child directories unless overridden 
by a .gitignore file in the child directory.
:::

:::{grid-item-card}
* https://git-scm.com/docs/gitignore
:::
::::

::::{grid}
:::{grid-item-card}
What is the significance of maintaining multiple `.gitignore` files in a repository ?
:::

:::{grid-item-card}
It allows for more granular control over which files are ignored in different directories.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/git-basics/ignoring-files
:::
::::

::::{grid}
:::{grid-item-card}
How does Git handle conflicting settings between `.gitignore` files in parent and child directories ?
:::

:::{grid-item-card}
It prioritizes settings from child directories.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
https://docs.github.com/en/get-started/git-basics/ignoring-files
:::
::::
