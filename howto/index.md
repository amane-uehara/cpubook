# 回路を動かす手順

たぶん大半の方はFPGA評価ボードをお持ちでないと思います。
そこでまず最初に、開発環境を整えてCPUの回路をシミュレートしてみましょう。
FPGA評価ボードを買うのは後からでも大丈夫です。

### Windowsユーザーの方へ

FPGAを扱うにはWindowsが一番楽です。

ここでは説明の例として
[Arty-S7-50](https://japan.xilinx.com/products/boards-and-kits/1-pnziih.html)
というボードを想定しています。
しかし回路図の描画や電圧シミュレーションについては、ボードが無くても実行可能です。

それでは以下の手順でCPUを作って動かして下さい！

1. [Vivadoのダウンロード](../download/index.md)
2. [Vivadoのインストール](../install/index.md)
3. [Vivadoへのデバイス情報の追加](../board/index.md)
4. [プロジェクトの作成](../project/index.md)
5. [回路図の表示](../schematic/index.md)
6. [電圧シミュレーション](../wave/index.md)
7. [ソースコードのコンパイル](../compile/index.md)

手順1から6についてはFPGA評価ボードを使用しません。
これだけでも、だいぶCPUを作って動かした感があります。

手順7のソースコードのコンパイルを済ませたら、FPGA評価ボードが欲しくなると思います。
購入の際は

* [本書の対象のFPGA評価ボード](../product/index.md)

を参考に、好きなボードを選んで下さい。

### Linuxユーザーの方へ

Xilinx社のサポートページ

<https://japan.xilinx.com/support/download.html>

の「ザイリンクス統合インストーラー Linux 用自己解凍型ウェブ インストーラー」
をダウンロードして、Vivadoをインストールして下さい。
基本的にWindows版と同じように扱えるはずです。

### Macユーザーの方へ

MacでFPGAを扱うのは、かなり厄介です。
何らかの方法でMac上にLinuxの環境を作って、その上でVivadoを動かすことになります。

* デュアルブートでLinuxを入れて、その上でVivadoを動かす
* Docker等でMac上にLinux環境を作り、その上でVivadoを動かす

などの方法が考えられますが、いずれにせよテクニカルです。
もし動かなければ、2万円程度で中古ノートのWindows 7を調達するのが楽だと思います。
