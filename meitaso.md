<style>
	:root {
		--white-bg-color: #fff;
		--white-text-color: #000;
		--dark-bg-color: #000;
		--dark-text-color: #fff;
		--dark-h-border: #232323;
		--dark-table-border: #36383b;
		--link-color: #1b94e0;
		}
	.color-change{
		text-align: center;
		padding:1rem 0;
	}
	[type="radio"]{
		position: fixed;
		left: -9999px;
		}
	label{
		display: inline-block;
		cursor: pointer;
		width:2rem;
		height:2rem;
		border-radius: 50%;
		border: 1px solid var(--link-color);
		}
	label[for="white"]{background:#eee; margin-right:1rem;}
	label[for="dark"]{background:#434343;}
	a, a:link, a:hover, a:active{
		color:var(--link-color);
		}
	body{
		transition: all 0.3s ease-in-out;
		}
	/* ホワイトスイッチ */
	body:has([id="white"]:checked) {
		color: var(--white-text-color);
		background: var(--white-bg-color);
		}
	body:has([id="white"]:checked) .grass-graph{
		filter: none;
		}
	body:has([id="white"]:checked) [for="white"]::before {
		background: var(--white-text-color);
		}
	/* ダークスイッチ */
	body:has([id="dark"]:checked) {
		color: var(--dark-text-color);
		background: var(--dark-bg-color);
		}
	body:has([id="dark"]:checked) h1,
	body:has([id="dark"]:checked) h2{
		border-bottom-color: var(--dark-h-border);
		}
	body:has([id="dark"]:checked) hr{
		background-color: var(--dark-table-border);
		}
	body:has([id="dark"]:checked) table th,
	body:has([id="dark"]:checked) table td{
		border:1px solid var(--dark-table-border);
		}
	body:has([id="dark"]:checked) table tr{
		background-color: var(--dark-bg-color);
		bprder-top: 1px solid var(--dark-table-border); 
		}
	body:has([id="dark"]:checked) .grass-graph{
		filter: invert();
		}
	body:has([id="dark"]:checked) [for="dark"]::before {
		background: var(--dark-text-color);
		}
	/* ダークモード用 */
	@media (prefers-color-scheme: dark) {
		body{
			color: var(--dark-text-color);
			background: var(--dark-bg-color);	
		}
		h1, h2{ border-bottom-color: var(--dark-h-border); }
		hr{ background-color: var(--dark-table-border); }
		table th, table td{
			border:1px solid var(--dark-table-border);
		}
		table tr{
			background-color: var(--dark-bg-color);
			bprder-top: 1px solid var(--dark-table-border); 
		}
		.grass-graph{filter: invert();}
	}
	
</style>
<div class="color-change"><label for="white"></label><label for="dark"></label></div>
<input type="radio" id="white" name="colors" value="white" checked>
<input type="radio" id="dark" name="colors" value="dark">

## めいたそ日記

### 2022年10月27日
- 朝も電話してくれた。マイナス思考は仕方ないけれど、励ましに対して向き合うことにした。許してくれるだろうか。

### 2022年10月26日
- めいたそは耳鼻科さん。お鼻の調子が良くなりますように。辛そうだもん。
- 貼り薬にしてもらうと言っていた。効くやつ頼むよ。
- 帰宅したら[REALITY](https://reality.app){:target="_blank":rel="noopener"}のコラボ枠がいっぱいだった。
- 釣りゲームのシーズンが終わるまで、ログインするのを止めようかな。
- 電話でいっぱい励ましてくれたけど心が拒否してしまった

### 2022年10月25日
- めいたそが美容院へ行った。より可愛くなって帰ってくると思うと胸がときめく。
- ブリーチして赤ピンクに染めたそうな。柔らかい髪色が優しさを強調させる。
- ショートも似合うのは羨ましいな。
- 私も10月31日16:00に美容院へ行ってくる予定。忘れそう。

{: align="center"}
(c) 2022 [Saluton874](https://github.com/Saluton874)