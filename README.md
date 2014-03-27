# HTML5 Rocks 日本語訳

URL: <http://www.html5rocks.com/>  
オリジナルレポジトリ: <https://github.com/html5rocks/www.html5rocks.com>  
html5j英語部レポジトリ: <https://github.com/html5j-english/www.html5rocks.com>

## HTML5 Rocksの日本語訳にあたって

まずはこちらの[LOCALIZATION.md](https://github.com/html5rocks/www.html5rocks.com/blob/master/LOCALIZATION.md) / [日本語訳](https://gist.github.com/myakura/6d920770a4939b5deeb6) by @myakura を一読ください。

### HTML5 Rocksの日本語訳を行いたい場合

本レポジトリはhtml5j英語部における **監訳ワークフロー** ([\*1](https://github.com/html5j-english/README/wiki/Review-and-Pull-Request-Work-Flow))や原文アップデートに合わせた翻訳の修正コラボレーションワークなどのためのレポジトリとなります。

html5j英語部スタッフ/有志によるイベント(オンライン/オフライン問わず)時に推奨翻訳記事リストを作成し、それを元に本リポジトリに必要なディレクトリや原文などを追加しています。翻訳希望の記事が推奨翻訳記事リストに **ある場合** は本レポジトリを **Fork** して、翻訳を行ってください。  
それ以外の場合は、本レポジトリを **Clone** した上で、翻訳する記事用のディレクトリ、原文(もちろん翻訳してもOKです)を作成した上で、本レポジトリに **Pull Request** してください。

#### submoduleについて

本レポジトリにhtml5j英語部用にforkしたHTML5 Rocksのレポジトリをsubmoduleとして追加しています。  

```
git clone git@github.com:html5j-english/html5rocks.git
cd html5rocks
git submodule update --init
```

上記コマンドでsubmoduleをfetchできます。  

GitやGitHubでの作業がわからない、という場合にはお気軽にIssue、あるいは[Gitter](https://gitter.im/html5j-english)までご質問ください。

### 翻訳前にIssueを確認してください。

上記どちらのケースでも事前にIssueにて翻訳を行う旨、宣言していただければと思います。もしかすると他の人も同時に翻訳を進めていることもありますので、ご協力お願いいたします。  
同様に、翻訳を行う前にはIssueを確認いただいて、自分が翻訳したい記事が翻訳作業に入っているかどうかも確認ください。

html5j英語部はあくまでも有志による翻訳コミュニティです。オリジナルであるHTML5 Rocksとは関連はありませんし、全てのHTML5 Rocksの日本語訳が本コミュニティを通じて行われているわけではありません。  
