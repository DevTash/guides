# Deploy DotNet Core 3.1 Container to Azure Function

## Pre-requisites
* Azure DevOps subscription
* Sample app - In this case we are deploying the identity server 4 sample
* Github account

### Clone Identity Server 4 sample app
To keep things simple we will use the [Identity Server 4 sample app](https://github.com/brockallen/IdentityServerAndApi) by [Brock Allen](https://github.com/brockallen).
<br>
<br>
Fork or download the repository. If you downloaded the code, ensure you have pushed to source control.


### Setting up the pipeline
1. Login to Azure DevOps and navigate to your desired project.
2. Select to pipelines from the side bar
3. Create a new pipeline by clicking 'New pipeline'

#### Linking Github to Azure DevOps (optional)
1. Select Github
2. Authorize Azure Pipelines
<br>
<br>

4. Select the repository containing the sample app source
5. Approve and install Azure Pipelines
6. Authorize Azure Pipelines
7. Select the repository containing the sample app source
8. https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/containers/build-image?view=azure-devops
