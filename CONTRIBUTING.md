# Contributing Guide

Contributions are welcome and are greatly appreciated! Every little bit helps, and credit will
always be given.

Create app with Expo
## Setting up your environment

After forking to your own github org, do the following steps to get started:

```bash
# clone your fork to your local machine
git clone https://github.com/hongquanjs95/nhahangpos.git

# step use expo
$ npm install exp --global
$ exp init my-new-project
$ cd my-new-project
$ exp start

# step into local expo
$ npm i -g create-react-native-app
$ create-react-native-app my-project
$ cd my-project
$ npm start

# step into local none expo
$ npm install -g react-native-cli
$ react-native init my-project
$ cd my-project
$ npm start

# install dependencies with npm
$ npm install
$ npm install -g yarn
$ npm install [package]
$ npm restart
$ npm rebuild
$ npm uninstall [package]
$ npm cache clean
$ rm -rf node_modules && npm install (reinstall)

# install dependencies with yarn
$ yarn install
$ yarn add [package]
$ yarn install --force (rebuild)
$ yarn remove [package]
$ yarn cache clean [package]
$ yarn upgrade (reinstall)
# delete and reinstall node
rm -rf node_modules && npm install
npm start -- --reset-cache

# run packager for development
$ react-native start
$ npm start

### Developing on Android
react-native eject
react-native link
react-native run-android
