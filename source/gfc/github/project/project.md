# Project

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
What is the primary purpose of GitHub Projects ?
:::

:::{grid-item-card}
To create an adaptable tool for planning and tracking work.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects
:::
::::


::::{grid}
:::{grid-item-card}
What is the primary benefit of GitHub Projects ?
:::

:::{grid-item-card}
Organizing and managing team tasks and priorities.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects
:::
::::


::::{grid}
:::{grid-item-card}
Which of the following statements accurately describes GitHub Projects ?\
*Choose TWO correct answers.*
:::

:::{grid-item-card}
* {bdg-success}`Correct` Projects are structured like a spreadsheet.
* {bdg-success}`Correct` You can use Projects for planning sprints and features.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects
:::
::::


## Layout

::::{grid}
:::{grid-item-card}
Which layout options are available in GitHub Projects ?\
*Choose THREE correct answers.*
:::

:::{grid-item-card}
* {bdg-success}`Correct` Roadmap
* {bdg-success}`Correct` Board
* {bdg-success}`Correct` Table
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/changing-the-layout-of-a-view#changing-the-project-layout
:::
::::

## Fork

::::{grid}
:::{grid-item-card}
Suppose you'd like to work with a project on GitHub, but you don't have write access to the project.\
What can you do to contribute ?
:::

:::{grid-item-card}
Fork the project's repository to your GitHub account, clone the forked repository to your local machine, push changes to your repository, and submit a pull request to the target (upstream) repository.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::

## Project as Template

::::{grid}
:::{grid-item-card}
How can you set a project as a template in GitHub ?
:::

:::{grid-item-card}
Navigate to the "project settings" under settings, select the "Templates" section, and toggle the "Make template" switch to On.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-your-project/managing-project-templates-in-your-organization#setting-a-project-as-a-template
:::
::::

## `Projects` vs `Projects Classic`

::::{grid}
:::{grid-item-card}
What sets Projects apart from Projects Classic in GitHub ?\
*Choose TWO correct answers.*
:::

:::{grid-item-card}
* {bdg-success}`Correct` Insights is available for new Projects.
* {bdg-success}`Correct` Projects offer more views with advanced customization and automation.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/manage-work-github-projects/2-project-vs-project-classic
:::
::::

## organization-owned

::::{grid}
:::{grid-item-card}
When creating an organization-owned GitHub Project, which of the following statements is correct ?
:::

:::{grid-item-card}
* {bdg-success}`Correct` A Project can be created at the organization level and later linked to repositories.
* You must always select a template; starting from scratch is not allowed.
* All checklist items must be converted into sub-issues before adding issues to the Project.
* A Project can only be created from a repository.
:::

:::{grid-item-card}
1. Projects can be created at the organization level, independent of any repository.
2. You can link repositories later, so it’s not required during creation.
3. Projects can start from scratch or use a template, so selecting a template is optional.
4. Checklist items can be converted into sub-issues after issues exist.
5. Projects can also be created from repositories, but it is not mandatory.
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/manage-work-github-projects/3-how-to-create-project
:::
::::

## issues and Pull Requests

::::{grid}
:::{grid-item-card}
How are GitHub Projects updated when changes are made to issues and pull requests ?
:::

:::{grid-item-card}
Information is automatically synced to the project as changes are made.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects#staying-up-to-date
:::
::::

## Large issues

::::{grid}
:::{grid-item-card}
Why is it recommended to break down large issues into smaller ones in project management ?
:::

:::{grid-item-card}
To make the work more manageable and enable team members to work in parallel.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/best-practices-for-projects#break-down-large-issues-into-smaller-issues
:::
::::

## Open-Source

::::{grid}
:::{grid-item-card}
What is the purpose of a pull request in an open-source project ?
:::

:::{grid-item-card}
To propose changes to the project.
:::

:::{grid-item-card}
A pull request is a formal way to propose changes to an open-source project. It contains a title, description, and one or more commits that constitute the changes being proposed.\
Pull requests facilitate discussion, code review, and collaboration among project contributors before the changes are merged into the main codebase.
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/contribute-open-source/3-contribute
:::
::::

::::{grid}
:::{grid-item-card}
What is a recommended course of action when your code can be reused across multiple projects ?
:::

:::{grid-item-card}
Publish the code as a stand-alone library (dependency).
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/contribute-open-source/5-next-steps
:::
::::

::::{grid}
:::{grid-item-card}
What benefits do GitHub actions bring to open-source projects ?
:::

:::{grid-item-card}
Provides packaged scripts for automating tasks in a software development workflow.
:::

:::{grid-item-card}
GitHub Actions are packaged scripts that automate various tasks in a software-development workflow directly within GitHub.\
These actions can perform actions such as running tests, deploying applications, and interacting with external services.\
By using GitHub Actions, developers can streamline their workflows, improve productivity, and maintain consistency across projects.\
Additionally, GitHub Actions contribute to the open-source ecosystem by providing a standardized way to automate repetitive tasks and enhance project efficiency.



```{Admonition} Example
Imagine you're maintaining an open-source project hosted on GitHub, and you want to automate the process of running tests whenever a new pull request is submitted.\
You can create a GitHub Action that triggers test execution whenever changes are made to the codebase.\
This action ensures that all proposed changes undergo thorough testing, helping maintain code quality and reliability.
```
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/github-actions-automate-tasks/2-github-actions-automate-development-tasks
:::
::::

::::{grid}
:::{grid-item-card}
Peter is a project manager for a startup company looking for software solutions that offer flexibility, customization, and cost savings.\
Which advantage of open source software would be most appealing to Peter's requirements ?
:::

:::{grid-item-card}
No vendor lock-in
:::

:::{grid-item-card}
Open source software offers the advantage of no vendor lock-in, meaning there are no lengthy contracts with technical vendors. This allows organizations like Peter's startup to have more budget and bandwidth to experiment with a variety of tools and integrations.
:::

:::{grid-item-card}
* https://resources.github.com/open-source/what-is-open-source-software/
:::
::::

### Issue tracker

::::{grid}
:::{grid-item-card}
Where is the best place to communicate your intent to contribute to an existing open-source project ?
:::

:::{grid-item-card}
Issue tracker
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/contribute-open-source/3-contribute
:::
::::

## Inner-Source

### Primary purpose

::::{grid}
:::{grid-item-card}
What is InnerSource ?
:::

:::{grid-item-card}
Sharing of source code within the organization.
:::

:::{grid-item-card}
InnerSource is a development methodology where engineers collaborate on proprietary software using best practices from large-scale open source projects.\
It involves sharing code within an organization to encourage collaboration and improve the quality of the codebase.

This approach enables teams to work together more effectively, leverage existing internal projects, and build software faster.

InnerSource principles are inspired by successful open source projects and emphasize transparency, open collaboration, and community-driven development.
:::

:::{grid-item-card}
* https://github.com/resources/articles/innersource
:::
::::

::::{grid}
:::{grid-item-card}
What is InnerSource ?
:::

:::{grid-item-card}
A strategy that applies open source practices to proprietary code to enhance collaboration.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://about.gitlab.com/topics/version-control/what-is-innersource/#what-does-inner-source-mean
:::
::::


::::{grid}
:::{grid-item-card}
How does innersource promote code reuse within an organization ?
:::

:::{grid-item-card}
By enabling teams to discover, customize, and reuse existing internal projects.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://github.com/resources/articles/innersource
:::
::::

::::{grid}
:::{grid-item-card}
What role do open source workflow practices play in InnerSource adoption?
:::

:::{grid-item-card}
They facilitate collaboration, visibility, and code reuse.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://about.gitlab.com/topics/version-control/what-is-innersource/#benefits-of-inner-source
:::
::::

### Success program

::::{grid}
:::{grid-item-card}
What is the recommended approach for measuring the success of an InnerSource program ?
:::

:::{grid-item-card}
Tracking the number of external contributors and their contributions.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/manage-innersource-program-github/2-manage-innersource-program
:::
::::

::::{grid}
:::{grid-item-card}
Suppose your team has been tracking data of all kinds since your InnerSource program went live three months ago.\
Which of the following metrics indicates your program is a great success ?
:::

:::{grid-item-card}
* A growing rate of bug reports that are quickly closed because they cannot be reproduced.
* {bdg-success}`Correct` A dramatic rise in pull requests that address bugs in your software.
* A steady decline in new issues.
* Monitoring the frequency of commits made by each team.
:::

:::{grid-item-card}
* A dramatic rise in pull requests that address bugs in your software indicates that more people are motivated to improve the quality of your software and are making the investment themselves.
* Bug reports don't necessarily mean that your software quality is improving.
* A decline in new issues may be an indication that users are satisfied with your software, or it could mean that they have low confidence that reporting issues and requesting features will produce progress. This metric alone is not enough to infer success.
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/manage-innersource-program-github/2-manage-innersource-program
:::
::::


## Build-In Workflow

::::{grid}
:::{grid-item-card}
Meg is managing a GitHub project with a large number of issues and pull requests.\
She wants to ensure that the project remains organized.\
Which of the following actions can Meg take to automatically manage items in her project ?
:::

:::{grid-item-card}
Configure built-in workflows to automatically archive items based on specific criteria.
:::

:::{grid-item-card}
By configuring built-in workflows to automatically archive items based on specific criteria such as status (open, closed, merged), reason (completed, reopened, not planned), and last updated date, Meg can ensure that the project stays organized and does not exceed the item limit.\
This automation helps in managing the project efficiently without manual intervention.

```{admonition} Example
Meg sets up a workflow to automatically archive closed issues and pull requests that have not been updated in the last month.\
By doing so, she ensures that inactive items are archived, reducing clutter in the project and staying within the item limit.\
GitHub automatically handles the archiving process based on the criteria defined in the workflow.
```
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/archiving-items-automatically
:::
::::

::::{grid}
:::{grid-item-card}
What happens when Peter enables an auto-add workflow in GitHub for an existing project board ?
:::

:::{grid-item-card}
The workflow will not add existing items to the project board, but it will add new items that meet the filter criteria.
:::

:::{grid-item-card}
When Peter enables an auto-add workflow in GitHub for an existing project board, existing items matching the criteria will not be automatically added.\
However, the workflow will add new items as they are created or updated if they match the specified filter criteria.
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/adding-items-automatically#about-automatically-adding-items
:::
::::

::::{grid}
:::{grid-item-card}
How many default workflows are enabled when a project initializes in GitHub Projects ?
:::

:::{grid-item-card}
Two
:::

:::{grid-item-card}
When a GitHub Project is initialized, two workflows are enabled by default:
* When issues or pull requests in the project are closed, their status is automatically set to Done.
* When pull requests in the project are merged, their status is automatically set to Done.

Other automation workflows, such as `auto-adding issues` to the project or `auto-closing issues`, are available but not enabled by default and require manual configuration.

```{admonition} UPDATE
Auto-closing issues: There is a blog post regarding this workflow (GitHub Changelog – April 25, 2024), which mentions that for new projects it is enabled by default, but the official documentation still lists it as requiring manual configuration.
```

```{admonition} IMPORTANT NOTE FOR TESTS
Your answers should depend only on the current official documentation.\
Recent updates, blog posts, or new workflows (e.g., Auto-add sub-issues) will not be included in the test.\
GitHub frequently updates its features and workflows, so for the most accurate and up-to-date information, always refer to the official documentation and changelogs.
```
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/using-the-built-in-automations
:::
::::

::::{grid}
:::{grid-item-card}
What is the easiest way to add automation to your Project ?
:::

:::{grid-item-card}
**Built-in Automation**
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/using-the-built-in-automations
:::
::::


## Field

### `Single select`

::::{grid}
:::{grid-item-card}
What field can you use in order to make a Priority grouping like High, Medium, and Low in your Project ?
:::

:::{grid-item-card}
`Single select`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/understanding-fields/about-single-select-fields
:::
::::

### `Iteration`

::::{grid}
:::{grid-item-card}
What does an iteration field help you do in Projects ?
:::

:::{grid-item-card}
Allows you to create sequential phases of your project and group issues and pull request based on the phase.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/understanding-fields/about-iteration-fields
:::
::::
