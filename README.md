# GAS 順番シャッフル
## 開発環境
### init
```
$ npm i && npm i -g clasp
```

claspのloginをする
ログインするとトークンが`.clasprc.json` がhome(`~`)に生成される

```
$ clasp login
```

`.clasp.json` をexampleからコピーしてプロジェクトルートに配置。

```
$ cp .clasp.json.example .clasp.json
```

GASからスクリプトIDをコピーしてこの `.clasp.json` に記載

### 開発環境の解説
GASはclaspで管理中

claspのCLIを使う都合上、 `-g` でインストールのこと
```
$ npm i -g clasp
```