# リファレンス
- JPHACKに参加する上で、チーム開発に便利なツールや使い勝手の良いフレームワークなどを紹介します。
- こちらは随時追加編集をしていきます。
- 組織委員会が勝手に記載をしているものであり、利用は必須ではありません。
- 是非皆様のチーム開発にお役立てください。

## 便利なチートツール
ゼロから作らなくても、ある程度のアプリができてしまう超便利テンプレート。

- [Hackathon Starter](https://github.com/sahat/hackathon-starter)  
主要なSNSや公開APIとのOAth認証、Bootstrapでのテンプレートを活用することができる
- [Bootswatch](https://bootswatch.com/)  
Bootstrapのフリーテーマ。手軽に超カッコイイフロントが作れてしまう！

## 共有・バージョン管理
### ソース・コードホスティング
#### [GitHub](http://github.com/)
GitHubとは、ソフトウェア開発プロジェクトのためのソースコード管理サービスです。
リポジトリを生成して、プロジェクトのソース・コードをチームでGitベースで管理することができます。また、issueを用いたチケット管理やコメントなどのSNS要素も含まれており、チームでの開発に優れています。

#### [bitbucket](https://bitbucket.org/)
GitHubと同様のソース・コードホスティングサービスです。
GitHubとの違いはこちらなどをご参照ください。

- [GitHubとBitbucketの比較：Webデザイナーの業務にはBitbucketが向いている](http://webbingstudio.com/weblog/internet/entry-651.html)

### ファイルホスティング
- [Dropbox](http://dropbox.com/)
- [Google Drive](https://www.google.com/intl/ja_jp/drive/)  

## 環境構築
### 開発環境構築
「仮想環境」といわれる、実際のコンピューターのように動作するコンピューターファイル (一般にイメージと呼ばれます) を構築するためのツールです。
例えばチーム開発をする際に、利用をする言語やフレームワーク、データベースなど、同時にチーム開発する上では同環境を別のPC上に構築しなければなりません。しかし、MacやWindowsなどのOS依存や、PCに搭載されている言語のバージョンなどによって上手くプロジェクトを動かすことができない場合があります。これらのツールを使って仮想化をしたり、イメージを共有してすぐに同環境を構築することで、複数人での開発をスムーズに行うことができます。
[Vagrantとdockerを使って快適な開発環境を作る（サンプルあり）](http://qiita.com/htanaka0828/items/57204c89bb6976312bb5)  


* [Vagrant](https://www.vagrantup.com/)
* [VMware](https://www.vmware.com/jp)
- [Docker](https://www.docker.com/)
- [Ansible](https://www.ansible.com/)

###PaaS/IaaS
PaaSとは、クラウド上で管理をすることができる総合的な開発環境のことです。クラウドサービスプロバイダーから必要なリソースを従量課金制で購入して、セキュリティで保護されたインターネット接続によってそれらのリソースにアクセスすることができます。
サーバリソースだけではなく、ミドルウェア、開発ツール、ビジネス インテリジェンス (BI) サービス、データベース管理サービスなども統合的に管理することができたりもします。
[【初心者向け】IaaS PaaS SaaSそれぞれの違いとVPSとの比較](http://qiita.com/kznr_luk/items/55a3ff527bd2b81a3d52)
[【クラウドサーバーサービス(IaaS)比較まとめ】](https://matome.naver.jp/odai/2141128309524837601)  

- [AWS](https://aws.amazon.com/jp/)
- [Google App Engin](https://blog.sedesign.co.jp/3463)
* [Microsoft Azure](http://azure.microsoft.com/ja-jp/)
- [Heroku](https://www.heroku.com/)
* [IBM Bluemix](https://console.ng.bluemix.net/)

## モック・デザイン・設計
### モック・デザイン
* [moqups](https://moqups.com/)
* [inVision](http://www.invisionapp.com/)
* [Mockup Builder](http://mockupbuilder.com/)
* [Pixate](http://www.pixate.com/)

### 設計
* [Cacco](https://cacoo.com/lang/ja/)
* [Mysql Workbench](https://www-jp.mysql.com/products/workbench/)
* [joint](http://www.jointjs.com/)

### API設計・連携
- [Swagger](https://swagger.io/)
- [IFTTT](https://ifttt.com/)

## 技術選定
### Webフレームワーク(サーバサイド)
#### PHP
* [FuelPHP](http://fuelphp.jp/)
* [Laravel](http://laravel.jp/)
* [CakePHP](http://cakephp.jp/)

#### Ruby
* [Ruby On Rails](http://rubyonrails.org/)
* [sinatra](http://www.sinatrarb.com/intro-ja.html)

#### Javascript
- [Express(Node.js)](http://expressjs.com/ja/)

#### Python
* [django](http://djangoproject.jp/)
- [bottle](https://bottlepy.org/docs/dev/)

#### Java
* [PlayFramework](https://www.playframework.com/)
- [Spring](https://projects.spring.io/spring-framework/)

### Webフレームワーク(フロントエンド)
#### CSSフレームワーク/ライブラリ
- [Bootstrap](http://getbootstrap.com/)
- [Sass](http://sass-lang.com/)
- [foundation](http://foundation.zurb.com/)
- [FontAwesome](http://fontawesome.io/)

#### Single Page Application
- [React](https://facebook.github.io/react/)
- [Vue.js](https://jp.vuejs.org/index.html)
* [AngularJS](https://angularjs.org/)
* [Backbone.js](http://backbonejs.org/)
* [Sails.js(Node.js)](http://sailsjs.org/)

### モバイルフレームワーク
- [React Native](https://facebook.github.io/react-native/)
* [cordova](https://cordova.apache.org/)
* [phoneGap](http://phonegap-fan.com/)
* [Titanium](http://install.titanium-mobile.jp/)

### ゲームエンジン
* [Unity](http://japan.unity3d.com/)
* [Cocos2dx](http://jp.cocos.com/)

## ディレクション・コミュニケーション
### ディレクション/タスク管理
* [trello](https://trello.com/)
* [Waffle.io](https://waffle.io/)
* [Github issue](https://github.com/)

### コミュニケーション
* [Slack](https://slack.com/)
* [gitter](https://gitter.im/)

## プレゼン
* [Reveal.js](http://lab.hakim.se/reveal-js/)
* [speaker deck](https://speakerdeck.com/)
* [Prezi](https://prezi.com/)

## 参考記事
* [今日から実践！アプリの企画や設計を効率的にするプロトタイピングの全貌（基本編）](http://www.sekai-lab.com/times/?p=1957)
* [アプリのUI設計は「紙でやる」のが早い！](http://qiita.com/flexfirm/items/8dd80f70029ce2c02ee8)
* [アプリのプロトタイプ・デモ画面がつくれるツールまとめ](http://appmarketinglabo.net/app-prototype-tool/)
* [プログラマ向けプレゼン・ツールまとめ](http://matome.naver.jp/odai/2133017481093611101)
* [時代はシェア！プロジェクトの進捗などを共有できるタスク管理ツール12選](http://liginc.co.jp/web/service/other-service/21670)
* [実録！ チーム開発が捗り過ぎるSlack＋GitHub＋Trelloの使い方](http://www.atmarkit.co.jp/ait/articles/1410/29/news042.html)
* [高速で無駄のない開発をするチームのための”７つ道具”](http://kuranuki.sonicgarden.jp/2014/03/tools.html)
* [【2015年最新版】プロジェクト管理ツール（無料）が便利すぎる](http://matome.naver.jp/odai/2140555898877842501)
* [チーム開発環境をワンストップで構築しよう
～Visual Studio Online](http://matome.naver.jp/odai/2140555898877842501)
* [自社サービス運営してる会社の開発環境を公開します](http://tech.cookbiz.co.jp/engineering-184)
* [VagrantとChefでチームの開発環境を共通化する](http://higelog.brassworks.jp/?p=2273)
* [2014年 Webアプリケーションフレームワークトレンド（PHP / Java / Ruby / Python / Perl）](http://qiita.com/shukotang/items/055058b33b553b48c164)
* [Webサービスの開発にフレームワークが必要な理由 ～Perl/Ruby/PHPユーザーのためのMVCフレームワーク入門～](http://codezine.jp/article/detail/3573)
