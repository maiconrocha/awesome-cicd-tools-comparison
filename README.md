# awesome-cicd-tools-comparison
Feature Comparison between popular CI/CD Tools

|                                                     | Gitlab               | Github                | Bitbucket             | AWS CI/CD Tools      | Azure DevOps         | Buildkite             | Jenkins              |
| --------------------------------------------------- | -------------------- | --------------------- | --------------------- | -------------------- | -------------------- | --------------------- | -------------------- |
| Feature                                             | Free                 | Premium               | Ultimate              | Free                 | Team                 | Enterprise            | Free                 | Standard | Premium | CodeCommit/CodeBuild/CodeDeploy/Codepipeline | Stakeholders (Free) | Basic | Basic + Test plans | Open Source<br> | Open Source Plan | Teams Plan<br> | Enterprise Plan<br> |  |
| CI/CD Minutes per month                             | 400                  | 100000                | 50000                 | 2000                 | 3000                 | 50000                 | 50                   | 2500 | 3500 | Unlimited | 1800 minutes using Microsoft-hosted agents,<br>unlimited using self hosted agents | Unlimited | Unlimited | Unlimited | Unlimited |
| Private Repositores                                 | Unlimited            | Unlimited             | Unlimited             | Unlimited            | Unlimited            | Unlimited             | Unlimited            | Unlimited | Unlimited | Maximum of 1,000 per Amazon Web Services account. This limit can be changed. |  | Unlimited | Unlimited | Unlimited |  | X | X | X |
| Public Repositories                                 | Unlimited            | Unlimited             | Unlimited             | Unlimited            | Unlimited            | Unlimited             | Unlimited            | Unlimited | Unlimited | Maximum of 1,000 per Amazon Web Services account. This limit can be changed. |  | Unlimited | Unlimited | Unlimited | X | X | X | X |
| Storage                                             | 10Gb per project     | 10Gb per project      | 10Gb per project      | 500Mb per project    | 2GB per project      | 50GB per project      | 2GB                  | 4GB | 4GB | Unlimited | Unlimited | Unlimited | Unlimited | Unlimited | Unlimited ? | Unlimited ? | Unlimited ? | Unlimited |
| Number of Users                                     | Unlimited            | Unlimited             | Unlimited             | Unlimited            | Unlimited            | Unlimited             | 5                    | 1-100 users | 1-100 users | Unlimited | 5 | Unlimited | Unlimited | Unlimited |  | 200 | 100 - ? |  |
| Pricing                                             | $0<br>per user/month | $19<br>per user/month | $99<br>per user/month | $0<br>per user/month | $4<br>per user/month | $21<br>per user/month | $0<br>per user/month | $3<br>per user/month | $6<br>per user/month | AWS CodePipeline costs $1.00 per active pipeline\* per month<br>AWS CodeBuild offers three compute instance types with different amounts of memory and CPU.<br>Charges vary by the compute instance type that you choose for your build.<br>For CodeDeploy on EC2, Lambda, ECS:<br>There is no additional charge for code deployments to Amazon EC2,<br>AWS Lambda or Amazon ECS through AWS CodeDeploy. | Free | First 5 users free,<br>then $6 per user per month | $52 per user<br>per month |  | 0 | $15 per user, per month | $30 per user, per month | Open Source and free, but have to pay for hosting resources |
| Built-in CI/CD                                      | X                    | X                     | X                     |                      |                      |                       | X                    | X | X |  | X | X | X | X | X | X | X | X |
| CI/CD for external repo                             |                      | X                     | X                     |                      |                      |                       |                      |  |  | X | X | X | X | X | X | X | X | X |
| Run Build inside a container                        | X                    | X                     | X                     | X                    | X                    | X                     | X                    | X | X | X | X | X | X | X | X | X | X | X |
| Manual approve/deny action for deployment jobs      | X                    | X                     | X                     |                      |                      | X                     | X                    | X | X | X | X | X | X | X | X | X | X | X |
| Parent-child pipelines                              | X                    | X                     | X                     |                      |                      |                       |                      |  |  | X | X | X | X | X | X | X | X |  |
| Hosted or self-managed Runners                      | X                    | X                     | X                     | X                    | X                    | X                     | X                    | X | X | X | X | X | X | X | X | X | X |  |
| CI/CD Horizontal Autoscaling                        | X                    | X                     | X                     |                      |                      |                       |                      |  |  | X | X | X | X | X | X | X | X |  |
| Scheduled triggering of pipelines                   | X                    | X                     | X                     | X                    | X                    | X                     | X                    | X | X | X | X | X | X | X | X | X | X |  |
| Protected variables                                 | X                    | X                     | X                     | X                    | X                    | X                     | X                    | X | X | X | X | X | X | X |  |  |  |  |
| Group-level variables                               |                      | X                     | X                     |                      |                      | X                     |                      |  |  | X | X | X | X | X |  |  |  |  |
| Customizable path for CI/CD configuration           | X                    | X                     | X                     |                      |                      |                       |                      |  |  |  | X | X | X | X |  |  |  |  |
| Run CI/CD jobs on Windows                           |                      | X                     | X                     |                      |                      |                       |                      |  |  | X | X | X | X | X | X | X | X | X |
| Run CI/CD jobs on macOS                             | X                    | X                     | X                     | X                    | X                    | X                     |                      |  |  |  | X | X | X | X | X | X | X | X |
| Run CI/CD jobs on Linux ARM                         |                      | X                     | X                     |                      |                      |                       |                      |  |  | X | X | X | X | X | X | X | X | X |
| Protected Runners                                   | X                    | X                     | X                     |                      |                      |                       |                      |  |  |  |  |  |  |  |  |  |  |  |
| Include external files in CI/CD pipeline definition |                      | X                     | X                     |                      |                      |                       |                      |  |  |  | X | X | X | X | X | X | X |  |
| Explicit support for monorepos                      |                      | X                     | X                     | X                    | X                    | X                     |                      |  |  | X | X | X | X | X | X | X | X |  |
| Pipeline Resource Groups                            | X                    | X                     | X                     |                      |                      |                       |                      |  |  |  | X | X | X | X | X | X | X |  |
| Pipeline as a Code                                  | X                    | X                     | X                     | X                    | X                    | X                     | X                    | X | X |  | X | X | X | X | X | X | X | X |
| Store CI configuration outside the repository       | X                    | X                     | X                     |                      |                      |                       | X                    | X | X |  |  |  |  |  |  |  |  |  |
| Cross-project jobs with artifact dependencies       |                      | X                     | X                     |                      |                      |                       |                      |  |  |  |  |  |  |  |  |  |  |  |
| Ability to deploy failed steps only                 |                      |                       |                       |                      |                      |                       | X                    | X | X | X | X | X | X | X | X | X | X |  |
| OpenID Connect Support                              | X                    | X                     | X                     | X                    | X                    | X                     | X                    | X | X |  | X | X | X | X |  |  |  |
