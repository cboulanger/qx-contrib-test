# Test Contrib

This is a qooxdoo contrib solely meant for testing the qooxdoo contrib system. It doesn't 
come with a package.json but expects a globally installed qxcompiler package that gets linked
to the project.

## Install and test
skip all unneeded install commands):

```
nvm install 8 # (or 10) to install node, skip if already installed
npm install -g qxcompiler # this also installs qooxdoo-sdk, skip if already installed
npm link qxcompiler
npm link qooxdoo-sdk
qx compile
```

## Publish
```
qx contrib publish --token <GITHUB-TOKEN>
```