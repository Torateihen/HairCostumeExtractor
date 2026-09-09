髪や衣装だけを残して、それ以外のメッシュと、使っていない骨をまとめて消すUnityエディタ拡張です。

### 導入
VCC / ALCOM の Settings > Packages > Add Repository に次のURLを追加してください。

```
https://raw.githubusercontent.com/Torateihen/HairCostumeExtractor/main/index.json
```

### Ver1.1.0 の変更
- 実行結果から「プレハブとして保存」「unitypackage で書き出す」ボタンを追加
- 用途が「不明」でチェックの入っていないメッシュがあるとき、一覧と実行前の確認に警告を出すようにした
- 保護して残すオブジェクトを一覧で表示し、1件ずつ「消す」に変更できるようにした
- 生成物の置き場所をまとめ、やり直しても増えないようにした
- メッシュ一覧に検索ボックスと並べ替えを追加
- チェック状態と設定を覚えて、開き直しても復元するようにした
- 実行内容を 抽出レポート.txt に書き出すようにした
- VCC（VPM）に対応

BOOTH: https://bbeyemtkw.booth.pm/items/8808121
