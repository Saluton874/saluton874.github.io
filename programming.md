<link href="https://meitaso.net/assets/css/github-page-design.css" rel="stylesheet">
<div class="color-change"><label for="white"></label><label for="dark"></label></div>
<input type="radio" id="white" name="colors" value="white">
<input type="radio" id="dark" name="colors" value="dark">

## プログラミング雑記

詰まったことや、困ったこと、頑張ったことの記録。

### 2022年11月05日
- 助動詞以外の分類も、できる限り対応した。[こちらの記事](https://qiita.com/ensan_hcl/items/885588c7d2d99de85b44){:target="_blank":rel="noopener"}を参考にした。
- なんだかもう満足してしまって、燃え尽き症候群中。

### 2022年11月04日
- `tone_changer.py`を強化し、助動詞はひと段落。

### 2022年11月01日
- `tone_changer.py`の大幅な見直しが必要。

### 2022年10月31日
- `tone_changer.py`の処理を大幅に増やした。バグが増えた。
	- [助動詞活用表](https://www.kokugobunpou.com/助動詞/助動詞活用表/#gsc.tab=0){:target="_blank":rel="noopener"}を一通り完了。チェック作業は明日にする。
	- カ変活用（くる）の処理を一旦停止。

### 2022年10月30日
- `tone_changer.py`にてカ変活用（くる）の処理を強化した。
	- 「来らます→**来ます**」「来るらせです→**来させます**」「来るさしです→**来させます**」「来るさせるです→**来させます**」
		- 気がくるいそう。漏れはあると思う。
- `tone_changer.py`にて「ない」から「よう」まで言葉遣いを見直すコードを書いた。
	- MeCabでは「よう」は助動詞ではなく、動詞の未然ウ接続という扱いになっているようだった。
		- 元々日本語分からないから何も問題はなかった。
- 結局「た（だ）」まで進めた。*（範囲が広すぎて、バグの巣窟だろうなあ。）*
- 正しい言葉が変になるバグが発生している。あはははは。
- ~~**起きるせう** 宿題~~ これは「う」が来ること自体おかしいので対応しないことにした。
	- 今現在、**起きるせる**は「起きさせる」へ正しく変換されている。

### 2022年10月28日
- GitHubページのCSSの反映が遅いので、外部CSSの[github-page-design.css](https://meitaso.net/assets/css/github-page-design.css){:target="_blank":rel="noopener"}を読み込むように変更した。
- `tone_changer.py`にて「せる」から「られる」まで言葉遣いを見直すコードを書いた。無論、簡易的なもの。*（簡易という言葉は便利だなあ。）*

### 2022年10月27日
- [GitHubページ](https://saluton874.github.io)をダークモードに対応させつつ、色変更できるようにした。
	- CSSの優先順位の勉強になった。`:has`、`:not`の使い方を学んだ。
- `tone_changer.py`を大幅に改変中。

{: align="center"}
(c) 2022 [Saluton874](https://github.com/Saluton874)