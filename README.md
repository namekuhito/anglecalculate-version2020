# anglecalculate-version2020は下肢ROMテストのシステム化についてのソースコードである。
https://github.com/sunagat/anglecalculate20180906を参考に構築した。

newapp1_refinementは関節測定を行うインターフェイスである。

：主な処理：
画面の遷移
OpenPoseの設定・実行
Cpp_angle_calculateの設定・実行
測定値の保存
グラフの生成

cpp_angle_calculate_refinementはOpenPoseからの関節座標を計算・結果画像の作成を行う。

：主な処理：
OpenPose検出点データの読み込み
ベッド直線の検出
関節可動域の計算
結果画像の描画・生成

本システムはOpenPoseを用いている。https://github.com/CMU-Perceptual-Computing-Lab/openpose
