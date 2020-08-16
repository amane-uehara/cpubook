# 本書の対象のFPGA評価ボード

本書のソースコードは極めて原始的なので、大抵どんなボードで動きます。
つまりどのボードを購入しても(このページに載っていないボードでも)問題ありません。

しかし初心者の方は、多機能でハイスペックで高価なボードより、むしろシンプルで扱いやすく安価なボードを選ぶのが良いと思います。
以下では1万円程度で購入できるボードをいくつか紹介します。
これより安いボードを買うと、取り扱いが厄介(ハンダ付け等の作業が要求される)になります。

# Arty-S7-50

* これが超おすすめ！！
* Digilent社の製品
* Xilinx社のFPGAコア「Spartan-7」を搭載
* 秋月電子の通販だと13000円ぐらい。Amazonだと20000円ぐらい。

このサポートサイトは、このボードを想定して作っています。
いくつか参考URLを並べます。

* Xilinx社の説明ページ <https://japan.xilinx.com/products/boards-and-kits/1-pnziih.html>
* Digilent社の説明ページ <https://store.digilentinc.com/arty-s7-spartan-7-fpga-board-for-hobbyists-and-makers/>
* 秋月電子の通販ページ <http://akizukidenshi.com/catalog/g/gM-12558/>

# Arty-S7-25

* Arty-S7-50のダウングレード版
* 扱える回路規模やBRAMのサイズは、Arty-S7-50の半分以下
* 秋月電子の通販には在庫が無さそう。Amazonだと17000円ぐらい。

これを買うなら、上記の Arty-S7-50 を買った方がオトクだと思います。
いちおう参考URLを並べます。

* Xilinx社の説明ページ <https://japan.xilinx.com/products/boards-and-kits/1-ulj76y.html>
* Digilent社の説明ページ <https://store.digilentinc.com/arty-s7-spartan-7-fpga-board-for-hobbyists-and-makers/>

# Arty

* Digilent社の製品
* Xilinx社のFPGAコア「Artix-7」を搭載
* 少し古い製品
* 秋月電子の通販だと16000円ぐらい

参考URLを並べます。

* Xilinx社の説明ページ <https://japan.xilinx.com/products/boards-and-kits/arty.html>
* Digilent社の説明ページ <https://reference.digilentinc.com/reference/programmable-logic/arty/start>
* 秋月電子の通販ページ <http://akizukidenshi.com/catalog/g/gM-14484/>

# DE0-Nano

* Terasic社の製品
* Intel社のFPGAコア「Cyclone IV」を搭載
* USB-UART機能が付いていない (Artyファミリーには付いている)
* 開発環境ソフトはXilinx社のVivadoではなく、Intel社のQuartusを使う
* マルツの通販だと12000円ぐらい

これはVivadoではなくQuartusを使用して開発します。
筆者の怠慢により、Quartusのインストール方法と使用方法のページは未作成です。
動作確認は取れているので、そのうち説明ページを作ります。

参考URLを並べます。

* Intel社の説明ページ <https://www.intel.co.jp/content/www/jp/ja/programmable/products/boards_and_kits/dev-kits/partners/kit-terasic-de0-nano.html>
* Terasic社の説明ページ <https://www.terasic.com.tw/cgi-bin/page/archive.pl?No=1046>
* マルツの通販ページ <https://www.marutsu.co.jp/pc/i/557709/>
