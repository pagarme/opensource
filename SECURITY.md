# Security

## before turning a private repository to public
- Check if there is any sensitive data on the code and commit history
- Add a SECURITY.md using the [template](../template/SECURITY.md). If necessary, make changes to it.
- Add security testing (sonarqube, snyk.io, etc..). Make sure there isn't any serious vulnerability pointed by those tests. The Security-team can help you with that.

## for opensource repositories
- Never store credentials hardcoded or env/config files in GitHub.
- Block sensitive data being pushed to the remote repo by creating a template and adding .gitignore file
Example:
```sh
cp env.template env
echo 'env' >> .gitignore
```

## If sensitive data is made public:
- If possible, invalidate the sensive data (token, password, api-key, etc.) as soon as possible.
- Remove the info and clear Github history ([force push rewrite history](https://help.github.com/articles/removing-sensitive-data-from-a-repository/))
- Assess the impact of leaked data.

Based/inspired on 
1. Snyk Github Security Best Practices (https://res.cloudinary.com/snyk/image/upload/v1535626770/blog/10_GitHub_Security_Best_Practices_cheat_sheet.pdf)
2. Github Opensource Guide (https://github.com/github/opensource.guide) 
