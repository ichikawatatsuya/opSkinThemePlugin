opSkinThemePlugin
======================

## 機能概要
テーマを変更する事によって、簡単にスキンを変更する機能を追加します。

## スクリーンショット
### 設定フォーム
![SS](https://raw.github.com/suzuki-mar/opSkinThemePlugin/master/doc/img/setting.png)
### サンプルテーマ
![SS](https://raw.github.com/suzuki-mar/opSkinThemePlugin/master/doc/img/basic.png) ![SS](https://raw.github.com/suzuki-mar/opSkinThemePlugin/master/doc/img/united.png)
![SS](https://raw.github.com/suzuki-mar/opSkinThemePlugin/master/doc/img/cerulean.png) ![SS](https://raw.github.com/suzuki-mar/opSkinThemePlugin/master/doc/img/superhero.png)

## インストール方法
1. 以下のコマンドを実行して、プラグインをインストールしてください。
 * ./symfony opPlugin:install opSkinThemePlugin -r 0.9.1
2. 以下のコマンドを実行し、opSkinThemePluginのwebディレクトリ以下のファイルを公開ディレクトリにコピーしてください
 * ./symfony plugin:publish-assets

## プラグインの使用方法

### スキンテーマを有効にする
管理画面にログイン後、スキンプラグイン設定画面にアクセスします。(プラグイン設定 -> スキンプラグイン設定)  
  スキンプラグイン設定画面で、opSkinThemePluginを有効にします。

### 使用するテーマを選択する
スキンテーマを有効にした後に、スキンプラグイン設定画面からopSkinThemePluginの設定画面にアクセスします。  
  opSkinThemePluginの設定画面から、使用するテーマを選択してください。       
  [テーマの作成方法について](https://github.com/suzuki-mar/opSkinThemePlugin/blob/master/doc/how_to_make_theme.md)


## 更新履歴
### 0.9.1 alpha
* OpenPNEの標準テーマを作成した
* 今までのOpenPNEのHTMLとBootstrapに対応したHTMLを共存できるようにした

### 0.9 alpha
* テーマを選択して、スキンを変更することができるようにした
* 簡易テーマプレビュー機能の追加
* サンプルテーマの作成 (cerulean, superhero, united)



## 要望・フィードバック
要望・フィードバックは #opSkinThemePlugin のハッシュタグをつけてつぶやいてください。             
  GitHubのアカウントを持っている人は [issues](https://github.com/suzuki-mar/opSkinThemePlugin/issues)にチケットを作成してください。
