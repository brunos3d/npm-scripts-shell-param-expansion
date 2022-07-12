# npm-scripts-shell-param-expansion

This is just a study repo about npm scripts and bash parameter expansion, it contains some examples of using env-vars as scripts, it also includes concurrently to run all scripts.

I created it to understand some behaviours of npm scripts and use it with Nx monorepos and heroku

## With "all" as fallback

Running only backend

```bash
PROJECT_NAME=backend npm run start
```

Running only frontend

```bash
PROJECT_NAME=frontend npm run start
```

Running all apps

```bash
npm run start
```

## concurrently build

Building backend

```bash
PROJECT_NAME=backend npm run build
```

Building frontend

```bash
PROJECT_NAME=frontend npm run build
```

Building all apps

```bash
npm run build
```

## Refs

https://www.gnu.org/software/bash/manual/html_node/Shell-Parameter-Expansion.html
https://stackoverflow.com/questions/2013547/assigning-default-values-to-shell-variables-with-a-single-command-in-bash
