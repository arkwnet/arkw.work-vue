<template>
	<div>
		<!-- 製品情報 -->
		<h1 class="heading">製品情報</h1>
		<div class="pr_menu">
			<a href="javascript:changeProductsMenu('windows')"><div class="pr_menu_item pr_menu_selected" id="pr_menu_windows">PCソフトウェア</div></a>
			<a href="javascript:changeProductsMenu('web')"><div class="pr_menu_item" id="pr_menu_web">ウェブアプリ</div></a>
			<a href="javascript:changeProductsMenu('dev')"><div class="pr_menu_item" id="pr_menu_dev">開発者向け</div></a>
		</div>
		<p>
			<div class="pr_list_bg">
				<!-- 製品情報：Windows -->
				<div class="pr_list" id="pr_item_windows">
					<a href="https://arkw.net/products/win/wsm/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/wsm.png"></div>
							<div class="topics_main">
								<h1>WinSmartWatch</h1>
								<p>スマートウォッチをモチーフとしたデスクトップアクセサリ</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/win/cpr/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/cpr.png"></div>
							<div class="topics_main">
								<h1>コピペレコーダー</h1>
								<p>クリップボードのコピー履歴を保持し、再利用できるソフトウェア</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/win/eims/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/eims.png"></div>
							<div class="topics_main">
								<h1>はじめての写真管理S</h1>
								<p>視覚的かつシンプルに大量の写真を管理できるソフトウェア</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/webgeki/wg/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/webgeki.png"></div>
							<div class="topics_main">
								<h1>ウェブ撃</h1>
								<p>オープンソースの次世代型ウェブサイト制作ツール</p>
							</div>
						</div>
					</a>
					<a href="https://nagaharu.github.io/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/nghr.png"></div>
							<div class="topics_main">
								<h1>Nagaharu</h1>
								<p>シンプルに使えるオープンソースの文書作成ソフトウェア</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/win/TypingFactory/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/typing.png"></div>
							<div class="topics_main">
								<h1>タイピングファクトリー</h1>
								<p>英単語や地名など短い文を連続して入力するタイピングゲーム</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/win/TriEditorLE/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/tried.png"></div>
							<div class="topics_main">
								<h1>TriEditor LE</h1>
								<p>学習用途に特化したHTML/CSS用のテキストエディタ</p>
							</div>
						</div>
					</a>
					<br>
					<p><b>開発終了 － Windows 8.1/10</b></p>
					<a href="https://arkw.net/products/win/eim2/"><img src="img/pr_icon/eim2.png" class="main_social">はじめての写真管理2</a><br>
					<a href="https://arkw.net/products/win/old/EImageManage_1.1.2.exe"><img src="img/pr_icon/download.png" class="main_social">はじめての写真管理 Ver.1.1.2 インストーラー版</a><br>
					<a href="https://arkw.net/products/win/old/EImageManage_1.1.2.zip"><img src="img/pr_icon/folder-zipper.png" class="main_social">はじめての写真管理 Ver.1.1.2 ポータブル版</a><br>
					<a href="https://arkw.net/products/win/old/EDigitalDiary_1.0.zip"><img src="img/pr_icon/folder-zipper.png" class="main_social">はじめてのデジタル日記 Ver.1.0</a><br>
					<a href="https://arkw.net/products/win/old/EasyAddress_1.0.1.zip"><img src="img/pr_icon/folder-zipper.png" class="main_social">かんたん住所録 Ver.1.0.1 修正版</a><br>
					<a href="https://arkw.net/products/win/old/e_page_editor_1.0.1.zip"><img src="img/pr_icon/folder-zipper.png" class="main_social">E-Page Editor Ver.1.0.1</a><br>
					<a href="https://arkw.net/products/win/old/Okoshimon_1.0.1.zip"><img src="img/pr_icon/folder-zipper.png" class="main_social">おこしもん Ver.1.0.1</a><br>
					<a href="https://arkw.net/products/win/old/SimpleShinchoku_1.0.zip"><img src="img/pr_icon/folder-zipper.png" class="main_social">シンプル進捗管理 Ver.1.0</a><br>
					<a href="https://arkw.net/products/win/old/Jikagaki_1.0.1.zip"><img src="img/pr_icon/folder-zipper.png" class="main_social">直書きランチャー Ver.1.0.1</a><br>
					<a href="https://arkw.net/products/win/old/ShiseiChecker_1.0.zip"><img src="img/pr_icon/folder-zipper.png" class="main_social">姿勢チェッカー for Windows Ver.1.0</a><br>
				</div>
				
				<!-- 製品情報：ウェブアプリ -->
				<div class="pr_list" id="pr_item_web">
					<a href="https://arkw.net/products/web/prohaya/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/prohaya.png"></div>
							<div class="topics_main">
								<h1>プロ生早押しクイズ</h1>
								<p>プロ生ちゃんや情報処理研究会のキャラクターと早押しクイズで対決！</p>
							</div>
						</div>
					</a>
					<a href="https://psk.arkw.net/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/psk.png"></div>
							<div class="topics_main">
								<h1>プロ生進捗管理</h1>
								<p>その日に出した進捗を気軽に記録できるウェブサービス</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/web/dokaben/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/dokaben.png"></div>
							<div class="topics_main">
								<h1>ドカベンメーカー</h1>
								<p>「ドカベン」のロゴ風画像を作成できるウェブアプリ</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/web/hakase/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/hakase.png"></div>
							<div class="topics_main">
								<h1>教えて！ハカセ ジェネレータ</h1>
								<p>「教えて！○○ハカセ」の画像を作成できるウェブアプリ</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/web/smsg/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/smsh.png"></div>
							<div class="topics_main">
								<h1>支離滅裂な思考・発言 ジェネレータ</h1>
								<p>「支離滅裂な思考・発言」の画像を作成できるウェブアプリ</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/web/kintetsu/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/kintetsu.png"></div>
							<div class="topics_main">
								<h1>近鉄車番検索</h1>
								<p>近鉄車両の車両番号、両数、電算記号などを検索できるウェブアプリ</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/web/meitetsu/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/meitetsu.png"></div>
							<div class="topics_main">
								<h1>名鉄車番検索</h1>
								<p>名鉄車両の車両番号、両数、電算略号などを検索できるウェブアプリ</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/web/atck/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/atck.png"></div>
							<div class="topics_main">
								<h1>Article Checker</h1>
								<p>文章を検査し、「日本語の使い方」や「読みやすさ」をチェックするツール</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/web/mygen/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/mygen.png"></div>
							<div class="topics_main">
								<h1>マイ元号メーカー</h1>
								<p>2019年エイプリルフール企画</p>
							</div>
						</div>
					</a>
					<br>
					<p><b>Arakawa Web Tools</b></p>
					<a href="https://arkw.net/products/web/tools/kutouten/"><img src="img/pr_icon/icon_kutouten_16.png" class="main_social">句読点変換</a><br>
					<a href="https://arkw.net/products/web/tools/indent/"><img src="img/pr_icon/icon_indent_16.png" class="main_social">インデント変換</a><br>
					<a href="https://arkw.net/products/web/tools/wordcount/"><img src="img/pr_icon/icon_wordcount_16.png" class="main_social">文字数カウント</a><br>
				</div>
				
				<!-- 製品情報：開発者向け -->
				<div class="pr_list" id="pr_item_dev">
					<a href="https://arkw.net/products/dev/arkw_tmpl/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/atmpl.png"></div>
							<div class="topics_main">
								<h1>Arakawa Template</h1>
								<p>汎用的なウェブサイト用CSSテンプレート</p>
							</div>
						</div>
					</a>
					<a href="https://github.com/arkwnet/AkariFramework">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/akari.png"></div>
							<div class="topics_main">
								<h1>AkariFramework</h1>
								<p>シンプルなCSSフレームワーク（Bijou CSS Framework ベース）</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/dev/katamuki_js/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/katamuki.png"></div>
							<div class="topics_main">
								<h1>Katamuki.js</h1>
								<p>ウェブページ上の文字を綺麗に表示できるJavaScriptライブラリ</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/dev/emotion_cover/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/emotion_cover.png"></div>
							<div class="topics_main">
								<h1>Emotion Cover</h1>
								<p>HTML5 Canvas/JavaScript製のスライドショースクリプト</p>
							</div>
						</div>
					</a>
					<a href="https://arkw.net/products/dev/AoiEngine/">
						<div class="topics">
							<div class="topics_icon"><img src="img/pr_icon/aoi.png"></div>
							<div class="topics_main">
								<h1>AoiEngine</h1>
								<p>コンテンツ開発を効率化するJavaScriptゲームエンジン</p>
							</div>
						</div>
					</a>
				</div>
			</div>
		</p>
		<br>

		<!-- コンテンツ -->
		<h1 class="heading">コンテンツ</h1>
		<p>
			<a href="http://arkw.client.jp">Arakawa No-SSL</a><br>
			<a href="https://arkw.net/index2.html" target="blank">Arakawa 旧トップページ</a><br>
			<a href="https://arkw.net/blog/">Arakawa Blog</a><br>
			<a href="https://arkw.net/contents/bg_archive/">背景画像アーカイブ</a><br>
			<a href="https://arkw.net/contents/axella/">Team Axella 跡地</a><br>
			<a href="https://arkw.work/shiori_sv/"><img src="img/links/shiori.png" class="main_left_banner"></a>
		</p><br>

		<!-- リンク集 -->
		<h1 class="heading">リンク集</h1>
		<p>
			<a href="http://yotiosoft.com/" target="blank"><img src="img/links/yotiosoft_logo_2.png" width="180"></a><br>
			<a href="https://nona-takahara.github.io/" target="blank"><img src="img/links/taka_impact.png" width="180"></a><br>
			<a href="http://bvetk.webcrow.jp/" target="blank"><img src="img/links/bvetk.png"></a><br>
			<a href="https://gakujochan.com/" target="blank"><img src="img/links/gakujo.png" width="180"></a><br>
			<a href="https://xr-hamaria.github.io/virtual-inf/" target="blank"><img src="img/links/banner_120_90.png"></a><br>
			<a href="https://hishoutai.arkw.net/" target="blank"><img src="img/links/hishoutai.png"></a><br>
			<a href="https://satoyama-nogyo.com/" target="blank">里山農業プロジェクト</a><br>
			<a href="https://xeltica.work/" target="blank">Xeltica.work</a><br>
		</p><br>
		<p>
			<a href="https://www.shizuoka.ac.jp/" target="blank"><img src="img/links/shizuoka.gif" width="180" class="link-banner"></a><br>
			<a href="http://hsp.tv/" target="blank"><img src="img/links/hsptv_bnr.gif"></a><br>
			<a href="https://pass-case.com/" target="blank">Pass-case</a><br>
			<a href="http://shinohara03.starfree.jp/" target="blank">Optinum Surviter</a><br>
			<a href="https://uotaka.hamazo.tv/" target="blank">うおたか奮闘記</a>
		</p>
	</div>
</template>

<style scoped lang="scss">
@import "./common.scss";

.pr_menu {
	margin-top: 10px;
	overflow: hidden;
	a {
		color: $arkw-color;
	}
}

.pr_menu_item {
	margin-top: 5px;
	margin-right: 10px;
	padding: 5px 10px;
	float: left;
	border: solid 1px $arkw-color;
	border-radius: 15px;
}

.pr_menu_selected {
	background-color: $arkw-color;
	color: $white;
	transition-property: background-color,color,text-shadow;
	transition-duration: 0.1s;
	transition-timing-function: ease-in-out;
}

.pr_list_bg {
	margin: 10px 0;
}

#pr_item_web, #pr_item_dev {
	display: none;
}
</style>