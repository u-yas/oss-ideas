# What is ? 
ossのアイデアを書き残すために作成しました。

## Contributing
- そのアイデアもうすでに作られたやつあるよってのがあったらIssuesにあげて教えていただけると嬉しいです。
- こんなアイデアあるんだけどどう？みたいのがあったらPRで教えてください


## Idea lists

- create-npm-modules
JSなどのnpmパッケージに必要な環境構築を提供するcliツール
↓こんな感じの
```bash
$ npx create-npm-modules --node <appName> --with-typescript
# node用のnpmライブラリを作るためのテンプレート(rollup、webpackの設定)をインストールするみたいな
```
 -> create-react-app, create-next-app　みたいな？exampleフォルダを作って色々PR来たやつを入れていく

- React component api    
MaterialUIみたいにゴリゴリにデザインが作り込まれてるのでは無く、ロジックだけ提供する。Modalとかaccordionとか、textfieldとか
利点
 ・デザインそのものは好きなCSSで作れる(tailwindとかchakraとか、その他色々)
 ・デザインシステムの開発スピードを上げられる    
 
 refで提供？テンプレートを用意して置くだけで使えるようにするが、カスタマイズもできるようにする    
materialuiやchakraのロジック部分を無効化するrefを作り、デザインだけ使えるようにする
 ->できるのか？要検証

- Next.rs
 Next.jsをRustで書き換える
 -> JSONの受け渡しをどうするか 
   -> graphQLのスキーマみたいに共有できる型を作る
   -> superJsonみたいなのを作る
   -> そもそもメリットが有るのか
   -> 技術力
 -> SSRとSSGをrustでできるのか　
 　　-> できるだろうけど相当な技術力必要そう
