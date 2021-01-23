このページではXilinx社のFPGA統合開発環境「Vivado」について説明します。
たぶん読者の大半はFPGA評価ボードをお持ちでなく、馴染みも薄いと思いますので、細かい話はピンと来ないかもしれません。

最重要なポイントは、**今すぐFPGA評価ボードを買う必要はない**、ということです。
回路図の描画や電圧シミュレーションについては、ボードが無くても実行可能なのです。
そこでまず最初に、開発環境を整えてCPUの回路をシミュレートしてみます。

# Windowsユーザーの方へ

話の都合上、ここでは説明の例として
[Arty-S7-50](https://japan.xilinx.com/products/boards-and-kits/1-pnziih.html)
というFPGA評価ボードを想定します。
以下の手順でCPUを作って動かして下さい！

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

# Linux (Ubuntu) ユーザーの方へ

まず重要なポイントですが
**2020/09/08 現在、Ubuntu20.04ではVivadoが動きません。**
Vivadoを動かすには旧バージョンのUbuntu18.04が必要です。

さてVivadoのインストール方法ですが、まずXilinx社のサポートページ

<https://japan.xilinx.com/support/download.html>

の「ザイリンクス統合インストーラー Linux 用自己解凍型ウェブ インストーラー」
をダウンロードしてVivadoをインストールして下さい。
基本的にWindows版と同じように扱えるはずです。

ただしLinux版では、デフォルトでケーブルドライバーがインストールされないようです。
これがないと、FPGA評価ボードをUSBで接続してもVivadoに認識されません。
下記リンクを参考に、ケーブルドライバーをインストールして下さい。

* <https://japan.xilinx.com/support/answers/59128.html>
* <http://openit.kek.jp/training/2015/fpga/docs/ar59128.pdf>

# Macユーザーの方へ

MacでFPGAを扱うのは、かなり厄介です。
何らかの方法でMac上にUbuntu18.04の環境を作って、その上でVivadoを動かすことになります。

* デュアルブートでUbuntu18.04を入れて、その上でVivadoを動かす
* Docker等でMac上にUbuntu18.04の仮想環境を作り、その上でVivadoを動かす

などの方法が考えられますが、いずれにせよテクニカルです。
もし動かなければ、2万円程度で中古ノートのWindows 7を調達するのが楽だと思います。
