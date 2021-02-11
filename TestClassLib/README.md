## Authentication

1. The `GITHUB_TOKEN`

     - This token is intentionally scoped to the single repository that invoked the workflow, and has the same level of access as a write-access user on the repository. The token is created before each job begins and expires when the job is finished. For more information, see "Authenticating with the `GITHUB_TOKEN`."
     - The `GITHUB_TOKEN` should be used whenever possible.

---

Publish to GitHub artifacts securely using a GitHub Token:
https://docs.github.com/en/actions/reference/authentication-in-a-workflow