# Vue CLIとfirebaseを使って作るWebアプリのベース
いつもいつもfirebaseの認証とか忘れるから作った。ここからならコーディングだけでいけるはず

## Project setup
firebaseのプロジェクトは作っておいてな

```
npm install
firebase init
```

### .env.sampleをコピーして自分だけの環境変数ファイルを作ろう！
```
cp .envsample .env
```
Vue CLIの.envはVUE_APP_~ってしないと認識しなかったりするから気をつけてねん

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
