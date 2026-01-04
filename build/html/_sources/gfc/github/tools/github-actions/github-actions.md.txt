# GitHub Actions

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

## Visualize

::::{grid}
:::{grid-item-card}
How can you visualize the execution progress of a GitHub Actions workflow run ?
:::

:::{grid-item-card}
By navigating to the "Actions" tab in the repository.
:::

:::{grid-item-card}
The progress of a GitHub Actions workflow run can be visualized by navigating to the "Actions" tab in the repository on `github.com`.\
From there, users can view a visualization graph of the run's progress and see the activity of each step in the workflow.
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/get-started/understand-github-actions#viewing-the-activity-for-a-workflow-run
:::
::::

## Events

### Primary purpose

::::{grid}
:::{grid-item-card}
Which of the following accurately describes the events that can trigger workflows in GitHub Actions ?
:::

:::{grid-item-card}
Workflows can be triggered by specific activity on GitHub, scheduled times, or events from external sources.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
https://docs.github.com/en/actions/reference/workflows-and-actions/events-that-trigger-workflows
:::
::::

### details

::::{grid}
:::{grid-item-card}
Which of the following events can trigger a workflow run in GitHub Actions ?
:::

:::{grid-item-card}
* By posting to a REST API.
* Only by pushing code changes.
* {bdg-success}`Correct` All of the above.
:::

:::{grid-item-card}
Workflows in GitHub Actions can be triggered by various events, including :
* code pushes,
* pull requests,
* issue creation,
* manual triggers,
* posting to a REST API, 
* or even on a defined schedule.
:::

:::{grid-item-card}
https://docs.github.com/en/actions/get-started/understand-github-actions#events
:::
::::

::::{grid}
:::{grid-item-card}
Which of the following can trigger a workflow in your GitHub repository ?\
*Choose FOUR correct answers.*
:::

:::{grid-item-card}
* {bdg-success}`Correct` Edit a pull request comment.
* {bdg-success}`Correct` Repository changes from private to public.
* {bdg-success}`Correct` Comment on a discussion.
* {bdg-success}`Correct` Someone stars a repository.
* Create more than three tags at once.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/reference/workflows-and-actions/events-that-trigger-workflows#create
:::
::::

### Webhooks

::::{grid}
:::{grid-item-card}
What is the purpose of using webhooks in GitHub Projects ?
:::

:::{grid-item-card}
To trigger automation based on project events.
:::

:::{grid-item-card}
You can use webhooks to subscribe to events taking place in your project.
For example, when an item is edited, GitHub can send a HTTP POST payload to the webhook's configured URL which can trigger automation on your server.
:::

:::{grid-item-card}
* https://docs.github.com/en/webhooks/about-webhooks
:::
::::

## Workflows

### Scope

::::{grid}
:::{grid-item-card}
A GitHub project can span multiple repositories, but a workflow is specific to a repository ?
:::

:::{grid-item-card}
* {bdg-success}`Correct` True
* False
:::

:::{grid-item-card}
A project can span multiple repositories, but a workflow is specific to a repository.\
Add the workflow to each repository that you want your project to track.
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/automating-projects-using-actions#github-actions-workflows
:::
::::

### File location

::::{grid}
:::{grid-item-card}
Which of the following is true about workflows in GitHub ?\
*Choose TWO correct answers.*
:::

:::{grid-item-card}
* {bdg-success}`Correct` Workflows are defined by a `YAML` file to run one or more jobs.
* {bdg-success}`Correct` Workflows are defined in the `.github/workflows` directory.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/get-started/understand-github-actions#workflows
:::
::::

::::{grid}
:::{grid-item-card}
Where can you define the actions you use in your workflow ?
*Choose THREE correct answers.*
:::

:::{grid-item-card}
* The same repository as your workflow file.
* A published Docker container image on Docker Hub.
* Any public repository.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/how-tos/write-workflows/choose-what-workflows-do/find-and-customize-actions#adding-an-action-to-your-workflow
:::
::::


### Syntax

::::{grid}
:::{grid-item-card}
What are the components of a GitHub Actions workflow ?
:::

:::{grid-item-card}
`Jobs`, `actions`, and `runners`.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/about-github-actions/understanding-github-actions#the-components-of-github-actions
:::
::::

::::{grid}
:::{grid-item-card}
What is an action in GitHub Actions ?
:::

:::{grid-item-card}
A custom application that performs a complex but frequently repeated task.
:::

:::{grid-item-card}
An action is a custom application for the GitHub Actions platform that performs a complex but frequently repeated task.\
Use an action to help reduce the amount of repetitive code that you write in your workflow files.\
An action can pull your git repository from GitHub, set up the correct toolchain for your build environment, or set up the authentication to your cloud provider.

You can write your own actions, or you can find actions to use in your workflows in the GitHub Marketplace.
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/concepts/workflows-and-actions/custom-actions
:::
::::

::::{grid}
:::{grid-item-card}
Brian, a software engineer, is setting up a continuous integration (CI) workflow for his project on GitHub.\
He wants to understand how jobs work within GitHub Actions to streamline the build and testing process efficiently.\
What is a job in the context of GitHub Actions ?
:::

:::{grid-item-card}
A set of steps executed on the same `runner`.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/get-started/understand-github-actions#jobs
:::
::::

::::{grid}
:::{grid-item-card}
What is a `job` in the context of GitHub Actions ?
:::

:::{grid-item-card}
A set of steps that are executed sequentially.
:::

:::{grid-item-card}
In GitHub Actions, a `job` is a collection of steps that are executed sequentially on the same runner. Each `job` performs a specific set of tasks defined within a workflow.

![](../../../../_include/gfc/github/tools/github-actions/E3Q22/img/E3Q22.png)
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/get-started/understand-github-actions#jobs
:::
::::

::::{grid}
:::{grid-item-card}
Peter is working on a GitHub Actions workflow for his project, which involves multiple tasks such as building the application, running tests, and deploying the application.\
What should Peter do to ensure that the deployment job in his GitHub Actions workflow starts only after the build and test jobs have completed successfully ?
:::

:::{grid-item-card}
Peter should specify job dependencies in the GitHub Actions workflow file to make the deployment job dependent on the build and test jobs.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/reference/workflows-and-actions/workflow-syntax#jobsjob_idneeds
:::
::::

### default

::::{grid}
:::{grid-item-card}
Which of the following is a default workflow available for GitHub projects ?
:::

:::{grid-item-card}
- {bdg-success}`Correct` Item reopened
- Issue open
- Sprint planning completed
- Issue resolved
:::

:::{grid-item-card}
Default workflows:
- `Item added to project`
- `Item reopened`
- `Item closed`
- `Code changes requested`
- `Code review approved`
- `Pull request merged`
- `Auto-archive items`
- `Auto-add to project`

![](../../../../_include/gfc/github/tools/github-actions/E3Q16/img/E3Q16.png)
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/reference/workflows-and-actions/workflow-syntax
:::
::::

::::{grid}
:::{grid-item-card}
What is the purpose of the actions/add-to-project workflow ?
:::

:::{grid-item-card}
It automates the process of adding issues and pull requests to projects.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://github.com/actions/add-to-project
:::
::::

### Security policy

::::{grid}
:::{grid-item-card}
As a repository owner, what actions can you restrict on GitHub Actions ?
:::

:::{grid-item-card}
You can disable GitHub Actions for a repository, or set a policy that configures which Actions and reusable Workflows can be used in the repository.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository
:::
::::

### redirects actions

::::{grid}
:::{grid-item-card}
Why does GitHub Actions not support **redirects** for actions or reusable workflows ?
:::

:::{grid-item-card}
To prevent security vulnerabilities.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/reference/workflows-and-actions/reusing-workflow-configurations#access-to-reusable-workflows
:::
::::

### Renaming directory

::::{grid}
:::{grid-item-card}
Chris has been actively developing a project on GitHub, utilizing GitHub Actions to automate various tasks in his workflow. Recently, he renamed one of the repositories containing actions referenced in his workflows.\
What consequence does Chris face regarding his workflows ?
:::

:::{grid-item-card}
* Workflows using the previous repository name will encounter failures.
:::

:::{grid-item-card}
When Chris renames a repository containing actions referenced in his workflows, any workflows using the previous repository name will fail. GitHub Actions does not support redirects for actions, necessitating Chris to update his workflows accordingly to ensure seamless automation processes.
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/learn-github-actions/finding-and-customizing-actions#adding-an-action-to-your-workflow
:::
::::

::::{grid}
:::{grid-item-card}
What happens if a workflow tries to use a reusable workflow from a repository that has changed its name ?
:::

:::{grid-item-card}
The workflow will fail because redirects are not supported.
:::

:::{grid-item-card}
If the name of a repository or an action changes, workflows using that action with the previous name will fail because redirects are not supported.

```{note}
To enhance security, GitHub Actions does not support redirects for actions or reusable workflows.
```
:::

:::{grid-item-card}
:::
::::

### reuse

::::{grid}
:::{grid-item-card}
What is the primary benefit of reusing workflows in GitHub Actions ?
:::

:::{grid-item-card}
Avoiding duplication and promoting best practices.
:::

:::{grid-item-card}
Reusing workflows

Rather than copying and pasting from one workflow to another, you can make workflows reusable. You and anyone with access to the reusable workflow can then call the reusable workflow from another workflow.

Reusing workflows avoids duplication. This makes workflows easier to maintain and allows you to create new workflows more quickly by building on the work of others, just as you do with actions. Workflow reuse also promotes best practice by helping you to use workflows that are well designed, have already been tested, and have been proven to be effective. Your organization can build up a library of reusable workflows that can be centrally maintained.

The diagram below shows an in-progress workflow run that uses a reusable workflow.

After each of three build jobs on the left of the diagram completes successfully, a dependent job called "Deploy" is run.

The "Deploy" job calls a reusable workflow that contains three jobs: "Staging", "Review", and "Production."

The "Production" deployment job only runs after the "Staging" job has completed successfully.

When a job targets an environment, the workflow run displays a progress bar that shows the number of steps in the job. In the diagram below, the "Production" job contains 8 steps, with step 6 currently being processed.

Using a reusable workflow to run deployment jobs allows you to run those jobs for each build without duplicating code in workflows.
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/how-tos/reuse-automations/reuse-workflows#access-to-reusable-workflows
:::
::::

::::{grid}
:::{grid-item-card}
Under what conditions can a workflow use a reusable workflow ?
:::

:::{grid-item-card}
If the called workflow is stored in a public repository or a private repository with appropriate access settings.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/how-tos/reuse-automations/share-across-private-repositories#sharing-actions-and-workflows-from-your-private-repository
* https://docs.github.com/en/actions/how-tos/reuse-automations/reuse-workflows
:::
::::

::::{grid}
:::{grid-item-card}
Which keyword is used to reference a reusable workflow within a job ?
:::

:::{grid-item-card}
`uses`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/actions/how-tos/reuse-automations/reuse-workflows#calling-a-reusable-workflow
:::
::::

::::{grid}
:::{grid-item-card}
What is the term for a workflow that uses another workflow ?
:::

:::{grid-item-card}
Caller workflow
:::

:::{grid-item-card}
:::

:::{grid-item-card}
https://docs.github.com/en/actions/how-tos/reuse-automations/reuse-workflows#using-inputs-and-secrets-in-a-reusable-workflow
:::
::::

## GitHub Actions vs Jenkins

::::{grid}
:::{grid-item-card}
oe Swanson is considering options for implementing a CI/CD solution for his development projects. He is comparing GitHub Actions and Jenkins to determine which one would best suit his requirements.\
Which statement best describes the difference between GitHub and Jenkins for CI/CD ?
:::

:::{grid-item-card}
Jenkins focuses only on automation and CI/CD capabilities, while GitHub Actions offers a complete DevOps and DevSecOps platform.
:::

:::{grid-item-card}
rying to decide whether to use GitHub Actions vs. Jenkins? If you’re looking for a cloud-hosted CI/CD solution, GitHub Actions bring extensive and platform-native capabilities to the GitHub platform. Plus, it’s included in GitHub Enterprise. You can also look at CloudBees, which is the commercial variant of Jenkins and fully integrates into the GitHub experience. But where GitHub offers a complete DevOps and DevSecOps platform, Jenkins and its CloudBees commercial solution focus only on automation and CI/CD capabilities.
:::

:::{grid-item-card}
* https://resources.github.com/devops/tools/compare/
:::
::::
