# Update a repo with a set of pre-defined PR labels
## Usage
- Create a a Personal access tokens for using with github API ([instructions](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/)). This token should have access to the repository you want to update. Example token scope:
```
[v] repo  Full control of private repositories
  [v] repo:status  Access commit status
  [v] repo_deployment  Access deployment status
  [v] public_repo  Access public repositories
  [v] repo:invite  Access repository invitations
```
- Download the `github-labels.sh` script from the repo (or clone the whole repo)
- Run the script: `> sh github-labels.sh`
- When asked by the script, paste the access token
- Specify the repository name in the format "org/repo" (e.g. `visually/some-repo`)
