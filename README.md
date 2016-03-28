# hello-gulp-jsforce-deploy
gulp-jsforce-deployの動作確認用ファイルです。

## Setup
```
$ cd desktop
$ gitclone git@github.com:tyoshikawa1106/hello-gulp-jsforce-deploy.git
$ cd hello-gulp-jsforce-deploy
$ npm install
```

## Create 『.env』 File
```
SF_USERNAME=<salesforce username>
SF_PASSWORD=<salesforce password>
```

## Deploy
```
$ foreman run gulp deploy
```

### foreman install command
```
$ gem install foreman
```

## jsforce/gulp-jsforce-deploy  
https://github.com/jsforce/gulp-jsforce-deploy
