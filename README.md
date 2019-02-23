# vue-cli3-app1
Vue.-cli でプロジェクトを作成し、そのプロジェクトを GitHub に Push するまでの方法  

## ローカルにプロジェクトを作成する。
1. vue create プロジェクト名　　
2. cd プロジェクト名
3. npm run serve
4. ブラウザを開き「http://localhost:8080」にアクセス

## GitHub Pageに公開する設定をする。
1. プロジェクトディレクトリにvue.config.jsを新規に作成する。
2. module.exports = {  　
    outputDir: 'docs',  
    assetsDir: './',  
    publicPath: './'  
   }  
   設定を追加する。  
3. router.jsの設定を変更する  
4. // mode: 'history',
   ヒストリーモードからハッシュモードに変更する  
5.  npm run build

## GitHub リポジトリの作成
1. GitHub ログイン後のトップページから、Repositories の New ボタンをクリックします。
2. Create a new repository の画面に遷移するので、リポジトリ名、ライセンス等を入力。Initialize this repository with a READMEはチェックせず画面下のほうにある Create repository ボタンをクリックします。
 
## プロジェクトを GitHub に Push する
1. git add -A
2. git commit -m "first commit"
3. git remote add origin https://github.com/hiramatsuYoshiaki/プロジェクト名
4. git push -u origin master




## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```
