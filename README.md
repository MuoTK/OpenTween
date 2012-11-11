OpenTweenA
==========
OpenTween の派生クライアントです。自分の便利なように変更を加えたものです。ですから、機能の要望などは基本的に受け付けません。


OpenTween との違い
------------------
* 右下からのドロップダウン・ショートカットキーからアカウント切り替えができるように
* コンシューマキーをアカウントごとに変更可能
* 140文字自動カット・末尾に全角スペースをつけるツイート重複防止
* APIコマンド回避の正規表現を修正されている
* ツイート時に\r\nではなく\nで送信される。文字数カウントが修正されている
* ツイートのトリムを ' ', '\t', '\r', '\n' のみに
* スペースキーでタイムラインにフォーカスを移すかを選択できるように
* 鍵アカでもQTをできるように。非公式RTはできない
* UserStreamsを2本張り、同じアカウントのタイムラインのまま他のアカウントでツイートすることが可能 * バグがあるかも
* パクリツイートの文字色を変更できる * 非常に重い
* ツイートのRTされた数・ふぁぼられた数が表示できる（rate limitedなAPIを使います）

色々抜けているかもしれません。ChangeLog.txtをみてください。

既知のバグ・不具合
-----------------
 * API残数表示が異常
 * UserStreamsが2本張られている場合、自分のツイートを既読にするような設定をしていても正常に動かない
 * UserStreamsが2本張られている場合、1本でも切れるとメニューの表示が■となる

あまり私には影響がないため、修正されない可能性もあります。たれかpull requestおくって(´へεへ`*)

開発環境
--------
Windows 8 Pro (64bit)  
.NET Framework 4.0  
Visual Studio Professional 2012  


リンク
------
[OpenTween - sf.jp](http://sourceforge.jp/projects/opentween/)  
[OpenTween - github](https://github.com/opentween/OpenTween)  
[re4k.info](http://re4k.info/)  
[@re4k](https://twitter.com/re4k)  

