# michaeljennings-website
Portfolio website of Michael Jennings at [http://michaeljennings.azurewebsites.net](http://michaeljennings.azurewebsites.net)

## Setup
- Clone or fork this repository.
- Make sure you have [node.js](https://nodejs.org/) installed.
- Run `npm install -g webpack webpack-dev-server typings typescript` to install global dependencies.
- Optionally, make sure global dependencies are up-to-date by running `npm update -g`.
- Run `npm install` to install local dependencies.
- Run `npm run typings-install` to install typings.
- Run `npm start` to start up the dev server.
- Point your browser to `http://localhost:3000`. Optionally, specify a port by supplying the `PORT` env variable.

## Deploy to Azure
- Make sure you have [Azure CLI](https://azure.microsoft.com/en-us/documentation/articles/xplat-cli-install/) installed.
- Run `azure site create [sitename] --git` to create the target website in Azure.
- Run `azure site set -w` to enable web sockets for the Azure app (disabled by default).
