# json-server on Cloud Functions for Firebase

## json-server

https://github.com/typicode/json-server

## deploy

1. install firebase-tools
```
$ npm install -g firebase-tools
```

2. login firebase
```
$ firebase login
```

3. npm install
```
$ cd functions
$ npm install
```

4. deploy function
```
$ cd ..
$ firebase -P {your firebase project} deploy --only functions
```


