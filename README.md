# Angular for dummy


1 - Install nodejs

```bash
$ apt install curl apt-transport-https

$ curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash 

$ apt install -y nodejs

$ npm install --global npm@latest
```

## Now First way to install Angular

## 1 - Clone quickstart

```bash
$ git clone https://github.com/angular/quickstart

$ cd quickstart/
```

## 2 - Install dependencies

```bash
$ npm install
```

## 3 - Run Server :: hello word

Prevent opening browser on npm start in the file ```package.json``` in the key add to script "serve": ```--no-browser```

```javascript
"serve": "lite-server --no-browser -c=bs-config.json",
"serve:e2e": "lite-server --no-browser -c=bs-config.e2e.json",
```

And run

```bash
$ npm start
```

## Now with the tool Angular CLI

Execute:

```bash
$ npm install -g angular-cli
```

Create a new project

```bash
$ ng new <name-project>
```

Run server

```bash
$ cd <name-project>

$ npm start
```


## Angular Component


Step 1 - Create folder to component ```name-component```:

```bash
$ mkdir <name-component>
```

Step 2 - Create file .ts of teh component ```<name-component>.component.ts```

```bash
$ cd <name-component>
$ touch <name-component>.component.ts
``` 

