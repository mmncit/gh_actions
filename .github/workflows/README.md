# Workflows

- define the event that triggers actions
- define which action to run

create a workflow

```console
mkdir -p .github/workflows
```

Repositories can contain multiple workflows based on different events

Adding dependencies:

- needs: Identifies one or more jobs that must complete successfully before a job will run

To prevent infinite loops, one workflow's actions can't trigger another workflow.
