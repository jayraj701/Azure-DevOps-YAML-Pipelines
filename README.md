# Azure-DevOps-YAML-Pipelines
YAML source controlled pipelines for Pull Request, Continues Integration, Continues Deployments

## PR- Pull Request Pipeline

### CI-CD :
Continues integration on Main branch to build & produce deployable artifact and initiate deployment on Test Resources and then wait for approval before deploying on Live include blue-green deployment style.

## Provisioning:

### Provisioningn Pipeline:
YAML pipeline to execute Provisioning ARM templates on Test and Live resource groups with manual validation to avoid unknown infrastructure modification
### Provisioning Script:
ARM template with paramter file to create App Service to deploy Angular Application with deployment slot and Application Insight
