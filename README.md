# my-event-workflow-demo

Demo del curso DevOps y GitHub Actions - MLOps con Python.

Workflow `.github/workflows/my-event-workflow.yaml`:

- Trigger: `pull_request` tipo `opened` hacia `main`.
- Jobs `model-ci` y `model-cd` corren en paralelo.
feat: demo
