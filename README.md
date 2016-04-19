# HSP3DPrinting
3D printing in HSP
![製作例](https://raw.githubusercontent.com/gutugutu3030/HSP3DPrinting/master/HSP%E3%83%97%E3%83%AA%E3%83%B3%E3%83%86%E3%82%A3%E3%83%B3%E3%82%B0.png)
とても簡単に3Dプリンタを制御できます

# 使い方
sample.hspを見てね
startPrintingの引数はCOMポートの番号です

# バグ
- 時々最後まで命令が実行されない
- ミスってqueueじゃなくてstackで実装しちゃった
