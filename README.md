# micro:bitとScratchの連携
## 準備
以下の2つのプログラムのインストールが必要です。
1. スクラッチオフラインエディター<br>
https://scratch.mit.edu/download
2. s2microbit-ble<br>
https://memakura.github.io/s2microbit-ble/

1は
「Scratchをダウンロードする方法を画像つきで詳しく解説！」
https://blog.codecamp.jp/scratch-download
なども参考になると思います。

## デモプログラム
「準備」が整ったらスクラッチオフラインエディターで読み込んでください。

ねこから逃げろmicrobit版.sb2<br>
1. bluetooth接続したmicro:bitを傾けた方向にネズミが動きます。
2. ピンチになればBボタンを押すことで爆弾を置き、ネコを動転させることができます。
3. 画面左上の数字は、ねずみが最初にネコに捕まるまで、秒数（＝得点）をカウントします。
4. 画面右上、対戦モードを「２」にすると、ネコをマウスで操作することができ、二人で遊ぶことができます。

microbit加速度センサーデモ.sb2<br>
加速度センサーを応用して、micro:bitの動き（傾き）をScratchの画面上にリアルタイムで描写するプログラムです。
