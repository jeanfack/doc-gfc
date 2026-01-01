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

## Roles

::::{grid}
:::{grid-item-card}
What is the minimum permission required to contribute to a GitHub repository ?
:::

:::{grid-item-card}
* {bdg-success}`Correct` `Write`
:::

:::{grid-item-card}
* `Read`: Recommended for non-code contributors who want to view or discuss your project
* `Triage`: Recommended for contributors who need to proactively manage issues, discussions, and pull requests without write access
* `Write`: Recommended for contributors who actively push to your project
* `Maintain`: Recommended for project managers who need to manage the repository without access to sensitive or destructive actions
* `Admin`: Recommended for people who need full access to the project, including sensitive and destructive actions like managing security or deleting a repository
:::

:::{grid-item-card}
* https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-repository-roles/repository-roles-for-an-organization#permissions-for-each-role
:::
::::

::::{grid}
:::{grid-item-card}
What are the predefined roles available for a GitHub repository in an organization ?\
*Choose THREE correct answers.*
:::

:::{grid-item-card}
* {bdg-success}`Correct` Maitain
* {bdg-success}`Correct` Write
* {bdg-success}`Correct` Triage
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/enterprise-cloud@latest/organizations/managing-peoples-access-to-your-organization-with-roles/roles-in-an-organization#about-pre-defined-organization-roles
:::
::::


## Create

::::{grid}
:::{grid-item-card}
Who can create repository a template on GitHub ?
:::

:::{grid-item-card}
Anyone with `admin` permissions to a repository.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository
:::
::::

## Internal

::::{grid}
:::{grid-item-card}
What distinguishes `internal` repositories from other repositories on GitHub?
:::

:::{grid-item-card}
`Internal` repositories are accessible to all enterprise members.
:::

:::{grid-item-card}
`Internal` repositories on GitHub are accessible to all members within an enterprise.\
This facilitates collaboration and sharing of code and projects among all authorized members of the organization.
:::

:::{grid-item-card}
* https://github.blog/news-insights/product-news/internal-repositories-are-now-generally-available-for-github-enterprise/
:::
::::

## Code scalling

### Primary purpose

::::{grid}
:::{grid-item-card}
What is the primary benefit of using **code scanning** in a GitHub repository ?
:::

:::{grid-item-card}
To analyze and find security vulnerabilities and errors in the code.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/code-security/code-scanning/introduction-to-code-scanning/about-code-scanning#about-code-scanning
:::
::::

### Shifting left

::::{grid}
:::{grid-item-card}
What does the concept of **shifting left** refer to in the context of secure development ?
:::

:::{grid-item-card}
Integrating security measures earlier in the development lifecycle.
:::

:::{grid-item-card}
**Shifting left** in the context of secure development refers to integrating security measures earlier in the development lifecycle.
This helps catch security issues earlier and ensures that security is considered from the beginning of the development process.
:::

:::{grid-item-card}
* https://www.dynatrace.com/news/blog/what-is-shift-left-and-what-is-shift-right/
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

## gh-pages

### Primary purpose

::::{grid}
:::{grid-item-card}
Peter, a developer, wants to create a new public repository on GitHub to host his personal website. What should Peter name his new public repository ?
:::

:::{grid-item-card}
Peter must name his repository `<username>.github.io`, where `<username>` is his username on GitHub.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#types-of-github-pages-sites
:::
::::

::::{grid}
:::{grid-item-card}
Chris Griffin works for an organization that develops various open-source projects.\
The organization wants to create a centralized website to provide information about its projects and activities.\
Which type of GitHub Pages site should Chris create for the organization's centralized website ?
:::

:::{grid-item-card}
Organization site
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
:::
::::

### Private

::::{grid}
:::{grid-item-card}
GitHub Pages sites are publicly available on the internet, even if the repository for the site is private.
:::

:::{grid-item-card}
* {bdg-success}`Correct` True
* False
:::

:::{grid-item-card}
GitHub Pages is available only in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server.

Hence, with GitHub paid accounts, GitHub Pages sites are publicly available on the internet, even if the repository for the site is private.\
If you have sensitive data in your site's repository, you may want to remove the data before publishing.
:::

:::{grid-item-card}
* https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#publishing-sources-for-github-pages-sites
:::
::::

## Stars

::::{grid}
:::{grid-item-card}
Lois has starred numerous repositories on GitHub related to various programming languages and frameworks.\
She wants to organize them into different categories for easier access.\
How can Lois organize her starred repositories into public lists on GitHub ?
:::

:::{grid-item-card}
By creating public lists that appear on her stars page using the "Lists" feature.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars#organizing-starred-repositories-with-lists
:::
::::

::::{grid}
:::{grid-item-card}
Stewie wants to know who has starred a repository called "awesome-quiz-experts-practice-test". How can he view the list of users who have starred this repository ?
:::

:::{grid-item-card}
Visit https://github.com/awesome-quiz-experts-practice-test/stargazers
:::

:::{grid-item-card}
Stewie can view the list of users who have starred the "awesome-quiz-experts-practice-test" repository by adding `/stargazers` to the end of the repository URL - https://github.com/awesome-quiz-experts-practice-test/stargazers.
:::

:::{grid-item-card}
* https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars#viewing-who-has-starred-a-repository
:::
::::

## Watch

::::{grid}
:::{grid-item-card}
Tricia Takanawa wants to stay updated on the activity in a specific repository on GitHub.\
What action should she take ?
:::

:::{grid-item-card}
* Fork the repository.
* Star the repository.
* Clone the repository.
* {bdg-success}`Correct` Watch the repository.
:::

:::{grid-item-card}
To stay updated on the activity in a specific repository on GitHub, Tricia Takanawa should `watch` the repository. 
Watching a repository means subscribing to updates for activity in that repository.
:::

:::{grid-item-card}
* https://docs.github.com/en/subscriptions-and-notifications/get-started/configuring-notifications#about-participating-and-watching-notifications
:::
::::

## Template

::::{grid}
:::{grid-item-card}
Bonnie wants to use a template repository as starter code for an assignment in GitHub Classroom.\
She wants to ensure that she understands any limitations associated with template repositories.\
What is a limitation of template repositories on GitHub ?
:::

:::{grid-item-card}
* {bdg-success}`Correct` They cannot include files stored using Git LFS.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository
:::
::::

::::{grid}
:::{grid-item-card}
Tom Tucker wants to create a template repository for his project to ensure that future repositories have the same directory structure, branches, and files.\
Which of the following statements is true regarding creating a template repository on GitHub ?
:::

:::{grid-item-card}
* Template repositories cannot be used as starter code for assignments on GitHub Classroom.
* Template repositories can include files stored using Git LFS.
* {bdg-success}`Correct` Branches created from a template repository have unrelated histories, so you cannot create pull requests or merge between them.
* Only users with admin permissions can create a new repository based on the template.
:::

:::{grid-item-card}
When you create a template repository on GitHub, anyone with access to the template repository can generate a new repository based on the template.\
However, the branches created from a template repository have unrelated histories, meaning that you cannot create pull requests or merge between these branches.\
This ensures that each new repository created from the template starts with a clean slate, separate from the original template repository.

```{admonition} Example
Tom Tucker creates a template repository for his project that includes a default branch with the main directory structure and files.\
When a team member generates a new repository from the template, they can choose to include all other branches from the template repository.\
However, these branches will have unrelated histories, preventing them from merging changes or creating pull requests between branches.
```
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository#creating-a-template-repository
:::
::::

::::{grid}
:::{grid-item-card}
What should you do if you want to include the directory structure and files from all branches of the template repository ?
:::

:::{grid-item-card}
Check the **Include all branches** option while creating the repository from the template.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template
:::
::::
