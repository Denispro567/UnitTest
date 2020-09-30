## Instructions to recreate unitTest in the simplest form:
> **for bash CLI**

*npm stands for Node Package Manager, which should be installed beforehand*
*"sum.js" is a main program; similar should already be placed*
*"sum.test.js" implements JEST testing framework*

### Steps:

1. "mkdir SimpleUnitTest" create directory;
2. "cd SimpleUnitTest" change working directory;
3. "npm init" to create package.json
4. "npm install --save-dev jest" to add node_modeles
5.  add to package.json file this part:
```
  "scripts": {
    "test": "jest"
  }
```
6. examine result with command "npm run test"

