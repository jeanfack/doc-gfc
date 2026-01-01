# Doc

::::{grid}
:::{grid-item-card}
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::

## `CONTRIBUTING.md`

::::{grid}
:::{grid-item-card}
What is the purpose of a `CONTRIBUTING.md` file in an InnerSource project ?
:::

:::{grid-item-card}
To explain the contribution policy for the project and guide potential contributors.

![](../../../../_include/gfc/github/repository/doc/CONTRIBUTING.md/E4Q2/img/E4Q2.png)
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/manage-innersource-program-github/2-manage-innersource-program
* https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors
:::
::::

## `README.md`

### File location 

::::{grid}
:::{grid-item-card}
What happens if Lois places the `README` file in the **root** directory of her repository and also in the `.github` directory ?
:::

:::{grid-item-card}
Only the `README` file in the `.github` directory will be shown.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes#about-readmes
:::
::::

### Profile

::::{grid}
:::{grid-item-card}
How can you make a README file appear on your GitHub profile automatically ?
:::

:::{grid-item-card}
Name the `README` file after your username.
:::

:::{grid-item-card}
To display a `README` on your GitHub profile, create a public repository with the same name as your GitHub username (for example, if your username is `quizexpert`, the repository should also be named `quizexpert`).

Place a `README.md` file in the **root** directory of this repository.\
GitHub will automatically render the contents of this `README` at the top of your profile page, allowing you to introduce yourself, showcase projects, or share updates using GitHub Flavored Markdown.
:::

:::{grid-item-card}
* https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme
:::
::::

### Relative link

::::{grid}
:::{grid-item-card}
What is the advantage of using relative links in `README` files ?
:::

:::{grid-item-card}
They ensure that links work regardless of the current branch.
:::

:::{grid-item-card}
Relative links in `README` files ensure that links work regardless of the current branch, as GitHub automatically transforms relative links or image paths based on the branch the user is currently on.\
This makes relative links more reliable for users who clone the repository.
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes#relative-links-and-image-paths-in-readme-files
:::
::::

## `SECURITY.md`

::::{grid}
:::{grid-item-card}
What is a security policy in GitHub ?
:::

:::{grid-item-card}
Define guidelines for reporting security vulnerabilities.
:::

:::{grid-item-card}
Give people instructions for reporting security vulnerabilities in your project.\ 
you can add a `SECURITY.md` file to your repository's **root**, `docs`, or `.github` folder.\
When someone creates an issue in your repository, they will see a link to your project's security policy.
:::

:::{grid-item-card}
https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository
:::
::::
