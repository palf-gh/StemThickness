# StemThickness

[日本語](#japanese)

## VariableStroke support

When [VariableStroke](https://github.com/palf-gh/VariableStroke) is installed and a glyph uses live variable strokes,
the reporter finds the nearest point on the generated outline and measures from
that outline to the opposite outline. The editable centerline is ignored. Install
the linked VariableStroke version and restart Glyphs 3 after rebuilding or
replacing this reporter. Ordinary outline glyphs continue to use
the original measurement path.

Show Thickness Plugin for [Glyphs App](https://glyphsapp.com/). The tool shows how thick the stem is at the pointed location:

![Show Thickness illustration](images/StemThickness.gif)

Right-click to open the context menu and choose *Add Guide for Measurement* to turn the current measurement into a static guide in measurement mode.

### Installation and Usage

1. In *Window > Plugin Manager,* look for *Show Stem Thickness* and press the *Install* button next to it.
2. Restart Glyphs.

For VariableStroke support, build this fork and install its
`StemThickness.glyphsReporter` in the Glyphs 3 Plugins directory. The Plugin
Manager entry installs the upstream release.

Choose *View > Show Stem Thickness* (Cmd-Opt-Shift-A) to toggle the stem measurement.

### Thanks

Thanks to Georg Seifert (@schriftgestalt) for his help with improving performance.

# License

Copyright 2015 Rafał Buchner (@rafalbuchner).

With code samples by Georg Seifert (@schriftgestalt), Rainer Scheichelbauer (@mekkablue) and Mark Frömberg (@Mark2Mark).

Licensed under the Apache License, Version 2.0 (the "License");
you may not use the software provided here except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

See the License file included in this repository for further details.

<a id="japanese"></a>

# 日本語

## VariableStroke への対応

[VariableStroke](https://github.com/palf-gh/VariableStroke) をインストールした環境では、可変ストロークを使うグリフの生成済みアウトラインを測定します。カーソルに最も近いアウトライン上の点を見つけ、そこから反対側のアウトラインまでの幅を表示します。編集用の中心線は測定に使いません。対応版の VariableStroke と本プラグインをインストールした後、Glyphs 3 を再起動してください。通常のアウトライングリフも従来どおり測定できます。

StemThickness は [Glyphs](https://glyphsapp.com/) 用のステムの太さを測るプラグインです。カーソルで指した位置の太さを表示します。

![ステムの太さを表示する例](images/StemThickness.gif)

測定モードで右クリックし、コンテキストメニューの *Add Guide for Measurement* を選ぶと、現在の測定結果を固定ガイドとして追加できます。

### インストールと使い方

1. *ウインドウ > プラグインマネージャ* で *Show Stem Thickness* を探してインストールします。
2. Glyphs を再起動します。

VariableStroke 対応版を使う場合は、このフォークをビルドして生成される `StemThickness.glyphsReporter` を Glyphs 3 の Plugins ディレクトリに配置してください。プラグインマネージャから入るのは元の公開版です。

*表示 > Show Stem Thickness*（Cmd-Option-Shift-A）で測定表示を切り替えます。

### 謝辞

パフォーマンス改善に協力してくださった Georg Seifert（@schriftgestalt）に感謝します。

## ライセンス

Copyright 2015 Rafał Buchner（@rafalbuchner）。Georg Seifert（@schriftgestalt）、Rainer Scheichelbauer（@mekkablue）、Mark Frömberg（@Mark2Mark）のコード例を含みます。

Apache License, Version 2.0 に基づき公開されています。詳細は、このリポジトリの [LICENSE](LICENSE) を参照してください。
