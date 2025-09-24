# MindAR マーカー音声再生アプリ

## セットアップ手順

1. **MindARターゲットファイルの生成**
   - https://hiukim.github.io/mind-ar-js-doc/tools/compile/ にアクセス
   - YU-KI.jpg画像をドラッグ&ドロップでアップロード
   - コンパイル完了後、生成された.mindファイルをダウンロード
   - ダウンロードしたファイルを`YU-KI.mind`にリネーム

2. **ファイル配置**
   - index.html
   - YU-KI.mind (上記で生成)
   - output_clip.mp3
   - YU-KI.jpg (参考用)

3. **デプロイ**
   - 全ファイルをHTTPSサーバーにアップロード
   - HTTPSが必須（カメラアクセスのため）

## 使用方法

1. スマートフォンやカメラ付きデバイスでアクセス
2. [カメラを開始]ボタンをクリック
3. カメラアクセスを許可
4. YU-KI.jpg画像をカメラに向ける
5. マーカーが認識されると音声が再生されます

## 対応ブラウザ

- iPhone: Safari, Chrome
- Android: Chrome
- PC: Chrome, Firefox, Safari

## MindARの利点

- 写真画像（YU-KI.jpg）の検出に最適化
- モバイルデバイスでの検出精度が向上
- AR.jsより安定した動作
- 複雑な画像でも高い認識率

## トラブルシューティング

- カメラが起動しない場合：HTTPSでアクセスしているか確認
- マーカーが検出されない場合：YU-KI.mindファイルが正しく生成されているか確認
- 音声が再生されない場合：output_clip.mp3ファイルが同じフォルダにあるか確認
