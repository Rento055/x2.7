# Nyanko_x4.7
x4.7は代行者向けのBan保障システムです。  
依頼者のアカウントを復元または複製することができます。  
<sup>※無料版は読み込みのみ対応</sup>

## ダウンロード
[./scripts/](https://github.com/Rento055/x4.3/tree/main/scripts) から最新バージョンのスクリプトをダウンロードしてください。  
[./offsets](https://github.com/Rento055/x4.3/tree/main/offsets) からオフセットのみをダウンロードすることも可能です。  

## 注意事項  
オフセットのjsonファイルをそのまま利用する場合、実行環境によってはコメントがエラーを吐く可能性があります。  
つきましては、以下のコードをご使用ください。
```js
let data = `{}`;
data = JSON.parse(data.replace(/\/\*[\s\S]*?\*\/|\/\/.*/g, ""));
```
また、オフセットはすべて10進数表記で記述されています。  
> 配列の説明  

- char: [ オフセット, キャラ数 ]  
- err_num: [ エラーキャラの番号 ]  
## 宣伝
> 有料版**Nyanko_x4.1**の紹介

更に高性能なスクリプトをお求めの方におすすめ！  
- メニューが豊富  
- 全端末対応(IOSの場合はUgphone必須)  
- アプデ毎の更新(ダウンロード)が不要  
- 買い切り2,000円  

詳細、ご購入はサポートサーバーまでご参加ください。  
サポートサーバー: https://discord.gg/knSUYAHwRm
