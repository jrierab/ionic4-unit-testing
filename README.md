# ionic4-unit-testing

[Català](#català)
[English](#english)

## English

Ionic 4 application based on tabs (using default configuration), readily prepared to conduct unit testing.

### Install

1. Install NVM (*Node Version Manager*) from [https://github.com/creationix/nvm](https://github.com/creationix/nvm)

2. Install [Node](https://nodejs.org)

```
nvm install latest
```

3. Install [Ionic](https://ionicframework.com/)

```
npm install -g ionic
```
4. Create a new Ionic 4 application (with tabs, no Ionic Appflow SDK and default configuration)

```
ionic start ionic4-unit-testing
cd ionic4-unit-testing
```

or clone this repo and install dependencies:

```
git clone https://github.com/jrierab/ionic4-unit-testing.git
cd ionic4-unit-testing
npm install
```

### Build

1. Test on browser

```
ionic serve -c -s
```

2. Run unit testing

```
npm test
```

3. Run end-to-end testing

```
npm run e2e
```

## Català

Aplicació Ionic 4 basada amb pestanyes (configuració per defecte), ja preparada per realitzar tests unitaris.

[Instal·lació](#install)
[Execució](#build)
