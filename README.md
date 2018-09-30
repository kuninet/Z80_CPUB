# Z80マイコンボード

- SBC8080バスにつながるZ80 CPUボードのデータ類です。
- CPUボード+SBC8080 SUBボードのセットなどでコンピューターとして動作します。

## 回路図

[Z80CPUB](img/Z80-CPUB.pdf)

## 部品表

[部品表](KiCAD/Z80-CPUB.ods)はOpenOffice等でひらくことのできるフォーマットとなっています。

## ファイル/ディレクトリ

ファイル/ディレクトリの構成は以下のとおりです

|ファイル/ディレクトリ|概要|
|:--|:--|
|KiCAD/PCB/|基板製造用ガーバーファイル等|
|KiCAD/Z80-CPUB.ods|部品一覧表|
|img/Z80-CPUB.pdf|回路図 PDF版|
|KiCAD/Z80-CPUB*.*|KiCADファイル|

## 注意点

- SBC8080ルーズキットと完全互換ではありません。
  - DMAは行なえません。(#BUSREQ/#BUSACKに対応していない)
  - DMAに伴う#IOR/Wや#MEMR/Wのハイインピーダンス対応を実施していません。


## 参照

[電脳伝説:SBC8080ルーズキット](https://vintagechips.wordpress.com/2018/06/24/sbc8080-cpu%E3%83%AB%E3%83%BC%E3%82%BA%E3%82%AD%E3%83%83%E3%83%88/)

