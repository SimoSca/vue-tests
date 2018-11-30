VUEJS
=====

Semplice repository per svolgere alcuni test su Vue.js.


KickOff
-------

Per iniziare in maniera completa non mi limitero' a caricare **Vue** tramite links e cdn, ma provero' direttamente coi componenti.

Per dettagli vedere [https://vuejs.org/v2/guide/single-file-components.html](https://vuejs.org/v2/guide/single-file-components.html).

Oltre a quello l'altra parte importante per cui uso NPM e' per poter avere anche `ecmascript 2015` o oltre.


### Suggerimenti

Per iniziare mi ispirero' a uno dei templates riportati in 

- [https://github.com/vuejs-templates](https://github.com/vuejs-templates)

in particolare provo i seguenti:

````bash
$ npm install -g vue-cli
$ vue init webpack my-project (es: default-cli-webpack-template)
$ cd my-project
$ npm install
$ npm run dev
````


In ogni caso per approfondimenti posso provare a leggere questi:

- [vue-loader](https://vue-loader-v14.vuejs.org/en/)


PROJECTS
--------

#### default-cli-webpack-template

In questo progetto ho detto di no a tutto, nello specifico ho output:

````bash
Project name default-cli-webpack-template
? Project description A Vue.js project
? Author Simone Scardoni <>
? Vue build standalone
? Install vue-router? No
? Use ESLint to lint your code? No
? Set up unit tests No
? Setup e2e tests with Nightwatch? No
? Should we run `npm install` for you after the project has been created? (recommended) no

   vue-cli · Generated "default-cli-webpack-template".

# Project initialization finished!
````

#### default-cli-webpack-template-allyes

````bash
? Project name default-cli-webpack-template-allyes
? Project description A Vue.js project
? Author Simone Scardoni <>
? Vue build standalone
? Install vue-router? Yes
? Use ESLint to lint your code? Yes
? Pick an ESLint preset Standard
? Set up unit tests Yes
? Pick a test runner jest
? Setup e2e tests with Nightwatch? Yes
? Should we run `npm install` for you after the project has been created? (recommended) npm

   vue-cli · Generated "default-cli-webpack-template-allyes".


# Installing project dependencies ...
````

In questa prima fase puo' essere utile confrontantare le differenze tra le due configurazioni, in particolare:

- in un caso ho la directory `test`, nell'altro no
- in un `.babelrc` ho anche la parte di configurazione relativa ai tests, nell'altro no
- in uno ho anche la parte relativa a `.eslint...`, nell'altro no
- i due `package.json` hanno alcune differenze

Il resto e' identico.
