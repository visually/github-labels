# Update a repo with a set of pre-defined PR labels
## Usage
- Create a a Personal access tokens for using with github API ([instructions](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/)). This token should have access to the repository you want to update.
- Download the `github-labels.sh` script from the repo (or clone the whole repo)
- Run the script: `> sh github-labels.sh`
- When asked by the script, paste the access token
- Specify the repository name in the format "org/repo" (e.g. `visually/some-repo`)
