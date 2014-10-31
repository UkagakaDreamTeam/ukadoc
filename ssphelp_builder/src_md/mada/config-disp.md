<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE.html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/.htmll1/DTD/.html1-frameset.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="ja" xml:lang="ja">
<head>
  <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
  <meta http-equiv="content-style-type" content="text/css" />
  <title>設定：表示</title>
  <link rel="stylesheet" type="text/css" href="about.css" />
</head>
<body>
<div id="sidebar">
	<iframe src="contents.html" name="sidebar">
		フレーム非対応の環境では以下の目次ページからご覧ください。

[目次](contents.html)
	</iframe>
</div>
<div id="text">
<div id="breadcrumb">
	<span class="Upper">[目次](contents.html)</span>
	<span class="Upper">[設定](config.html)</span>
	<span class="Upper">本体設定</span>
	表示
</div>
<!-------------------------------------------------------------------------------------------------------------------------------->

# 設定：表示

	画像左側のリストを<span class="Doing">クリック</span>で、それぞれのダイアログのページに対応する解説のページへ移動します。

![本体設定ダイアログ表示](image/config-disp/0.png)
	<map name="configdialog" id="configdialog">
		<area shape="rect" coords="14,31,137,46" href="config-ippan.html" alt="一般">
		<area shape="rect" coords="14,47,137,66" href="config-ghost.html" alt="ゴースト(1)">
		<area shape="rect" coords="14,66,137,82" href="config-ghost2.html" alt="ゴースト(2)">
		<area shape="rect" coords="14,82,137,98" href="config-folder.html" alt="フォルダ">
		<area shape="rect" coords="14,98,137,114" href="config-disp.html" alt="表示">

		<area shape="rect" coords="14,115,137,133" href="config-talk.html" alt="喋り/バルーン">
		<area shape="rect" coords="14,134,137,152" href="config-conn1.html" alt="接続(1)">
		<area shape="rect" coords="14,150,137,168" href="config-conn2.html" alt="接続(2)">
		<area shape="rect" coords="14,167,137,185" href="config-pop.html" alt="POP">
		<area shape="rect" coords="14,184,137,202" href="config-extprog.html" alt="外部アプリ">

		<area shape="rect" coords="14,201,137,219" href="config-im.html" alt="IM">
		<area shape="rect" coords="14,218,137,236" href="config-ipmes.html" alt="IPMessenger">
		<area shape="rect" coords="14,235,137,253" href="config-i18n.html" alt="国際化">
		<area shape="rect" coords="14,252,137,270" href="config-dev.html" alt="開発/その他">
	</map>

このページでは右クリックメニューの「設定」サブメニューにある項目「本体設定」で開くダイアログの、「表示」ページについて解説しています。

## 各項目の解説

<dl>
   <dt>カーソルを変更しない</dt>   
   <dd>ON状態では、マウスカーソル付きバルーンであっても、カーソルを変更しないようにします。

   バルーンによりマウスカーソルが変更されるのが嫌な場合は、ONにしてお使いください。　</dd>

   <dt>デスクトップ下端オフセット</dt>
   <dd>デスクトップ下端から何ドットずらすかを指定します。

   「タスクバーを自動的に隠す」設定時に、タスクバーの裏に隠れてしまわないように設定する使い方などがあります。　</dd>

   <dt>メニュー幅を背景画像に合わせる</dt>
   <dd>通常、メニューの幅はメニュー項目の幅の分だけ表示されていますが、これをゴースト付属のメニュー画像の幅に合わせます。

   これにより、ゴーストメニュー画像の全体が見えるようになります。
   </dd>

   <dt>メニュー選択中にプレビュー画像を表示する</dt>
   <dd>右クリックメニューでゴースト切換え・呼び出し・シェル切換え・バルーン切換え等のメニューの選択中に、対応している場合はプレビュー画像(thumbnail.png)を表示します。</dd>

   <dt>メニューの縦方向の余白設定</dt>
   <dd>右クリックメニューの行ごとの余白を設定します。

   Windowsのメニューと同じ間隔は2ですが、必要に応じて見やすくするために変更すると良いでしょう。</dd>

   <dt>一部のメニューを階層化する</dt>
   <dd>[設定：フォルダ](config-folder.html)で複数フォルダの読み込みを設定した場合に、これをONにするとメニューがフォルダごとに分けられます。

   ゴースト・バルーン等、フォルダ設定可能なすべてのメニューに適用されます。

   多くのゴーストをインストールしており、整理して表示したい場合に使うと良いでしょう。</dd>

   <dt>ゴースト・バルーン・最近使ったものメニューの最大文字数</dt>
   <dd>一部の名前の長いゴーストを表示するために、メニューで画面が埋め尽くされてしまう場合の対策用です。ここで設定した文字数を超える場合、後ろに"..."がついて省略表示となります。

   画面が狭い人は少なめに設定しておくと良いでしょう。</dd>

   <dt>最近使ったものメニューの最大記録数</dt>
   <dd>「最近使ったもの」に残す履歴の数です。この回数より前に起動/使用した項目は消えていきます。</dd>

   <dt>Flip3D中でも表示する。<span class="System">[Windows Vista以降のみ]</span></dt>
   <dd>Filp3Dでウインドウを切り替えている間もキャラクター＋バルーンを表示したままにします。いつでもキャラクターを表示しておきたい場合に使用して下さい。</dd>

   <dt>タスクバーにキャラクターウインドウを表示</dt>
   <dd>
   通常キャラクターが表示されるウインドウはタスクバーに表示されませんが、Windows 7以降などで、ジャンプリストやプレビューを使いたい場合に、表示しておきたい場合があります。

その時に、このオプションを有効にすると、上記機能が使えるようになります。

   <dt>フルスクリーンのアプリが起動した時に最小化</dt>
   <dd>ゲームなどフルスクリーン表示するアプリケーションを起動した時に、自動的にキャラクターを最小化表示します。</dd>
</dl>

### 半透明ウインドウ <span class="System">[Windows 2000/XP以降のみ]</span>

"Layered Window"とも呼ばれる、Windows 2000以降で登場した半透明ウインドウを実現する機能を使う設定です。

使用可能な場合は標準で有効になっています。

<dl>
  <dt>透明化(Layered Window)を使う</dt>
   <dd>
   WindowsXPや2000では、ウインドウを半透明にできる機能が備わっています。これをチェックするとその機能を利用して表示します。

   なお、XP以降では、特に半透明に設定しない場合でも、この機能を利用した場合のほうが比較的高速となっています。
   </dd>

   <dt>クロスフェーダを使う</dt>
   <dd>
   キャラクターの表情が切り替わったり、バルーン等の表示・非表示が切り替わる際に、じわじわと切り替わってゆくフェードイン・フェードアウト的な効果を使います。
   </dd>

   <dt>ドラッグ中に透明度を上げる</dt>
   <dd>キャラクターのウインドウをドラッグ中に、下にあるものが見えやすいように、不透明度を下げて裏側が見えるようにします。</dd>

   <dt>（本体/バルーン/カレンダーの透明度設定）</dt>
   <dd>それぞれのウインドウの透明度をスライダーを動かして調節します。</dd>
</dl>

## 下部のボタン

<dl>
	<dt>ヘルプ</dt>
	<dd>
		本体設定ダイアログの、設定中のページのヘルプ（つまりこのページ）を開きます。

ダイアログ右上の「？」マークも同様です。
	</dd>

	<dt>閉じる</dt>
	<dd>
		本体設定ダイアログを閉じます。

ダイアログ右上の「×」マークも同様です。
	</dd>
</dl>

<!-------------------------------------------------------------------------------------------------------------------------------->
<div id="navigation">
	<span class="Prev">[設定：フォルダ](config-folder.html)</span>
	<span class="Return">[目次](contents.html)</span>
	<span class="Next">[設定：喋り/バルーン](config-talk.html)</span>
</div>
</div>
<body>
</html>