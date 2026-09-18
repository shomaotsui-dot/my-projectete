Magic — Cinematic AR Spellcasting

起動方法
1. Chrome / Edge で HTTPS または localhost から index.html を開いてください。
2. TAP TO BEGIN → カメラを許可。
3. 手をカメラに映して操作します。

ジェスチャー
OPEN: エネルギー召喚
PINCH: 圧縮・整形
FIST: チャージ
SWIPE: 魔法弾発射
両手を近づける: エネルギー融合

軽量化
・MediaPipe 推論と描画FPSを分離
・モデル複雑度0
・エフェクトの大半をキャッシュ済みCanvasスプライト化
・端末FPSに応じて自動品質調整
・粒子数上限 / 雷生成レート / DPRを制御

補足
カメラが使えない場合は自動でマウス操作モードに切り替わります。
