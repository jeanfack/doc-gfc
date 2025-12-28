# Account

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
What are the differences between organization members and external collaborators in GitHub ?
:::

:::{grid-item-card}
External collaborators cannot be team maintainers.
:::

:::{grid-item-card}
:::

:::{grid-item-card}
* https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-outside-collaborators/adding-outside-collaborators-to-repositories-in-your-organization
:::
::::

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

