# gh_actions

GitHub Actions is a continuous integration tool that allows to automate tasks for repos.

### Different attributes of GitHub Actions

_name:_

- The name of the workflow
- Not required

_on:_

- webhooks

_jobs:_

- workflows must have at least one job
- each job must have a unique identifier
- job identifier must start with a letter or underscore
- jobs run in parallel by default

_runs-on:_

- dictates runners (an os version)

_steps:_

- tasks within a job
- run as processes on the compute resource
- access to file system in the virtual environment
- can run command/actions

_uses:_

- defines the Docker image that will run the Action.

- The “needs” attribute is used to establish dependencies between Actions in a Workflow.

### Automating with GitHub Actions

- Use this powerful tool to build workflows triggered by events

- Develop a continuous integration and continuous delivery (CI/CD) pipeline

- Create custom actions
