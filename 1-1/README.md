**1-1 WEBページの基本**

WEBページは、HTMLという拡張子のファイルでできている。
HTMLとは、HyperText Markup Languageの略であり、通常の文書をマークアップして機能を拡張したもの。

HTMLファイルをテキストエディタで表示してみると、本文のほかに<>で囲まれた多数のタグが表れる。
文章の構造や、図やリンクの挿入などは、このタグによって制御されており、WEBブラウザがHTMLファイルを読み込む際に、タグに基づいてページの再構築を行う。

![image](http://www.ei-ic.sakura.ne.jp/handson20180721/img/1-1_01.png)



ページの背景色や文字の大きさ、その他様々なデザインに関することは、CSS（Cascading Style Sheets）という言語によって指定される。
CSSは、HTMLファイル内に書き込むこともできるが、通常は.cssという別ファイルにて管理される。

![image](http://www.ei-ic.sakura.ne.jp/handson20180721/img/1-1_02.png)


HTMLやCSS、JavaScriptなどのファイルは、「クライアントサイド」のプログラムである。
クライアントサイドとは、ファイルをサーバーから受け取ったあと、表示する端末がそれらのプログラムを実行するという意味である。
そのためプログラムの処理速度は、端末の処理速度に依存することになる。
その対義語として「サーバーサイド」のプログラムがあるが、サーバー上でプログラムを実行し、その結果を端末に送信し表示するということを意味する。

今日学ぶ内容は、全て「クライアントサイド」である。
しかも、PC上のローカルな環境で全て完結するものであり、サーバーは使用しない。

![image](http://www.ei-ic.sakura.ne.jp/handson20180721/img/1-1_03.png)