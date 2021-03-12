## 1

## References

- [What is DevOps?](https://docs.microsoft.com/azure/devops/learn/what-is-devops)
- [Bridging the gap between business and development](https://www.developer-tech.com/news/2016/jan/29/devops-bridging-gap-between-business-and-development/)
- [Pair programming](https://www.agilealliance.org/glossary/pairing/)

### Getting Started

There are numerous options for managing source code during this  OpenHack and in other DevOps activities. Many choose GitHub because of  its relationship to Open Source, however the advanced DevOps, security  and inner source capabilities may also help with your decision. Some  will choose Azure DevOps, or a combination of GitHub and Azure DevOps.  And others may choose other tools for work management, source control  and/or CI/CD.

> **Note:** If using GitHub or Azure DevOps, public repos and projects are recommended for the OpenHack as they offer additional benefits (*e.g.* additional concurrent CI/CD jobs, etc.)

- GitHub

  - [Setting up Git](https://help.github.com/github/getting-started-with-github/set-up-git#setting-up-git)
  - [Getting started with GitHub](https://help.github.com/github/getting-started-with-github)
  - [Creating a GitHub Organization](https://help.github.com/github/setting-up-and-managing-organizations-and-teams/creating-a-new-organization-from-scratch)
  - [Organizing work with Project Boards](https://help.github.com/github/managing-your-work-on-github/about-project-boards)
  - Managing work with [GitHub Issues](https://help.github.com/github/managing-your-work-on-github/about-issues) and [GitHub Projects](https://github.com/features/project-management)
  - [Improving code quality and security with GitHub Protected Branches](https://help.github.com/github/administering-a-repository/about-protected-branches)
  - [Linking GitHub Issues](https://help.github.com/github/writing-on-github/autolinked-references-and-urls#issues-and-pull-requests)
  - [Mastering GitHub Issues](https://guides.github.com/features/issues/)
  - [Closing issues via Pull Requests](https://github.blog/2013-05-14-closing-issues-via-pull-requests/)

- Azure DevOps

  - [Create an Azure DevOps organization](https://docs.microsoft.com/azure/devops/user-guide/sign-up-invite-teammates)
  - [What is Azure Boards?](https://docs.microsoft.com/azure/devops/boards/get-started/what-is-azure-boards)
  - [Integrating Azure Boards and GitHub](https://docs.microsoft.com/azure/devops/boards/github/?view=azure-devops)
  - [Improving code quality with Azure Repos branch policies](https://docs.microsoft.com/azure/devops/repos/git/branch-policies)
  - [Link work items to support traceability and manage dependencies](https://docs.microsoft.com/azure/devops/boards/queries/link-work-items-support-traceability)
  - [Link work items to GitHub Commits and Pull Requests](https://docs.microsoft.com/azure/devops/boards/github/link-to-from-github?view=azure-devops)

  > **Note:** You may have to review the permissions of each member of your team at the [organization and project level](https://docs.microsoft.com/azure/devops/organizations/security/index?view=azure-devops).

## 2

## References

A **Cheat sheet** for the DevOps OpenHack is available at the end of the **Overview** page.

> **Note**: Continuous Integration (CI) uses best practices including automated testing and ideally [trunk-based development](https://trunkbaseddevelopment.com/). Automated testing will be covered later and will extend the CI setup completed here.

- [What is Continuous Integration?](https://docs.microsoft.com/azure/devops/learn/what-is-continuous-integration)
- [Azure DevOps Engineering Release Flow](https://docs.microsoft.com/azure/devops/learn/devops-at-microsoft/release-flow)

### Work Management

- GitHub
  - [Organizing work with Project Boards](https://help.github.com/github/managing-your-work-on-github/about-project-boards)
  - [Managing Teams in GitHub](https://help.github.com/github/setting-up-and-managing-organizations-and-teams/about-teams)
  - Managing work with [GitHub Issues](https://help.github.com/github/managing-your-work-on-github/about-issues) and [GitHub Projects](https://github.com/features/project-management)
- Azure DevOps
  - [Azure Boards & GitHub](https://docs.microsoft.com/azure/devops/boards/github/?view=azure-devops)
  - [View and add work items using the Work Items page](https://docs.microsoft.com/azure/devops/boards/work-items/view-add-work-items)

### Branch protection

- GitHub
  - [GitHub - About protected Branches](https://help.github.com/articles/about-protected-branches)
  - [GitHub Code Owners](https://help.github.com/github/creating-cloning-and-archiving-repositories/about-code-owners)
- Azure DevOps
  - [Configure Branch Policies](https://docs.microsoft.com/azure/devops/repos/git/branch-policies)
  - [Code Reviewers](https://docs.microsoft.com/azure/devops/repos/git/branch-policies?view=azure-devops#automatically-include-code-reviewers)

## 3

## References

A cheat sheet for the DevOps OpenHack is available at the end of the **Overview** page.

- [What is Continuous Integration?](https://docs.microsoft.com/azure/devops/learn/what-is-continuous-integration)
- [Continuous Integration: What is CI? Testing, Software & Process Tutorial](https://codeship.com/continuous-integration-essentials)

### Workflow orchestration

[What is Pipeline as Code?](https://www.youtube.com/watch?v=C7NFwlmSAqU)

- GitHub:
  - [GitHub Actions](https://github.com/features/actions)
  - [GitHub Actions Schema and Syntax Reference](https://help.github.com/actions/reference)
- Azure DevOps
  - [Azure Pipelines](https://docs.microsoft.com/azure/devops/pipelines/get-started/what-is-azure-pipelines?view=azure-devops)
  - [Azure Pipelines Schema and Syntax Reference](https://docs.microsoft.com/azure/devops/pipelines/yaml-schema?view=azure-devops&tabs=schema%2Cparameter-schema)
- Jenkins:
  - [Creating a Jenkins pipeline](https://jenkins.io/doc/book/pipeline/)
  - [GitHub Permissions and API token scopes for Jenkins](https://support.cloudbees.com/hc/articles/234710368-GitHub-Permissions-and-API-token-Scopes-for-Jenkins)
  - [Known issue with Docker workflow plugin and multi stage builds](https://issues.jenkins-ci.org/browse/JENKINS-44609)

### Unit testing

- [Test Driven Development Essay](http://agiledata.org/essays/tdd.html)
- [Writing and running unit tests with GoLang](https://blog.alexellis.io/golang-writing-unit-tests/)
- [Writing and running unit tests with Node.JS](https://blog.risingstack.com/node-hero-node-js-unit-testing-tutorial/)
- [Writing and running units test with .Net Core](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-dotnet-test)
- [Writing and running unit tests with Java](https://www.vogella.com/tutorials/Mockito/article.html)

## 4

- Orchestrators
  - **[GitHub Actions](https://github.com/features/actions)**
  - **[ Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/)** Part of Azure DevOps, formerly known as Visual Studio Team Services (VSTS)
  - **[Jenkins](https://jenkins.io/)**
- Version Control
  - **[GitHub](https://github.com/)**
- Docker Registry
  - **[Azure Container Registry](https://azure.microsoft.com/services/container-registry/)**
  - **[GitHub Packages](https://github.com/features/packages)**

## References

- Continuous Delivery
  - [What is Continuous Delivery? ](https://docs.microsoft.com/azure/devops/learn/what-is-continuous-delivery)
  - [Why continuous delivery?](https://continuousdelivery.com/#why-continuous-delivery)
- Github
  - [GitHub Actions - Docker build and push](https://github.com/docker/build-push-action)
  - [GitHub Actions - Azure WebApp](https://github.com/marketplace/actions/azure-webapp)
- Azure Pipelines
  - [Azure Pipelines - Deploy a custom Linux container to Azure App Service](https://docs.microsoft.com/azure/app-service/containers/quickstart-docker)
  - [Azure Pipelines - Tutorial: Build a custom image and run in App Service from a private registry](https://docs.microsoft.com/azure/app-service/containers/tutorial-custom-docker-image)
  - [Azure Pipelines - Docker task](https://docs.microsoft.com/azure/devops/pipelines/tasks/build/docker?view=azure-devops)
- Docker Registries
  - [GitHub Packages Documentation](https://help.github.com/packages)
  - [Azure Container Registry documentation](https://docs.microsoft.com/azure/container-registry/)

##  5

## References

- [Blue/Green deployment](https://martinfowler.com/bliki/BlueGreenDeployment.html)
- [Staging environments in Azure App Service](https://docs.microsoft.com/azure/app-service/deploy-staging-slots)
- [Azure Slot Deployment with Blue-Green Deployment Model](https://medium.com/@sangeetavsunchu/azure-slot-deployment-with-blue-green-deployment-model-b52cd5ffaf07)

## 6

## References

### Azure resources

- Azure Monitor

  - [Overview of the Azure Monitoring solutions](https://docs.microsoft.com/azure/azure-monitor/overview)
  - [Getting started with Azure Monitor Log Analytics](https://docs.microsoft.com/azure/azure-monitor/log-query/get-started-portal)
  - [Monitoring Azure resources with Azure Monitor](https://docs.microsoft.com/azure/azure-monitor/insights/monitor-azure-resource)
  - [Monitor Azure App Service performance](https://docs.microsoft.com/azure/azure-monitor/app/azure-web-apps)
  - [Monitor Azure SQL Database using Azure SQL Analytics](https://docs.microsoft.com/azure/azure-monitor/insights/azure-sql)
  - [Create diagnostic setting to collect resource logs and metrics in Azure](https://docs.microsoft.com/Azure/app-service/web-sites-monitor)
  - [Monitor apps in Azure App Service](https://docs.microsoft.com/azure/azure-monitor/platform/diagnostic-settings)
  - [What is Application Insights?](https://docs.microsoft.com/azure/azure-monitor/platform/diagnostic-settings)
  - [Create, view, and manage log alerts using Azure Monitor](https://docs.microsoft.com/azure/azure-monitor/platform/alerts-log)
  - [Overview of alerts in Microsoft Azure](https://docs.microsoft.com/azure/azure-monitor/platform/alerts-overview)

- Azure Logic Apps

  - [Overview - What is Azure Logic Apps?](https://docs.microsoft.com/azure/logic-apps/logic-apps-overview)
  - [Azure DevOps Connector for Azure Logic Apps](https://docs.microsoft.com/connectors/visualstudioteamservices/)

- Kusto documentation and references

  :

  - The solutions in Azure will evolve to use [Azure Data Explorer query language](https://docs.microsoft.com/azure/kusto/query/) (also know as [Kusto](https://docs.microsoft.com/azure/kusto/query/))
  - Syntax for regular expressions supported by [Azure Data Explorer](https://docs.microsoft.com/azure/kusto/query/re2)

- Regular Expressions

  - You can test your regular expression on this site: [RegExr: Learn, Build, & Test RegEx](https://regexr.com/)

  - You can use regular expressions in the `extract()`  function in Kusto. For example, this code will extract and convert to a  double the response time from the container output showed above:

    ```
    todouble(extract(@"CreateTripPoint ([0-9.]*)ms", 1, LogEntry))
    ```

- Application availability and responsiveness

  - [Availability alerts of any web site](https://docs.microsoft.com/azure/azure-monitor/app/monitor-web-app-availability#alerts)

### Additional Reading

- [Azure Monitor overview](https://docs.microsoft.com/azure/azure-monitor/overview)
- [Application performance FAQs for Web Apps in Azure](https://docs.microsoft.com/azure/app-service/faq-availability-performance-application-issues)

## 7

## References

- Dependency Scanning
  - [GitHub Security Alerts](https://help.github.com/github/managing-security-vulnerabilities/about-security-alerts-for-vulnerable-dependencies)
  - [Automated Security Updates with GitHub](https://help.github.com/github/managing-security-vulnerabilities/configuring-automated-security-updates)
  - [Whitesource Bolt with Azure Pipelines](https://bolt.whitesourcesoftware.com/azure/faq/)
  - [OWASP Dependency Checker in the Azure DevOps marketplace](https://marketplace.visualstudio.com/items?itemName=dependency-check.dependencycheck)
- Code Coverage
  - [CoverAlls](https://coveralls.io/)
  - [CodeCov](https://codecov.io/)
  - [Jacoco](https://www.jacoco.org/jacoco/)
  - [CoverAlls for GitHub Actions](https://github.com/marketplace/actions/coveralls-github-action)
  - [Azure Pipelines ecosystem (per-language code coverage docs)](https://docs.microsoft.com/azure/devops/pipelines/ecosystems/?view=azure-devops)
  - [GitHub Coverage Reporter for Jenkins](https://github.com/jenkinsci/github-coverage-reporter-plugin)
- Static Code Analysis
  - [Linters in the GitHub Actions marketplace](https://github.com/marketplace?type=actions&query=lint)
  - [Static Code Analysis tools (Wikipedia)](https://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis)
  - [SonarCloud for GitHub Actions](https://github.com/marketplace/actions/sonarcloud-scan)
  - [Integrate Visual Studio Team Services with SonarCloud](https://docs.microsoft.com/labs/devops/sonarcloudlab/index)
  - [Using SonarCloud in an Azure DevOps pipeline](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Extension+for+VSTS-TFS)
- Variant Analysis (Security)
  - [Variant Analysis for Security](https://semmle.com/variant-analysis)
  - [Continuous security analysis (with GitHub and SEMMLE)](https://lgtm.com/)
- Integration Testing
  - [Integration testing](http://softwaretestingfundamentals.com/integration-testing/)
  - [Integration tests vs Unit tests](https://www.guru99.com/unit-test-vs-integration-test.html)
  - [Integration test with .Net Core](https://docs.microsoft.com/aspnet/core/test/integration-tests)
  - [Integration testing in GO](https://blog.codeship.com/testing-in-go/)
  - [Set up a go workspace](https://docs.microsoft.com/azure/devops/pipelines/languages/go#set-up-a-go-workspace)
  - [Integration testing with Node.JS](https://www.codementor.io/olatundegaruba/integration-testing-supertest-mocha-chai-6zbh6sefz)
- Load Testing
  - [Blazemeter with Azure Pipelines](https://guide.blazemeter.com/hc/en-us/articles/360004191957-Testing-via-Azure-DevOps-Pipeline-Testing-via-Azure-DevOps-Pipeline)
- Manual Approvals
  - [Setting up Webhooks for GitHub Actions](http://www.btellez.com/posts/triggering-github-actions-with-webhooks.html)
  - [GitHub Deployments (REST API)](https://developer.github.com/v3/repos/deployments/)
  - [Release approval gates for Azure Pipelines](https://docs.microsoft.com/azure/devops/pipelines/release/approvals/?view=azure-devops)
  - [Manual Intervention task for Azure Pipelines](https://docs.microsoft.com/azure/devops/pipelines/tasks/utility/manual-intervention?view=azure-devops)



## 8

## Reference

- Topical References
  - [Route traffic with Azure App Service and Deployment slots](https://docs.microsoft.com/azure/app-service/deploy-staging-slots#route-traffic)
  - [Explore how to progressively expose your Azure DevOps extension releases in production to validate, before impacting all users](https://docs.microsoft.com/azure/devops/migrate/phase-rollout-with-rings)
  - [Deployment considerations for DevOps](https://docs.microsoft.com/azure/architecture/framework/devops/deployment)
  - [Canary Deployments Using Azure Web App Deployment Slots](https://www.c-sharpcorner.com/blogs/doing-canary-deployments-using-azure-web-app-deployment-slots)
- GitHub
  - [GitHub Action Rollback Release](https://github.com/marketplace/actions/rollback-release)
  - [Context and expression syntax for GitHub Actions](https://help.github.com/actions/reference/context-and-expression-syntax-for-github-actions)
- Azure Pipelines
  - [How to implement rollback strategies in Azure Pipelines](https://mattvsts.github.io/2019/07/07/how-to-implement-rollback-strategies-in-azure-pipelines/)