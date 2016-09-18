# Coding WebIDE Frontend

This repo contains frontend code of the Coding WebIDE Community Edition. Please refer to the WebIDE-Workspace repo for instruction on running the project.

## Requirement

The repo is written in ES2015, to avoid complications once and for all, please make sure your environment have the right version of node. We use:

- node **v6.x**
- npm **v3.x**


## Development

To start development on this repo, run:
```
npm install
npm start
```

## Configuration

By default the backend host is set to `http://localhost:8080` and can be changed from `app/config.js`. `webpack-dev-server` serves on port 8060, which is specified in `package.json`.
