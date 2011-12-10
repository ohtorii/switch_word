monday.vimを秀丸エディタへ移植してみた。
========

vimエディタに面白いマクロがあったので秀丸エディタへ移植してみました。

### キーを押すと単語をインクリメント・デクリメントできます。 ###
- January → February → March → April
- class → struct
- private → public → protected
- iterator → const_iterator
- true → false

### 動作イメージ ###
- ![Alt text](http://cdn-ak.f.st-hatena.com/images/fotolife/o/ohtorii/20110708/20110708160519.gif)
- ![Alt text](http://cdn-ak.f.st-hatena.com/images/fotolife/o/ohtorii/20110708/20110708160544.gif)

### ファイルの説明 ###
- switch_word_next.mac  単語を次へ切り替える
- switch_word_prev.mac  単語を前に戻す
- switch_word.mac       内部利用のマクロ

### 導入方法 ###
下記３ファイルを秀丸エディタのスクリプトディレクトリへコピーします。
-switch_word.mac
-switch_word_next.mac
-switch_word_prev.mac

「switch_word_next.mac／switch_word_prev.mac」にショートカットキーを割り当てます。
switch_word.macにはショートカットキーを割り当てないで下さい。（内部利用のマクロなので）
