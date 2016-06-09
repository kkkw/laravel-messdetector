# laravel-messdetector

Laravelを使用したプロジェクトのために用意された
phpmdのルールセット

## インストール

### パッケージをインストール

`composer.json` に記載してインストールする  
`repositories` と `require-dev` にそれぞれ追記する

``` json:composer.json
"repositories": [
 {
  "type":"package",
    "package": {
      "name": "kkkw/laravel-messdetector",
      "version":"master",
      "source": {
        "url": "git@github.com:kkkw/laravel-messdetector.git",
        "type": "git",
        "reference":"master"
      }
    }
  }
],
"require-dev": {
    "kkkw/laravel-messdetector": "*@dev"
},
```
