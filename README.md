# Firebase Web Codelab - Start code

This folder contains the starting code for the [Firebase: Build a Real Time Web Chat App Codelab](https://codelabs.developers.google.com/codelabs/firebase-web/).

## Start Guide

### install
```
$ npm -g install firebase-tools
$ firebase --version
$ firebase login
$ cd web-start/
$ firebase use --add
```

### build
```
$ firebase serve --only hosting
```

### deploy

```
$ firebase deploy --only database
$ firebase deploy --only storage
$ firebase deploy --except functions
```

