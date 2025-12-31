# Filters

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

## type:repo

::::{grid}
:::{grid-item-card}
Peter Griffin wants to find GitHub repositories related to cats that have 10 or fewer stars.\
Which search query should he use to achieve this ?\
*Choose TWO correct answers.*
:::

:::{grid-item-card}
* `cats stars:~10`
* {bdg-success}`Correct` `cats stars:<=10`
* {bdg-success}`Correct` `cats stars:*..10`
* `cats stars:10`
:::

:::{grid-item-card}
Peter Griffin should use the search query `cats stars:<=10` or `cats stars:*..10` to find GitHub repositories related to cats with 10 or fewer stars.

`cats stars:<=10` matches repositories with the word "cats" that have 10 or fewer stars.
:::

:::{grid-item-card}
https://docs.github.com/en/search-github/searching-on-github/searching-for-repositories#search-by-number-of-stars
:::
::::


## type:issue,pr

::::{grid}
:::{grid-item-card}
Can issues or pull requests be filtered based on the most added reaction ?
:::

:::{grid-item-card}
* {bdg-success}`Correct` Yes
* No
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/filtering-and-searching-issues-and-pull-requests#sorting-issues-and-pull-requests
:::
::::

::::{grid}
:::{grid-item-card}
Lois is a project manager using GitHub to track software development issues for her team.\
She wants to identify issues that have received a moderate level of discussion, specifically those with comments ranging from 500 to 1,000.\
Which search query should Lois use to achieve this ?
:::

:::{grid-item-card}
`comments:500..1000 is:issue`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/search-github/searching-on-github/searching-issues-and-pull-requests#search-by-number-of-comments
:::
::::

::::{grid}
:::{grid-item-card}
The `involves` qualifier is a logical OR between the `author`, `assignee`, `mentions`, and `commenter` qualifiers for a single user.
:::

:::{grid-item-card}
* {bdg-success}`Correct` True
* False
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::

::::{grid}
:::{grid-item-card}
Meg, a developer, is looking for open issues in her GitHub repository that have not been labeled, assigned to anyone, and have no comments yet.\
Which search query should Meg use to find these issues ?
:::

:::{grid-item-card}
`is:open is:issue no:label no:assignee comments:0`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::

::::{grid}
:::{grid-item-card}
Peter is searching for issues created before March 2024 in the "family-guy" project owned by QuizExperts.\
Which search query should he use ?
:::

:::{grid-item-card}
`repo:quiz-experts/family-guy created:<2024-03-01 type:issue`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::

::::{grid}
:::{grid-item-card}
Jillian is a project manager overseeing a software development project.\
She wants to filter and find pull requests opened in May 2023 that have a failed status.\
Which search query should she use ?
:::

:::{grid-item-card}
`created:2023-05-01..2023-05-31 status:failure type:pr`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/search-github/getting-started-with-searching-on-github/understanding-the-search-syntax#query-for-dates
* https://docs.github.com/en/search-github/searching-on-github/searching-issues-and-pull-requests#search-by-commit-status
:::
::::

::::{grid}
:::{grid-item-card}
Peter wants to see all the issues and pull requests that are assigned to him in the project.\
Which filter option should he use ?
:::

:::{grid-item-card}
`is:open assignee:@me`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::

::::{grid}
:::{grid-item-card}
How can you filter issues or pull requests that have either the bug or error labels ?
:::

:::{grid-item-card}
`label:bug,error`
:::

:::{grid-item-card}
:::

:::{grid-item-card}
:::
::::

::::{grid}
:::{grid-item-card}
Which of the following options helps you search for issues with the "404 error" string in repositories owned by the QuizExperts organization ?
:::

:::{grid-item-card}
Search `"404 error" org:QuizExperts` and click on "Issues" under the "Filter by" section.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/filtering-and-searching-issues-and-pull-requests?tool=cli
:::
::::

::::{grid}
:::{grid-item-card}
What does the search qualifier `review-requested:[USERNAME]` allow you to find?
:::

:::{grid-item-card}
Pull requests where the specified user is requested for review.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/viewing-a-pull-request-review
:::
::::

::::{grid}
:::{grid-item-card}
How can you find issues that mention a specific user on GitHub ?
:::

:::{grid-item-card}
Use the `mentions:` followed by the username.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/search-github/searching-on-github/searching-issues-and-pull-requests#search-by-mention
:::
::::


::::{grid}
:::{grid-item-card}
Lois is a project manager on GitHub and wants to filter all the open issues and pull requests in her repository to prioritize tasks.\
Which filtering option should she use?
:::

:::{grid-item-card}
Open issues and pull requests.
:::

:::{grid-item-card}
Lois should choose the option to filter for "Open issues and pull requests" to see all the active tasks in the repository, regardless of their assignees or creators.\
This filter will help her prioritize tasks based on their urgency and importance.
:::

:::{grid-item-card}
* L: https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/filtering-and-searching-issues-and-pull-requests#filtering-issues-and-pull-requests
:::
::::

::::{grid}
:::{grid-item-card}
Stewie is a developer working on a project with multiple contributors. He wants to filter issues and pull requests to see only those that are assigned to him.\
Which filtering option should he select?
:::

:::{grid-item-card}
* {bdg-success}`Correct` Everything assigned to you.
* Your issues.
* Open issues and pull requests.
* Your pull requests.
* Everything mentioning you.
:::

:::{grid-item-card}
Stewie should choose the option to filter for "Everything assigned to you" to focus on the tasks specifically assigned to him.\
This filter will help him efficiently manage his workload and address his assigned tasks promptly.
![](../../../_include/gfc/github/filters/img/E4Q41_1.png)

You can also use `is:open assignee:@me` in search bar to get same results.
![](../../../_include/gfc/github/filters/img/E4Q41_2.png)

You can also use this URL to directly to see all the active tasks in the repository.\
`https://github.com/<USER-NAME>/<REPO-NAME>/issues?q=is:open+assignee:@me`
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/filtering-and-searching-issues-and-pull-requests#filtering-issues-and-pull-requests
:::
::::

## Github CLI

::::{grid}
:::{grid-item-card}
Suppose you are leading a software development project on GitHub.\
To assist the team in prioritizing tasks and ensuring that critical issues are promptly addressed, you must compile a list of all issues without an assignee and bearing either the 'error' or 'bug' label, sorted by their creation date.\
Which of the following options, based on the provided reference, would help you accomplish this objective ?
:::

:::{grid-item-card}
* `gh issue list --search 'no:assignee labels:error,bug sort:created-asc'`
* `gh issue list --search --assignee=none --label=error --label=bug --sort=created-asc`
* `gh issue list --search --assignee=none --label=error,bug --sort=created-asc`
* {bdg-success}`Correct` `gh issue list --search 'no:assignee label:error,bug sort:created-asc'`
:::

:::{grid-item-card}
* `gh issue list --search 'no:assignee labels:error,bug sort:created-asc'`\
{bdg-danger}`Incorrect` erreur de typo de `label` qui est sans 's'.
* `gh issue list --search --assignee=none --label=error --label=bug --sort=created-asc`\
{bdg-danger}`Incorrect` a cause de l'option `--sort` qui n'existe pas.
* `gh issue list --search --assignee=none --label=error,bug --sort=created-asc`\
{bdg-danger}`Incorrect` a cause de l'option `--sort` qui n'existe pas.
* `gh issue list --search 'no:assignee label:error,bug sort:created-asc'`\
{bdg-success}`Correct`.
:::

:::{grid-item-card}
* https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/filtering-and-searching-issues-and-pull-requests?tool=cli#using-search-to-filter-issues-and-pull-requests
:::
::::
