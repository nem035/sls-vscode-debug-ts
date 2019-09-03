# Serverless VSCode Debug TypeScript

Demo project on setting up a serverless API on [API Gateway](https://aws.amazon.com/api-gateway/) using the [serverless framework](https://serverless.com/), [typescript](https://www.typescriptlang.org) and [VSCode](https://code.visualstudio.com/) for debugging (breakpoints yay!).

Local development is executed with the [`serverless-offline`](https://github.com/dherault/serverless-offline) plugin.

## Installation

```sh
git clone https://github.com/nem035/sls-vscode-debug-ts
cd sls-vscode-debug-ts
npm i
```

## Requirements

- [Setup VSCode debugging](https://code.visualstudio.com/docs/editor/debugging)

## Debugging

1. Set a breakpoint within `hello` handler
2. Press the VSCode debug button
3. Make a request to the `/hello` endpoint

