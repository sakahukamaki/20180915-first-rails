<link href="https://fonts.googleapis.com/earlyaccess/mplus1p.css" rel="stylesheet" />  
<link href="https://fonts.googleapis.com/earlyaccess/roundedmplus1c.css" rel="stylesheet" />  
<link href="https://fonts.googleapis.com/earlyaccess/sawarabigothic.css" rel="stylesheet" />  
<link href="https://fonts.googleapis.com/earlyaccess/nicomoji.css" rel="stylesheet" />  
<link href="https://fonts.googleapis.com/earlyaccess/notosansjapanese.css" rel="stylesheet" />  
<link href="https://fonts.googleapis.com/css?family=Exo+2" rel="stylesheet">

# @css[h1-narrow](Railsことはじめ)

@css[p-narrow](2018/9/15) IWM @css[p-narrow](@マヤッカ)
 
---

# @css[h1-wide](自己紹介)

名前： 大谷明日香  
年齢： 22歳    
職業： 開発SE（4年目）    
言語： Ruby！ Rails！    
所属： 株式会社 島根情報処理センター    

---

# @css[h1-wide](注意点)

緊張しています  
大目に見てください  
早口になったら教えてください  
Twitterとかに書かないでね

---

@snap[midpoint]
緊張をほぐしたいので趣味の話をします
@snapend

---

## 刀使ノ巫女
2018年1月～、4月～    
2クールオリジナルアニメ    


!TODO 画像

---

## @css[h1-narrow](少女☆歌劇 レヴュースタァライト)
2018年7月～  
舞台と同時展開  

!TODO 画像

---

## アクタージュ
週刊少年ジャンプ  
!TODO 画像  

---

## @css[h1-narrow](ランウェイで笑って)
週刊少年マガジン  
!TODO 画像  

---

@snap[midpoint]
それぞれ漫画を持ってきたので興味ある方はお声がけください
@snapend
---

@snap[midpoint]
# 布教終わり
@snapped

---

@snap[midpoint]
# 本題入ります
@snapped

---
# 喋ること

新人のときに知りたかったことを喋ります  
雑なところもあります

---

# Rubyデキる人

「えっこんなところまで話す？」  
「誰でも知ってるのに？」

---

# すまんな

新人の頃知らなかったことを話すので  
もし知ってたら静かに寝てください

---

# 新人さんへ

鵜呑みにする必要はないので  
取捨選択してください

---

# 内容について
初心者向けに噛み砕いてるので  
「いや違うわ」という意見があれば  
お菓子の時にどうぞ  

---
# それでは
前置き終わり  

---
# 目次

- そもそもRailsって？  
- Railsをインストールするまで 
- Railsプロジェクトを拡張していく

---
# 目次

- そもそもRailsって？ 👈 
- Railsをインストールするまで
- Railsプロジェクトを拡張していく

---

# @css[h1-narrow](Ruby on Railsとは)
Ruby on Railsとは  


- オープンソースの |
- Webアプリケーションの |
- フレームワーク |

である

---

@snap[midpoint]
オープンソース？
@snapped

---

## オープンソースとは
ソフトウェアのソースコードが公開されていて、誰でも自由に修正・再配布できること
また、その開発方法のこと

再配布・修正の範囲はライセンスに依存するので注意

---
# @css[h1-narrow](Ruby on Railsとは)
Ruby on Railsとは  


- オープンソースの
- Webアプリケーションの |
- フレームワーク |

である

---

@snap[midpoint]
Webアプリケーション？
@snapped

---
## Webアプリケーションとは

インターネットを介して利用する  
アプリケーション（ソフトウェア）  
のこと

---

@snap[midpoint]
アプリケーション？
@snapped

---
## アプリケーションとは

アプリケーションプログラムと呼ばれる  

コンピュータを「応用」する目的に応じた、コンピュータ・プログラムのこと  
（ワープロや表計算ソフトなど）

---
# @css[h1-narrow](Ruby on Railsとは)
Ruby on Railsとは  

- オープンソースの 
- Webアプリケーションの 
- フレームワーク |

である

---

@snap[midpoint]
フレームワーク？
@snapped

---
## フレームワーク
多くの再利用可能なコードをフレームワークにまとめることによって開発者の手間を省き、  
新たなアプリケーションのために標準的なコードを改めて書かなくて済むようにする  
構造化されたクラスやライブラリの集まりのこと

---
## フレームワーク（雑）
フレry「同じことやるの辛いだろ？」  
フレry「俺に任せろ！」

---

# @css[h1-narrow](Ruby on Railsとは)
Ruby on Railsとは  


- オープンソースの
- Webアプリケーションの
- フレームワーク

である

---

# @css[h1-narrow](Ruby on Rails(雑))
「Webアプリ作るのに必要な骨組み揃えてやったぜ」

---
# Rails理解できた

---
# Ruby的には
Ruby on Railsはただのgem

---
## gemとは
Rubyのライブラリのこと    
gemから本体になったり本体のライブラリからgemになったりする  
 
Rubygemsで配布される  

---
## RubyGemsとは
gemを公開するポータルサイト   
ここに登録すれば全世界からgemとして利用できる

---
# まとめ

---

# @css[h1-narrow](Ruby on Railsとは)
- オープンソースの |
- Webアプリケーションの | 
- フレームワークであり |
- ひとつのgemである |

---

@snap[midpoint]
ちなみに
@snapped

---


# Railsの最新を知る
- Rails news
- Rails release
- GitHub rails/rails

---
# 全部英語

![Rails news is all english](https://raw.githubusercontent.com/sjc-ohtani-a/20180915-first-rails/master/pictures/rails-news-is-english.png)

---
# 翻訳記事を探す
- 週刊Railsウォッチ
- 「右クリック」「翻訳」

---
# Rails以外も
- [Menthas\.com](https://menthas.com/)
- [はてなブックマーク テクノロジー](http://b.hatena.ne.jp/hotentry/it)
- Qiita新着

---
# @css[h1-narrow](大切なこと)

「こういうものがある」を知ること  

---

# @css[h1-narrow](知っているだけ)

理解しなくていい  
そういう知識の幅を浅く広げるだけでエンジニアの生存率が上がる

---

# 超人にはなれない
技術はすぐに出ては消えていくので、  
フロントからバックまで全部把握しようとしたらキャパオーバーになる

---

## そもそもRailsって？<br> はここまで

---
# 目次

- そもそもRailsって？ 
- Railsをインストールするまで 👈
- Railsプロジェクトを拡張していく

---

# @css[h1-narrow](Railsを<br>インストールするまで)

1. 環境を作る 👈
2. rails new

---
# Railsを始める前に
Railsを始めるには？環境はどうしたら？  
みたいな記事が少ない  
ちょっと突っ込んだ話をします

---
# 開発環境
UNIXである前提で世の中のRails開発は動いています 

---
# UNIX
OSの種類

Windowsとは遠く離れている

---

# Windowsの人
パッと思いつく選択肢はこんな感じ。

1. 仮想環境を作る
2. WSLを使う
3. Cygwinとかを導入する
4. Windowsで頑張る

---

# 非推奨
## 3. Cygwinとかを導入する

Windowsに無理にUNIX突っ込めばﾍｰｷﾍｰｷ  

そんなわけないじゃん

---

## なんで？

- 入れるのがめんどくさい  
- 消すのがすごくめんどくさい  
- WSL使えば？ → 2へ |

---
# 非推奨
## 4. Windowsで頑張る

WindowsにRubyを突っ込むの？  
(´･ω･｀)ﾅｼﾃﾞｼｮ

---

## なんで？
UNIXじゃないから動かないgemが多い  
native extensionつらい

---
# 微妙
## 2. WSLを使う

WSL #=> Windows Subsystem for Linux

![wsl](https://raw.githubusercontent.com/sjc-ohtani-a/20180915-first-rails/master/pictures/wsl-lie.png)

---

# なんで？
所感として安定しない  
個人的にubuntuに慣れてない  
コンソールがだめ  

---
# 推奨
## 1. 仮想環境を作る

VirtualBox＋Vagrant＋CentOSとか

---
# おすすめ
VirtualBox＋Vagrant＋CentOS

仮想作るならVMWareもある  
慣れたのがあればそちらで

---
# Macの人
そのままの環境でも問題ない  

Windowsと同じくVirtualBoxとVagrantで仮想環境作るのも良い

---
# Linuxの人
自分で選んでくれ

---

# 準備
絶対に必要なもの  

- Ruby
- 関連する知識をかじるやる気
- 寄り道する余裕

---

# Rubyインストール
（Windowsは仮想環境を作った前提）

---
# rvmとrbenv

一長一短
個人的にはrbenvがおすすめ

---
# インストール方法
教えません  

調べてください

---

@snap[midpoint]
## じゃあ調べよう
@snapped


---
# 調べるときのコツ

やりたいことで絞る  
`rbenv install` でggる

---
# 環境で絞る
さらに環境で絞る

- WindowsとMacの情報はいらない
- LinuxだけどUbuntuじゃなくてCentOS
- CentOSだけど6じゃなくて7

---
# 日付で絞る
「ツール」の「期間指定」で変更できる

---
## 全部Qiitaでいいの？
情報の取捨選択が出来ない内はよくない

---
# 情報の取捨選択
気にしたほうがいいこと

- 各種バージョンが明記されているか |
- 言葉遣いが雑ではないか |
- 他の記事のクオリティは？ |
- 求める情報と合致しているか？ | 

---
# 情報の鮮度
2013年の記事より2017年の記事の方が  
信用できる  
※プロジェクトの環境が古い場合はこの限りではない  

---

@snap[midpoint]
# Ruby installed!
@snapped

---
# じゃあ早速開発を

1. 環境を作る 
2. rails new 👈❓

---

# できません
Railsをインストールするまで

1. 環境を作る  
1.5.  基本的な知識を身につける 👈
2. rails new

---
# Rails開発に必要な知識
なんかいっぱい

Ruby/SQL/Redis/Webpacker/npm/PostgreSQL/
Bundler/Git/SCSS/CentOS/Ubuntu/SQLServer/
MySQL/JavaScript/Ransack/ReactJS/Vue.js/
Riot.js/CSS/Sass/Heroku/Haml/Guard/Slim/
ERB/HTML/Spring/AWS/GCP/etcetc

---
# @css[h1-narrow](最低限の知識)
- Ruby
- Bundler
- Git
- JavaScript, CSS
- HTML, ERB

---
# Ruby
Silver取れるくらいRubyに詳しいのが理想

![資格](https://raw.githubusercontent.com/sjc-ohtani-a/20180915-first-rails/master/pictures/certified.png)

---
# Bundler

gem "rails"を動かすには  
このバージョンの"activesupport"が必要、  
あれもこれもそれもどれも必要！  

という状況で、

## @css[h1-narrow](gem同士の互換性を保ちながら)

各gemの導入、管理を行う

---

# Bundler
同じ環境で異なるバージョンのRailsを動かすことができる。

```
gem install bundler --no-ri --no-doc 
```

---
# Gemfile

必要なgemを羅列するファイル  

本番環境だけ使うgem、テスト環境だけ使うgemのように、  
対象環境をグループ分けして
それぞれ必要なgemを使い分けることができる

---
# bundle install

bundlerがGemfileに書いてあるgemを  
いい感じに解釈しつつインストールするコマンド   

初回実行後、Gemfile.lockというファイルが作られる

---
# Gemfile.lock

まじめな話はScrapboxに書いた  
→ [Gemfile\.lock](https://scrapbox.io/sakahukamaki-first-rails/Gemfile.lock)

---
## Git/JavaScript/CSS/HTML

 
飛ばします  
知らない人はドットインストールにGO！

---

# ERB

Rubyのコードを記述できるHTMLのようなもの

```erb
<%# コメント %> # コメント  
<%= 123 %>     # 出力されるRubyのコード  
<% if true %>  # 出力されないRubyのコード  
```

---

# @css[h1-narrow](完ッ璧に理解した🐇)

---
# Railsやろうぜ

1. 環境を作る  
1.5.  基本的な知識を身につける
2. rails new  👈

---
# 基本形のコマンド

```sh
rails new starlight
```

---
# 派生形のコマンド
よく見るやつ  
同じ環境で複数のRailsアプリを作る場合

```sh
mkdir starlight && cd starlight
bundle init 
bundle install --path vendor/bundle 
bundle exec rails new .
```

---

@snap[midpoint]
## 基本形と違いすぎる
@snapped

---

@snap[midpoint]
## 本当に？
@snapped

---

# 検証

```sh
rails new starlight
# mkdir starlight && cd starlight
# bundle init
# bundle install
# たくさんのファイルを作る
```

```sh
mkdir starlight && cd starlight
bundle init 
bundle install --path vendor/bundle 
bundle exec rails new .
# たくさんのファイルを作る
```

---

@snap[midpoint]
ざっくり同じことをしている
@snapped


---

# 奥深いですね

---
## newのオプション

["rails new" options explained](https://gist.github.com/eliotsykes/ace0222174804372b51a)

---

# よく使うもの
個人的によく使うもの
```
-B # skip bundle
-T # skip test 

-d=xxx # select database 
```

---
newする前に考えておきたいことについては  
ちょっと真面目に記事書いた    
 [Rails newする前に](https://scrapbox.io/sakahukamaki-first-rails/Rails_new%E3%81%99%E3%82%8B%E5%89%8D%E3%81%AB)

---

# Railsプロジェクト
出来ましたね！  

## Railsをインストールするまで
はここまで

---


# 目次

- そもそもRailsって？ 
- Railsをインストールするまで 
- Railsプロジェクトを拡張していく 👈

---

## 拡張＝gemを追加する

---

# 必須

---
## さいつよデバッグgem
- pry-rails
- pry-byebug

PryはIRBの上位互換ですごいつよい  
さいつよ  
[今更聞けないpryの使い方と便利プラグイン集](https://qiita.com/k0kubun/items/b118e9ccaef8707c4d9f)

---

# rails-i18n
I18nの辞書ファイル集  
RailsのWebアプリケーションを多言語化するのに必要  

よく[ja.yml](https://github.com/svenfuchs/rails-i18n/blob/master/rails/locale/ja.yml )だけ使われる

---
あとはN+1検出の`bullet`と、  
Linterの`rubocop`と、  
Test::Unitの代わりの`rspec`を入れて…

---
# これで完璧ですね

---

# 本当に？

---
# よく見かける謎文法
```ruby
@user.deleted_at&.strftime("%Y/%m/%d")

@user.try(:deleted_at).try(:strftime, "%Y/%m/%d")

@user.name ||= "ななし"
```

---
# nil対策三銃士
```ruby
&.method
```

[nil でもメソッド呼び出しがエラーにならない safe navigation operator](https://qiita.com/jnchito/items/0faac073cb77417d61c7#nil-%E3%81%A7%E3%82%82%E3%83%A1%E3%82%BD%E3%83%83%E3%83%89%E5%91%BC%E3%81%B3%E5%87%BA%E3%81%97%E3%81%8C%E3%82%A8%E3%83%A9%E3%83%BC%E3%81%AB%E3%81%AA%E3%82%89%E3%81%AA%E3%81%84-safe-navigation-operator)

```ruby
try(:method)
```

[nilチェックの代わりにObject\#try\(:method\_name\)を使う](https://qiita.com/jnchito/items/dedb3b889ab226933ccf#nil%E3%83%81%E3%82%A7%E3%83%83%E3%82%AF%E3%81%AE%E4%BB%A3%E3%82%8F%E3%82%8A%E3%81%ABobjecttrymethod_name%E3%82%92%E4%BD%BF%E3%81%86)

```ruby
||=
```

[nilだったら初期化、の代わりに \|\|= を使う](https://qiita.com/jnchito/items/dedb3b889ab226933ccf#nil%E3%81%A0%E3%81%A3%E3%81%9F%E3%82%89%E5%88%9D%E6%9C%9F%E5%8C%96%E3%81%AE%E4%BB%A3%E3%82%8F%E3%82%8A%E3%81%AB--%E3%82%92%E4%BD%BF%E3%81%86)

---

# Rubyの知識が弱すぎる

---

# Ruby イディオム <br>で [検索]☜

---

# @css[h1-narrow](動かないJS)

---

# @css[h1-narrow](Turbolinks<br>って知ってる？)

---
# Turbolinks（雑）
@css[p-narrow](GETリクエストの時はキャッシュをフル活用する)

---
# Turbolinks対策
 - [Turbolinksをオフしないためにやった事](https://qiita.com/saboyutaka/items/bcc0966313c6f7399a6e)
 - [Turbolinks5についてまとめてみる](https://qiita.com/saboyutaka/items/bb089e8208239bf6fdc0)
 - [Rails5でturbolinksをオフにする時に気をつけること](http://kansiho.hatenablog.com/entry/2017/08/08/Rails5%E3%81%A7turbolinks%E3%82%92%E3%82%AA%E3%83%95%E3%81%AB%E3%81%99%E3%82%8B%E6%99%82%E3%81%AB%E6%B0%97%E3%82%92%E3%81%A4%E3%81%91%E3%82%8B%E3%81%93%E3%81%A8)

---

# 初期トラブル解決

---

# 応用に走る

---

### 日時のフォーマットを標準化したい  
いちいち`created_at.strftime`って書くのが嫌だ！

 → [日付/時間フォーマットのデフォルトを設定](https://qiita.com/Vit-Symty/items/399c77d1fd681b77d593)

---

### Railsの環境を読み込んで<br>スクリプトを走らせたい
Runnerを使えば解決

→ [rails runnerを使ってみた](https://qiita.com/3yatsu/items/416411c0a8f696dbf99e)

---
### 特定のattrだけ<br>エラーメッセージを上書きしたい

セレクトボックスの項目なのにエラーメッセージは「xxを入力してください」

→ [エラーメッセージを上書きする](https://scrapbox.io/sakahukamaki-first-rails/%E3%82%A8%E3%83%A9%E3%83%BC%E3%83%A1%E3%83%83%E3%82%BB%E3%83%BC%E3%82%B8%E3%82%92%E4%B8%8A%E6%9B%B8%E3%81%8D%E3%81%99%E3%82%8B)

---

### ERBつらい
`<%= %>`っていちいち入力するのがつらい人向け

[Railsのテンプレートエンジンをhamlやslimに変更する](https://www.sglabs.jp/rails-haml-slim/)

---

### `rails g` でファイルが大量発生する

`rails generator` でコントローラやモデルを作ったときにどのファイルを作ってどのファイルを作らないのかを設定できる。  
`config/initializers/gernerator.rb`を作るとよい。

[Rails自身が持つジェネレータはscaffoldを柔軟にカスタマイズできます](https://railsguides.jp/generators.html#%E3%83%AF%E3%83%BC%E3%82%AF%E3%83%95%E3%83%AD%E3%83%BC%E3%82%92%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%9E%E3%82%A4%E3%82%BA%E3%81%99%E3%82%8B)

---

### インスタンスメソッドと<br>クラスメソッドって<br>何が違うの
[メソッドの例の\`\#\`と\`\.\`について](https://scrapbox.io/sakahukamaki-first-rails/%E3%83%A1%E3%82%BD%E3%83%83%E3%83%89%E3%81%AE%E4%BE%8B%E3%81%AE%60%23%60%E3%81%A8%60.%60%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)

---
あと適当に書いてあるもの  
[Railsことはじめ](https://scrapbox.io/sakahukamaki-first-rails/)

---

# 今日話したこと
- Railsを導入するために必要なこと
- Railsをインストールするまで
  1. 環境を作る  
  1.5.  基本的な知識を身につける
  2. rails new  
- Railsプロジェクトを拡張していく
    - gem を追加する
    - よくある初期トラブル
    - デキるRailsエンジニアになる応用

---

@snap[midpoint]

### ドヤ顔できるRubyとRailsじゃなかったの
@snapped

--- 

@snap[midpoint]
Rails開発環境と`rails new`に対する  
並々ならぬ情熱が暴走したので尺がなくなった  
最後駆け足でちょっと書いたので許してください
@snapped

---

@snap[midpoint]
Rails入門の攻略（初心者向け）でした
@snapped

---

@snap[midpoint]
以上
@snapped

---

@snap[midpoint]
おつかれさまでした

@snapped
