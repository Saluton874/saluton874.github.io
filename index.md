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

# チェシャちの備忘録

## 主なリポジトリ

### [makirin_AI_v2](https://github.com/Saluton874/makirin_AI_v2)

<span style="color: red">**未完成**</span>の人工無脳プログラムです。

#### 関連ページ

- [datasetの中身について](https://github.com/Saluton874/makirin_AI_v2/blob/main/mod/dataset/README.md)
	- リポジトリをcloneした際の、足りないデータに関する補足です

---

## プログラム毎の備忘録

（準備中）

---

## 簡単な自己紹介

| 登録日 | 好きな言語 | レベル | 夢 |
--------|----------|-------|----|
|2022年5月9日|Python3|初心者|人工無脳を作ること|

**Powered by [Grass-Graph](https://grass-graph.appspot.com){:target="_blank":rel="noopener"}**
<a href="https://github.com/Saluton874" target="_blank" rel="noopener">
<img src="https://grass-graph.appspot.com/images/Saluton874.png" width="100%" class="grass-graph">
</a>

---

## 参考文献

順不同。（準備中）

---

## 日記

- [めいたそ日記](meitaso.md)
	- ときめきや思い出を忘れないように。

---

{: align="center"}
(c) 2022 [Saluton874](https://github.com/Saluton874)