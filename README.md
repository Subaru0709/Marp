#スライドのサンプル
https://Subaru0709.github.io/Marp/MakeMd/index.html
<br>スライドの内容は適当です

趣味でスライドをmarpで作ってアニメーションなどをつけてみようかなと思い、作ってみました。

<br>(スライドにアニメーションを入れて見やすくなったかとか、そもそもアニメーションが必要かどうかなどは一旦置いときます)

#実行方法
<br> Marp CLIを利用して、CSSをmdに反映させてスライドを一旦htmlファイルにしています。
<br> marp --theme ./CSS/slide.css ./MakeMd/index.md

htmlを開けばスライドが見れます。


#fileについて
<br>./CSS でCSSを記述
<br>./Download でanimation.cssなどをダウンロード
<br>./graph は必要に応じてグラフを書きたいときに使用
<br>./MakeMd にはMarkdownとhtmlが保存されている

#コードについて
<br> 元々公開するために作ったものではないのでタグの名前が雑になっている部分もあります(修正予定)
