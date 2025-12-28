# SSO

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

::::{grid}
:::{grid-item-card}
How does SAML SSO work with GitHub Enterprise ?
:::

:::{grid-item-card}
Users are redirected to the Identity Provider (IdP) to authenticate.
:::

:::{grid-item-card}
With SAML SSO, when a user accesses resources within a GitHub organization, GitHub redirects the user to the identity provider (IdP) for authentication. After successful authentication, the IdP redirects the user back to GitHub to access organization resources.\
{bdg-primary}`Example`

When an employee tries to access a repository in their organization's GitHub account, they are redirected to the company's login page to authenticate using their corporate credentials.
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/authenticate-authorize-user-identities-github/3-authentication
:::
::::
