# Authenticate

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

## A2F

::::{grid}
:::{grid-item-card}
Which option is not available for GitHub two-factor authentication ?
:::

:::{grid-item-card}
* GitHup Mobile.
* {bdg-success}`->` GitHub App.

```{danger}
*Attention au piège avec **GitHub Mobile** et **Authentication App** qui sont 2 méthodes valides*
```
* SMS.
* Security Key.
:::

:::{grid-item-card}
- **SMS**: Receive authentication codes via text message to a mobile phone number linked to your GitHub account.
- **Authentication App**: Use an authentication app like Google Authenticator, Authy, or similar apps to generate authentication codes.
- **Security Key**: Use a physical security key, such as a YubiKey, to provide an additional layer of security. This method is often considered more secure than SMS or authentication apps.
- **GitHub Mobile**: You can use GitHub Mobile for 2FA when signing into your GitHub account in a web browser. 2FA with GitHub Mobile does not rely on TOTP, and instead uses public-key cryptography to secure your account.
:::

:::{grid-item-card}
* https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication
:::
::::

::::{grid}
:::{grid-item-card}
Which of the following authentication methods is considered the most secure way to authenticate with 2FA on GitHub Enterprise ?
:::

:::{grid-item-card}
Security keys
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/code-security/supply-chain-security/end-to-end-supply-chain/securing-accounts
:::
::::

## PAT

::::{grid}
:::{grid-item-card}
What is the purpose of **P**ersonal **A**ccess **T**okens (PATs) in GitHub ?
:::

:::{grid-item-card}
To authenticate to GitHub API or command line.
:::

:::{grid-item-card}
Personal access tokens (PATs) in GitHub serve as an alternative to passwords for authentication when interacting with GitHub API or the command line.\
Users generate tokens and tie them to specific permissions for repositories or organizations.
:::

:::{grid-item-card}
* https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens
:::
::::

## SSO
::::{grid}
:::{grid-item-card}
How does SAML SSO work with GitHub Enterprise ?
:::

:::{grid-item-card}
Users are redirected to the Identity Provider (IdP) to authenticate.
:::

:::{grid-item-card}
With SAML SSO, when a user accesses resources within a GitHub organization, GitHub redirects the user to the identity provider (IdP) for authentication. After successful authentication, the IdP redirects the user back to GitHub to access organization resources.
```{admonition} Example
When an employee tries to access a repository in their organization's GitHub account, they are redirected to the company's login page to authenticate using their corporate credentials.
```
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/authenticate-authorize-user-identities-github/3-authentication
:::
::::

::::{grid}
:::{grid-item-card}
As the owner of your organization, you want to ensure that everyone who is signed in to your corporate network can access the GitHub website without having to sign in again.\
What type of technology would you use to achieve this?
:::

:::{grid-item-card}
Single sign-on (SSO).
:::

:::{grid-item-card}
* Single sign-on is the right technology to allow network users to access the GitHub website without extra sign-ins.
* Two-factor authentication requires each user to sign in by using a second means of identifying themselves, like using an authenticator app on their phones.
* Personal Access Tokens provide access for the git client or web API by using a cryptographic key. You don't use them to access the GitHub website.
* SSH keys provide access for the git client through a username and password. You don't use them to access the GitHub website.
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-gb/training/modules/github-introduction-administration/3-how-github-authentication-works
:::
::::

::::{grid}
:::{grid-item-card}
Which identity providers are supported for enabling team synchronization in GitHub ?
:::

:::{grid-item-card}
Microsoft Entra ID, Okta.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/enterprise-cloud@latest/organizations/managing-saml-single-sign-on-for-your-organization/managing-team-synchronization-for-your-organization#prerequisites
:::
::::

::::{grid}
:::{grid-item-card}
What permissions are required to enable team synchronization with Microsoft Entra ID ?
:::

:::{grid-item-card}
Read all user’s full profiles.
:::

:::{grid-item-card}
To enable team synchronization for Microsoft Entra ID, the installation needs the following permissions:
* Read all user’s full profiles.
* Sign in and read user profiles.
* Read directory data.
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/authenticate-authorize-user-identities-github/5-team-synchronization
:::
::::

::::{grid}
:::{grid-item-card}
Which protocol allows synchronization of user identity information between an identity provider (IdP) and GitHub ?
:::

:::{grid-item-card}
SCIM
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://learn.microsoft.com/en-us/training/modules/authenticate-authorize-user-identities-github/4-authorization
:::
::::

## Others
