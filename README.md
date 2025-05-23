This is a fork of the original [@kobalab/majiang-ui](https://github.com/kobalab/majiang-ui) created by [@kobalab](https://github.com/kobalab) with contributions from other members.

It is forked and tweaked for personal use only and I will take it offline if the original author complains.

Thanks.

------

### Tweaks:

* 2025/04/18: Switch to xml then convlog() to json from @kobalab/tenhou-log, avoid fetching from server mode of the same lib

------

# majiang-ui
麻雀UIライブラリ

手牌表示、盤面表示、牌譜再生 など画面表示やユーザとのインタラクションを実現するクラス群を提供します。

ver.2.0.0 以降の[電脳麻将](https://github.com/kobalab/Majiang)は、その実装に本パッケージを使用しています。

## インストール
```sh
$ npm i @kobalab/majiang-ui
```

## 使用法
```javascript
const Majiang = require('@kobalab/majiang-core');
Majiang.UI    = require('@kobalab/majiang-ui');
```

## 提供機能
| クラス名                 | 機能
|:-------------------------|:--------------------------------------------------
|``Majiang.UI.pai``        | 牌表示関数を生成する関数
|``Majiang.UI.audio``      | 音声出力関数を生成する関数
|``Majiang.UI.Shoupai``    | 手牌を表示するクラス
|``Majiang.UI.Shan``       | 牌山を表示するクラス
|``Majiang.UI.He``         | 捨て牌を表示するクラス
|``Majiang.UI.Board``      | 卓情報を表示するクラス
|``Majiang.UI.HuleDialog`` | 和了・流局時のダイアログを表示するクラス
|``Majiang.UI.Player``     | 打牌選択などのUIを実現するクラス
|``Majiang.UI.GameCtl``    | 対局速度などの付属UIを実現するクラス
|``Majiang.UI.PaipuFile``  | 牌譜一覧を表示するクラス
|``Majiang.UI.Paipu``      | 牌譜ビューアを実現するクラス
|``Majiang.UI.Analyzer``   | 検討モードを実現するクラス
|``Majiang.UI.PaipuStat``  | 牌譜を集計するクラス
|``Majiang.UI.PaipuEditor``| 牌譜エディタを実現するクラス
|``Majiang.UI.Util``       | ユーティリティ・ルーチン(fade-in/out, selector など)

## API仕様

* [API仕様](https://github.com/kobalab/majiang-ui/wiki) (執筆中)

## ライセンス
[MIT](https://github.com/kobalab/majiang-ui/blob/master/LICENSE)

## 作者
[Satoshi Kobayashi](https://github.com/kobalab)
