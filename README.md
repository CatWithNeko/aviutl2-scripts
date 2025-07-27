# aviutl2-scripts
自作aviutl2スクリプト置き場です

いろいろと粗がありますがご容赦ください

## 動作確認
[Aviutl Exedit2](https://spring-fragrance.mints.ne.jp/aviutl/)
beta4で動作確認


## 導入・削除
`aviutl2.exe`のあるフォルダに`data`フォルダがある場合、`data\script`内またはその子フォルダ内に置く/消す

`aviutl2.exe`のあるフォルダに`data`フォルダがない場合、`C:\ProgramData\aviutl2\Script`内またはその子フォルダ内に置く/消す

デフォルトだとフィルタ追加メニューの色調整とか抽出とかの中に入ります

オブジェクト追加メニューで整理できます(再起動後の設定の保持に管理者権限がいるかも)

## 簡単な説明

### Lens
レンズディストーション

歪み量、中心を設定可能


### LongShadow
方向と長さを指定して立体的なロングシャドーとフラットシャドーを描画します

個別オブジェクトで回転させたいときはFixRotateオンにしてフィルタ効果のほうから回転させてください

Flatモードの挙動はAodarumaさんの[FlatShadow](https://github.com/Aodaruma/Aodaruma-AviUtl-Script)から強く影響を受けています

### Gamma

RGBまたは全体にかかるガンマ補正

### Level

レベル補正っぽいやつ

ネガポジ反転にも使える

### Dither

閾値がランダム変化する二値化

ザラザラ質感になる

### Halftone
なんちゃってハーフトーン

水玉を大きくしすぎると水玉それぞれが四角くクロップされる仕様です

フレームバッファや部分フィルタではBlendモードが動作しない既知の不具合があるので、そのときはチェックボックスでオフにしてください

## 更新履歴
v1.0.0 2025/7/28 Googleドライブに置いていたものをgithubに移した
