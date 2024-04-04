# Welcome to docs contributing guide

- We are using [Redocly](https://redocly.com/) to generate the document page.

- In this file will let you know about 2 parts:

 1. Development
 2. Production


## 1. Development

1. Install [Node JS](https://nodejs.org/).
2. Clone this repo and run `npm install` in the repo root.

### Usage

#### `npm start`
Starts the reference docs preview server.

#### `npm run build`
Bundles the definition to the dist folder.

#### `npm test`
Validates the definition.

#### Add/Edit API

We are following the rule [OpenAPI 3.1.0](https://github.com/OAI/OpenAPI-Specification/tree/main/versions/3.1.0.md)

#### Preview
After running the `npm start`, we will have a local link to access the preview. (http://127.0.0.1:8080)

## 2. Production

After merging a Pull Request or pushing a commit to branch `main`, `Redocs` will trigger a deployment scenario and build the latest version for us. Go to the [application panel](https://app.redocly.com/) of redocs to see the progress.

After that, we will have the latest version of the document.
Production URL: https://mtinbox-docs.marinetraffic.com/
