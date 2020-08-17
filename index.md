これはマイナビ出版の書籍

<a target="_blank" href="https://www.amazon.co.jp/gp/product/4839968519/ref=as_li_tl?ie=UTF8&camp=247&creative=1211&creativeASIN=4839968519&linkCode=as2&tag=tukuroucpu-22&linkId=1a4efec3926c4cd2cf5e72bee2e737de">作ろう！CPU ～基礎から理解するコンピューターのしくみ～</a><img src="//ir-jp.amazon-adsystem.com/e/ir?t=tukuroucpu-22&l=am2&o=9&a=4839968519" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

のサポートページです。

<a target="_blank"  href="https://www.amazon.co.jp/gp/product/4839968519/ref=as_li_tl?ie=UTF8&camp=247&creative=1211&creativeASIN=4839968519&linkCode=as2&tag=tukuroucpu-22&linkId=7971e347c2e7cd8d52296e29ad0efdab"><img border="0" src="//ws-fe.amazon-adsystem.com/widgets/q?_encoding=UTF8&MarketPlace=JP&ASIN=4839968519&ServiceVersion=20070822&ID=AsinImage&WS=1&Format=_SL250_&tag=tukuroucpu-22" ></a><img src="//ir-jp.amazon-adsystem.com/e/ir?t=tukuroucpu-22&l=am2&o=9&a=4839968519" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

# 本書を購入して下さった方へ

買ってくださってありがとうございます。
感謝感謝です。
たぶん本書の11ページあたりを読んで、このサイトに来て下さったと思います。
そこで

[回路を動かす手順](howto/index.md)

↑
のリンクを開いてCPUを作り、FPGAで動かして下さい。

# 未購入の方へ

本書はCPUを作る本です。
コンピューターの頭脳と呼ばれる、あのCPUを自分で作るのです。
本書の特徴を並べます。

* 小学校レベルの回路から出発し、超単純な CPU (TD4) を作る。
* 電子回路についての事前知識は、一切不要。
* 抵抗や電流に関する数値の計算も、本書には登場しない。
* 代わりに回路図に**「矢印を描く」ことで CPU を理解**する。
* 電子工作やハンダ付けのような作業も、一切不要。
* 代わりにテキスト (ソースコード) で CPU を設計。
* **CPU のコード行数はわずか69行。**(12章のコードの行数)
* FPGA (USBで動く回路生成装置) で CPU の回路を実装。
* **作業開始から約2時間で CPU が完成**し、機械語が動く。
* FPGA は約1万円で購入可能。開発環境ソフトは無料。
* FPGA を買わずにシミュレーター上で CPU を動かすことも可能。
* つまり**書籍代以外は無料**で CPU が作れます。

要するに、超初心者に向けた自作CPUの解説本です。
他書よりはるかに丁寧に書きましたので、一冊目の入門本としてお薦めです。
しかし分かりやすさを追求した結果、完成するCPUが他書と比べてやや低機能になりました。
まず本書でコツをつかんでから、他書を参考に高機能なCPUを作るのが良いと思います。

実際に作る回路を見てみます。

![ ](top/mb-schematic.png)

上図は本書で設計するマザーボードを、FPGA開発環境の回路図ビューアーで表示したものです。
CPUだけ作っても動かないので、マザーボードやROM(メモリー)も作っています。
要するに本書はCPUだけでなく、コンピューター全体を設計して動かす本なのです。

![ ](top/cpu-schematic.png)

上図はCPU内部の回路図です。
まぁよく分からないと思いますが、本書を読めば全て分かります。

![ ](top/wave.png)

上図はCPUを動かしたときの、電圧変動のタイムチャートです。
さっぱり意味不明だと思いますが、上から3段目の`IN_B`とか`MOV_A_IMM`とか`ADD_A_IMM`は、いわゆる「機械語」というやつです。
本書を読めばCPUの言葉が分かるようになります。

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="https://rcm-fe.amazon-adsystem.com/e/cm?ref=qf_sp_asin_til&t=tukuroucpu-22&m=amazon&o=9&p=8&l=as1&IS1=1&detail=1&asins=4839968519&linkId=916b3d5ce6ebc0319c4f6521d8aeff8b&bc1=ffffff&lt1=_top&fc1=333333&lc1=0066c0&bg1=ffffff&f=ifr"></iframe>

# いろいろな方への紹介文

(以下工事中)

# その他

* 更新履歴: <https://github.com/amane-uehara/cpubook/commits/master>
* マイナビ出版のページ: <https://book.mynavi.jp/supportsite/detail/9784839968519.html>
* バグ・誤植の報告先: <https://github.com/amane-uehara/cpubook/issues>
