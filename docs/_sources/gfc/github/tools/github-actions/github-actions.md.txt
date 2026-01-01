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

## Events

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

## Workflows

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
