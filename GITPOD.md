# GitPod baby!
## Quickstart-ish

Right-click "Open Link in New Tab", to launch GitPod workspace instance.

[![Gitpod ready-to-code](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#prebuild/https://github.com/noinarisak/samples-nodejs-express-4/tree/gitpod)

Setup/configure Okta tenant and `.envrc` file inside GitPod workspace terminal.

> NOTE: Using `direnv` to load environment variables inside your GitPod workspace.

Create `.envrc` file with the following.

```bash
# Create
touch .envrc

# Get GitPod Workspace URL
$ gp url

# Update, copy & paste and save.
export ISSUER=https://[OKTA_ORG].okta.com/oauth2/default
export CLIENT_ID=0o...
export CLIENT_SECRET=eM9...
export APP_BASE_URL=https://[GITPOD_WORKPLACE_URL] #
```
