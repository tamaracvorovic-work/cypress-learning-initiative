# CYPRESS

# Installation
You need to have project folder with source code on your local machine.
You have two option to install Cypress:
1. ### Install Cypress via `npm` (recommended):
    `cd /your/project/path`
    
    `npm install cypress --save-dev`
    
    This will install Cypress locally as a dev dependency for your project.
    NOTE: Make sure that you have already run `npm init` or have a `node_modules` folder or `package.json` file in the root of your project to ensure cypress is installed in the correct directory.
2. ### Installing Cypress via `yarn`:
    `cd /your/project/path`
    
    `yarn add cypress --dev`
3. ### Direct download:
    If you’re not using Node or npm in your project or you want to try Cypress out quickly, you can always [download Cypress directly from Cypress CDN](https://download.cypress.io/desktop). The direct download will always grab the latest available version. Your platform will be detected automatically. Then you can manually unzip and double click. Cypress will run without needing to install any dependencies.

# Opening Cypress
If you used `npm` to install, Cypress has now been installed to your `./node_modules` directory, with its binary executable accessible from `./node_modules/.bin`.

You can open Cypress from your project root one of the following ways:
1. The long way with the full path: `./node_modules/.bin/cypress open`
2. Or with the shortcut using `npm bin`: `$(npm bin)/cypress open`
3. Or by using `yarn`: `yarn run cypress open`

# Switching Browsers
The Cypress Test Runner attempts to find all compatible browsers on the user’s machine. The drop-down to select a different browser is in the top right corner of the Test Runner.
