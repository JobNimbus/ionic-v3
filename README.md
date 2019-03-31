[![npm version](https://badge.fury.io/js/ionic-angular.svg)](https://badge.fury.io/js/ionic-angular)

### Getting Started

Start a new project by following our quick [Getting Started guide](https://ionicframework.com/getting-started/).
We would love to hear from you! If you have any feedback or run into issues using our framework, please file
an [issue](https://github.com/ionic-team/ionic-v3/issues/new) on this repository.

Fork source repo from GH (i.e. https://github.com/xxx/ionic-v3)
Clone new repo
Make changes
npm run-script link && sed -i.bak 's:ionic-angular:@namespace/ionic-angular:g' dist/ionic-angular/package.json && (cd dist/ionic-angular/ && npm publish)
npm login
npm publish
// Install custom npm module as "ionic-angular" (requires npm 6.9.0)
npm install ionic-angular@npm:@namespace/ionic-angular
Publish changes to forked repo