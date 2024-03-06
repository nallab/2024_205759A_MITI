### データ拡張による動機づけ面接のためのMITIコード推定手法の改良
動機づけ面接データセットにデータ拡張の手法を実践し、MITIコード推定を行って手法を評価しました。

## 実験手順
1. augmentation.ipynbを起動
2. セル[3]で拡張の倍率や[MASK]の数等を設定
3. 全てのセルを実行
4. augmentation.ipynbをshutdownして、classification.ipynbを起動
5. 全てのセルを実行

5.の手順の後、result内のp1〜p5のディレクトリに5分割交差検証で出た5回分の混同行列がtrain、valid、testの名前で保存されています。calc_average_matrices.ipynbを実行することで精度等の情報を見ることができます。