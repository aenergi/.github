# Hi, welcome to Å Energi @ GitHub!

It's a pleasure to have you join our organisation on GitHub. We have a few important things you should check out before you continue, to ensure that we all work well together.

## Verified Domain E-mail

For team syncronization to work, you need to ensure you have your corporate e-mail address added and verified.

Navigate here to add your corporate e-mail address: [https://github.com/settings/emails](https://github.com/settings/emails)

## Repository Migration

Migration of git repositories from Azure DevOps to GitHub can be provided by Sondre Bjellås. Contact Sondre on Teams and provide the following information:

- DevOps instance name
- Team project name
- Repository name (DevOps)
- Repository name (GitHub)

Repositories will be set to internal visibility by default, which means it's accessible to all developers in ther organisation. If you want a different (private), please let us know.

## Creating new repositories

Make sure you follow the naming guidelines when you create a new repository. This helps us keep a nice and tidy setup where everyone can more easily find the various repositories. Remember that all repositories is a flat structure.

Everyone invited to our GitHub organisation have read access to all repositories. If this is not acceptable for your needs, the repository can be made "private" instead of the default "internal".

After you make a repository, make sure your team is given access to it.

## Naming conventions

### Repositories

1. Prefix repos with the team or product name.
2. All lower-case naming.
3. Add as many sections with dashes (-) that makes sense.
4. Don't put product specific names in repos, e.g. "arm", "bicep" or "oracle", use generic terminology like "infra" and "db".
5. Attempt to rely on mono-repo if possible and rely on GitHub Actions with filters to trigger different workflows.

Examples: "devex-infra-corp", "devex-infra-online"

### Teams

Teams should be written with their names in a normal form, with the capitalization that is used and without any special prefix.

Examples: "DevEx" and "Flextools".

The GitHub teams are connected to Entra ID groups, which follows a different naming convention:

Examples: "g-gh-devex" and "g-gh-flextools".

Membership in teams are managed using Entra ID groups, not manually on GitHub.

Sometimes a team member must be removed and added to an Entra ID Group for sync to work properly. The user needs to signup for GitHub, before being added to the team group.

## Team Syncronization

Teams are automatically synced based upon membership on Entra ID groups. When you manage access control on GitHub, give access to Teams, not individual users.


## GitHub Copilot

To use GitHub Copilot, you must first actiev the license on your GitHub account and associating it with Å Energi.

[Getting started with GitHub Copilot](https://docs.github.com/en/copilot/using-github-copilot/getting-started-with-github-copilot)
