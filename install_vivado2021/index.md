# Vivado2021のインストール

Vivado2021のインストーラーをダウンロードします。
ダウンロード方法の詳細は
[こちら](../download/index.md)
のページをご参照下さい。

1  
![ ](install_vivado2021_001.png)

ダウンロードが完了したら、クリックして開きます。

2  
![ ](install_vivado2021_002.png)

以下の画面が開くので、`Next`をクリックします。

3  
![ ](install_vivado2021_003.png)

以下のアカウント認証画面が開きます。
`User ID` は Xilinx アカウント作成時に登録したメールアドレスです。
`Password` も Xilinx アカウント作成時に登録したものを入力します。

4  
![ ](install_vivado2021_004.png)

入力を終えたら`Next`をクリックします。

5  
![ ](install_vivado2021_005.png)

以下のインストール内容の選択画面が開きます。
`Vivado`を選択します。

6  
![ ](install_vivado2021_006.png)

チェックしたら`Next`をクリックします。

7  
![ ](install_vivado2021_007.png)

インストールするVivadoの種類が表示されるので、`Vivado ML Standard`を選択します。

8  
![ ](install_vivado2021_008.png)

チェックしたら`Next`をクリックします。

9  
![ ](install_vivado2021_009.png)

インストールする内容のチェックリストが表示されます。以下はデフォルトの設定です。

10  
![ ](install_vivado2021_010.png)

以下のように必要な項目だけチェックを残せば、インストール容量を削減できます。
今回は`Arty-S7-50`というFPGA評価ボードを動かしたいので、`Devices`のところを`7-Series`だけ残しました。

11  
![ ](install_vivado2021_011.png)

以下のライセンスの同意確認画面が開きます。
以下の2箇所が空白になっているので、チェックします。

12  
![ ](install_vivado2021_012.png)

チェックしたら`Next`をクリックします。

13  
![ ](install_vivado2021_013.png)

Vivadoのインストール場所と、使用できるユーザーを設定します。
ここはデフォルトの設定のまま Next を押してOKです。

14  
![ ](install_vivado2021_014.png)

ディレクトリの作成確認に`Yes`と答えます。

15  
![ ](install_vivado2021_015.png)

以下の最終確認画面が開きます。
サイズが大きいので、パソコンの記憶容量を確認してディスクがあふれないことを確かめて下さい。
ここで`Install`をクリックすると、統合開発環境本体のダウンロードが始まります。

16  
![ ](install_vivado2021_016.png)

ダウンロードとインストールが始まります。
しばらく待ちます。

17  
![ ](install_vivado2021_017.png)

インストールが完了すると、デスクトップに`Vivado`のアイコンが生成されます。
なお起動時に「Could not locate Quick Help files. Quick Help will not be available.」という警告が出ることがありますが、実害はありません。

起動が確認できたら終了してOKです。
引き続き
[Vivadoへのデバイス情報の追加](../board/index.md)
に進んで、デバイスファイルを追加して下さい。
