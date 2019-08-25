# alias comand

* ```alias gi="git init"```

* ```alias gs="git status"```

* ```alias ga="git add"```

* ```alias gcm="git commit -m"```

# package version
* axios@0.16.2

* babel-core@6.25.0<br>
→ES6をコンパイルするために必要なのがbabel

* babel-loader@7.1.1

* babel-preset-es2015@6.24.1

* babel-preset-react@6.24.1<br>
→reactをコンパイルするために必要

* css-loader@0.28.4

* extract-text-webpack-plugin@3.0.0

* geolib@2.0.22

* import-glob-loader@1.1.0

* lodash@4.17.4

* node-sass@4.5.3

* prop-types@15.5.10

* query-string@5.0.0

* react@15.6.1

* react-dom@15.6.1

* react-google-maps@7.2.0

* react-redux@5.0.6

* react-router-dom@4.1.2

* redux@3.7.2

* redux-devtools@3.4.0

* redux-devtools-extension@2.13.2

* redux-thunk@2.2.0

* sass-loader@6.0.6

* style-loader@0.18.2

* webpack@3.3.0<br>
→ビルドツール

* webpack-dev-server@2.5.1<br>
→ローカル上でwebサーバーを立てるためのパッケージ

* eslint@3.19.0

* eslint-config-airbnb@15.0.2

* eslint-plugin-import@2.7.0

* eslint-plugin-jsx-a11y@5.1.1

* eslint-plugin-react@7.1.0

# Tips
* ```./node_modules/.bin/eslint --init```を実行すると、```./node_modules/.bin/eslint```の実行ファイルが消えてしまい、
次の操作で```No such file or directory```のエラーが発生することが確認されています。
```init```実行後に```$ yarn install```を実行すると復活しますので、先へ進む前にこちらの実行してください。<br>
参考: https://www.udemy.com/react-redux-from-beginning/learn/v4/questions/2814568

* react・react-domという2つのパッケージを導入しますが、動画の通り```$ yarn add react react-dom```と入力すると、動画より新しいバージョンのreactがインストールされて一部挙動が違う部分が確認されています。
```$ yarn add react@15.6.1 react-dom@15.6.1 ```でバージョン指定でインストールをすること。<br>
参考: https://www.udemy.com/react-redux-from-beginning/learn/v4/questions/2900840