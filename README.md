# What is ? 
ossのアイデアを書き残すために作成しました。

## Contributing
- そのアイデアもうすでに作られたやつあるよってのがあったらIssuesにあげて教えていただけると嬉しいです。
- こんなアイデアあるんだけどどう？みたいのがあったらPRで教えてください


## Idea lists

- JSなどのnpmパッケージに必要な環境構築を提供するcliツール
↓こんな感じの
```bash
$ npx create-npm-app --node <appName> --with-typescript
# node用のnpmライブラリを作るためのテンプレート(rollup、webpackの設定)をインストールするみたいな
```
 -> create-react-app, create-next-app　みたいな？

- React component api    
MaterialUIみたいにゴリゴリにデザインが作り込まれてるのでは無く、ロジックだけ提供する。Modalとかaccordionとか、textfieldとか
利点
 ・デザインそのものは好きなCSSで作れる(tailwindとかchakraとか、その他色々)
 ・デザインシステムの開発スピードを上げられる    
 
 refで提供？テンプレートを用意して置くだけで使えるようにするが、カスタマイズもできるようにする    
materialuiやchakraのロジック部分を無効化するrefを作り、デザインだけ使えるようにする
