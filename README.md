# node-repl

This is a project for testing node scripts. These scripts can be run locally or in a docker container.

## Local Usage

```
npm i
node scripts/<script-name>.js
```

## Docker Usage

```
docker build -t node-repl .
docker run -it node-repl
```

A docker container will be started and you'll be taken to the zsh terminal.

```
node scripts/<script-name>.js
```

You can run the docker container with a lower amount of memory using the `-m` command.

`docker run -m 512m -it node-repl`