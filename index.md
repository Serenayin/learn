# New Starter
## GitHub Actions
### <a href="https://Serenayin.github.io/learn/github-actions-demo/index.html" title="Demo of REACT APP">Demo of REACT APP</a>

action of checkout will make a copy of repo in the github workspace directory path(which will make the path to something like /home/runner/work/repo/repo/... by default)[https://github.community/t/paths-and-environment-variables-in-artifact-paths/16944](https://github.community/t/paths-and-environment-variables-in-artifact-paths/16944)

### sub-project key point

1.use working-directory to assign shell the directory to run in;
2.specify relative path in "folder" of "JamesIves/github-pages-deploy-action" Build or things like that.
3.specify target-folder of deployment to meet with the same route of homepage url defined in package.json(react app).(github pages deploy according to file structure)

## Webhooks
### smee
$ smee -u https://smee.io/wSIFtllnAJ1nToM7 --path /events

Forwarding https://smee.io/wSIFtllnAJ1nToM7 to http://127.0.0.1:3000/events

### bundler
check BUNDLED_WITH version in Gemfile.lock, otherwise Error may raise because of version mismatch.
