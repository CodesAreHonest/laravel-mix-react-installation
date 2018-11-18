# React with Laravel
> A demonstration for installation of React into Laravel with Laravel Mix

React - 16.6.*  
React DOM - 16.6.*  
React Router DOM - 16.6.*  

# Installation
> Please ensure you have install NodeJS and NPM in your machine before perform the following steps (brew install node)

a. Create Laravel Project in specific version (5.5.28) with Composer.

```bash
composer create-project laravel/laravel react-laravel 5.5.*
```

b. If prefer to use React to buld your JavaScript Application, use **preset** command to replace Vue with **React Scaffolding**.

```bash
php artisan preset react
```

c. Add **cross-env** package into package.json. The package take cares of the setting and configure environment variable in various Environment.

```bash
npm install cross-env --save-dev
```

d. Create Node Modules into Laravel Project, a package management directory that contains the installed packages locally with NPM.

```bash
npm install
```

e. Compile React JSX into ES5, SASS into CSS and other require dependencies and configuration into assets.

```bash
npm run dev
```

f. Watch React JSX and SASS file during development and re-compiled once a single changes is made.

```bash
npm run watch
```

g. (Optional) Hot Reload :)

```bash
npm run hot
```
