# mocha-slack-reporter

This is a mocha slack reporter that report on console and on the end of tests
send a resume and errors to a slack channel using a slack webhook url.

### Requirements

* npm
* node js
* node-slack module
* mocha

### Install

1. In your project run npm install --save node-slack

```sh
npm install --save node-slack
```
2. Copy slack-reporter.js file on this repo to your node project path

3. Create a script command on package.json

```sh
mocha -R slack-reporter --reporter-options environment=TESTING,channel=#random,hook_url=http:/your-slack-hook-url
```


