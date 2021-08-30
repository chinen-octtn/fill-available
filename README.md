# -webkit-fill-availableの検証

2021年8月末時点

## SmartPhone
iOS Safari・・・OK
Android Google Chrome・・・-webkit-fill-availableが効かない。100vhだとアドレスバーの高さが引かれずに画面下にはみ出てしまう

## PC
Chrome・・・100vhでOK
Safari・・・100vhでOK
Firefox・・・100vhでOK

## 動作確認環境
node v14.17.3
npm 6.14.13

## ローカル開発環境の起動

初回のみ
```
npm i
```

```
npm start
```

2回目以降

```
npm start
```

