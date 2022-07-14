# gh_actions

GitHub Actions is a continuous integration tool that allows developers to automate tasks for their web projects.



### Different attributes of GitHub Actions

*name:*
- The name of the workflow
- Not required

*on:*
- webhooks

*jobs:*
- each job must have a identifier

*runs-on:*
- dictates runners (an os version)

*steps:*
- access to file system in the virtual environment
- dictates actions/run

*uses:*
- defines the Docker image that will run the Action.


Create a workflow
  Workflows 
- define the event that triggers actions
- define which action to run

Repositories can contain multiple workflows based on different events 


### Automating with GitHub Actions


- Use this powerful tool to build workflows triggered by events

- Develop a continuous integration and continuous delivery (CI/CD) pipeline

- Create custom actions

