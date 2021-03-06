Highly Scalable Angular Folder Structure
========================================

The project is inspired by the article on Medium called [How to define a highly scalable folder structure for your Angular project](https://itnext.io/choosing-a-highly-scalable-folder-structure-in-angular-d987de65ec7) by Mathis Garberg. The project is based on best practices from the community, other github Angular projects and developer experience from production Angular projects. 

![login screen screenshot](https://i.imgur.com/J1B3I02.jpg)


Documentation
-------------

[Read The Documentation](.documentation/index.rst) for details on each part of the directory structure.


Demonstration Application
-------------------------

[See The Application](https://mathisgarberg.github.io/angular-folder-structure/) in action.  


Install
-------

This project is an example of directory structure but it is also a working application.

This project assumes you have already created other projects for Angular on your system and have the required node and typescript libraries already installed.

After cloneing locally and `cd` to the project directory, install the node libraries:

```sh
  npm install
```


Scripts
-------

```
* npm start     -> Run dev. server on http://localhost:4200/
* npm run build -> Lint code and build app for production in dist folder
* npm run test  -> Run unit tests via Karma in watch mode
* npm test:ci   -> Lint code and run unit tests once for continuous integration
* npm run e2e   -> Run e2e tests using Protractor
* npm run lint  -> Lint code
```
