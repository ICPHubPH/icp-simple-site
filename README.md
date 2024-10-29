# ICP Simple Site Frontend Boilerplate

This template gives you everything you need to build a full-stack Web3 application on the [Internet Computer](https://internetcomputer.org/).
It includes a frontend built with Vite and React, and a backend written in JS/TS (Azle).

## Get started with one click:

### Locally:

Make sure you have you have the latest version of Docker (e.g. >25) and VS Code installed and running, then click the button below

[![Open locally in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/ICPHubPH/icp-simple-site)

### In your browser:

In Gitpod

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/ICPHubPH/icp-simple-site/)

## 🚀 Develop

When the editor opened, run the following commands to start a local ICP node and deploy the canister smart contract:

```bash
dfx start --clean # Start a local ICP node
# In a new terminal window:
dfx deploy # Deploy smart contract locally
```

To redeploy the smart contract, run `dfx deploy` again.

When ready, run `dfx deploy --playground` to deploy your application to the ICP playground.

## 💡 Tips and Tricks

- If you get an error "Error: An error happened during communication with the replica: ... Connection refused", run `dfx start --clean` to start dfx.
