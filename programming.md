<link href="https://meitaso.net/assets/css/github-page-design.css" rel="stylesheet">
<div class="color-change"><label for="white"></label><label for="dark"></label></div>
<input type="radio" id="white" name="colors" value="white">
<input type="radio" id="dark" name="colors" value="dark">

## プログラミング雑記

### 2022年10月31日
- `tone_changer.py`の処理を大幅に増やした。バグが増えた。

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