# texjp.org

Japanese TeX Development Community Webサイトのソースコードです。
このサイトは、静的サイト生成器Middlemanを使用して構築しています。

## ビルドツール

 * Ruby 2.4
 * Middleman
 * Bower

## 開発ルール

## `git checkout`後の作業

``` bash
$ bundle install
$ bower install
```

## ローカル環境で実行

Middlemanのサーバ機能を用います。

``` bash
$ bundle exec middleman server
```

以下のURLから動作確認できます。

```
http://localhost:4567/
```
