# Guguru Sans Code

Guguru Sans Code は、開発者向けフォントの [Google Sans Code](https://github.com/googlefonts/googlesans-code) と日本語フォントの [IBM Plex Sans JP](https://github.com/IBM/plex) を合成したプログラミング向けフォントです。

IBM Plex Sans JP の持つモダンで高い可読性はそのままに、Google Sans Code 由来の調和的で判読性の高い英数字を提供することを目指しています。

[👉 ダウンロード](https://github.com/yuru7/guguru-sans-code/releases/latest)
※「Assets」内の zip ファイルをダウンロードしてご利用ください。

## 特徴

以下の特徴を備えています。

- Google Sans Code 由来の視認性が高く美しいラテン文字
- IBM Plex フォントファミリーの一員である IBM Plex Sans JP 由来のモダンで読み易い日本語文字
- 全角スペースの可視化

### バリエーション

| 種類 | 説明 | 命名パターン |
| --- | --- | --- |
| 文字幅比率 半角1:全角2 | Google Sans Code を縮小することで、半角1:全角2の文字幅比率となるように合成したバリエーション。 | `GuguruSansCode-*.ttf`<br>※ファイル名に `35` が含まれて **いない** もの |
| 文字幅比率 半角3:全角5 | Google Sans Code を縮小せずに合成し、半角3:全角5の文字幅比率としたバリエーション。半角1:全角2と比べ、英数字などの半角文字がゆとりのある幅で表示される。| `GuguruSansCode35-*.ttf`<br>※ファイル名に `35` が含まれて **いる** もの |

## 表示サンプル

TODO ここに表示サンプルの画像を追加する

| 通常版 (幅比率 半角1:全角2) | 35版 (幅比率 半角3:全角5) |
| :---: | :---: |
| ![image](https://placehold.jp/600x300.png?text=GuguruSansCode) | ![image]() |

## ビルド

### 環境

- [FontForge](https://fontforge.org/en-US/)
- Python 3.x

### 依存パッケージのインストール

```shell
pip install fonttools
```

### ビルドの実行 (PowerShell)

TODO make.ps1 はこれから作成する

```powershell
./make.ps1
```

スクリプトが正常に完了すると、`build` ディレクトリにフォントファイルが生成されます。

### ビルドオプション

`make.ps1` を編集することで、`fontforge_script.py` に以下のオプションを渡して、生成するフォントをカスタマイズできます。

- `--35`: 半角3:全角5 の幅にする

## ライセンス

SIL OPEN FONT LICENSE Version 1.1 が適用され、商用・非商用問わず利用可能です。

- `Guguru Sans Code` is licensed under the [SIL Open Font License, Version 1.1](./LICENSE).
- `Google Sans Code` is licensed under the [SIL Open Font License, Version 1.1](./source/Google-Sans-Code/OFL.txt).
- `IBM Plex Sans JP` is licensed under the [SIL Open Font License, Version 1.1](./source/IBM-Plex-Sans-JP/license.txt).
