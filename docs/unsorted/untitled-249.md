# Enable permissions for Snyk Broker from your third-party tool

1. [Docs Library \| Snyk](https://github.com/snyk/user-docs/tree/58f91d848e16ddf2ffcca3711d6b8852412be402/hc/en-us/README.md)
2. [Integrations](https://github.com/snyk/user-docs/tree/58f91d848e16ddf2ffcca3711d6b8852412be402/hc/en-us/categories/360000598398-Integrations/README.md)
3. [Snyk Broker](https://github.com/snyk/user-docs/tree/58f91d848e16ddf2ffcca3711d6b8852412be402/hc/en-us/sections/360001138138-Snyk-Broker/README.md)

## Enable permissions for Snyk Broker from your third-party tool

### Assign permissions components

Assign permissions based on your integration as follows:

* [**GitHub / GitHub Enterprise**](https://github.com/settings/tokens): see [GitHub integration](https://support.snyk.io/hc/en-us/articles/360004032117-GitHub-integration).
* [**Bitbucket server**](https://confluence.atlassian.com/bitbucket/grant-repository-access-to-users-and-groups-221449716.html)**:** see [Bitbucket Server integration](https://support.snyk.io/hc/en-us/articles/360004002218-Bitbucket-Server-integration). 
* [**GitLab**](https://docs.gitlab.com/ee/user/profile/personal_access_tokens.html): see [GitLab integration](https://support.snyk.io/hc/en-us/articles/360004002238-GitLab-integration).
* [**Azure Repos**](https://docs.microsoft.com/en-us/azure/devops/repos/): see [Azure Repos integration](https://support.snyk.io/hc/en-us/articles/360004002198-Azure-Repos-integration).
* [**Jira**](https://confluence.atlassian.com/cloud/api-tokens-938839638.html): Snyk needs user credentials with API access. See [Jira integration](https://support.snyk.io/hc/en-us/articles/360004002458-Jira). 

### Generate credentials in the target application for Snyk Broker

After generating the credentials for the Broker's target application, configure the environment variables for launching the Broker.

* 