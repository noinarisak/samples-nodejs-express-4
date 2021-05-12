# GitPod baby!
## Start/open GitPod. Right right open browser

[![Gitpod ready-to-code](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#prebuild/https://github.com/noinarisak/samples-nodejs-express-4/tree/gitpod)

## Update and copy into the clipboard the following

> NOTE: Using `direnv` to load environment variables to GitPod workspace.

> NOTE: Inside GitPod workspace, the following `$ gp url` will get you the gitpod workspace url.

Create `.envrc` file with the following.

```bash
# Create
touch .envrc

# Update, copy & paste and save.
export ISSUER=https://[OKTA_ORG].okta.com/oauth2/default
export CLIENT_ID=0o...
export CLIENT_SECRET=eM9...
export APP_BASE_URL=https://[GITPOD_WORKPLACE_URL] #
```
