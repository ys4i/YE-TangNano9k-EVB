# YE-TangNano9k-EValuationBoard

コミックマーケット(C106)同人誌用TangNano9kの開発ボードです  
某月電子通商 Bタイプ基板(95×72mm)と寸法に互換性があります  
`販売コード[110243] B基板用アクリルパネル(アクリル板) 2mm厚(透明)`  
などでパネルを作れます

Tang Nano 9Kを用いた評価用ボードです。KiCad 9.0.3で設計されており、コミックマーケット(C106)頒布向けに作成されました。

## 特長
- 基板サイズ: 95 mm × 72 mm。某月電子通商 Bタイプ基板と同寸で、市販のB基板用アクリルパネルが使用可能。
- Seeed Studio製Tang Nano 9Kモジュールを搭載 (U1)。
- 24ピン×2列の拡張用ソケットコネクタを左右に配置 (J1, J2)。
- 4桁7セグメントLED表示器 OSL40391-IRA を搭載し、簡単な数値表示が可能。
- ブザー UGCM1205XP と、駆動用NPNトランジスタ 2SC1815 (Q1) を装備。
- 入力インターフェースとして SPDTスイッチ (SW1) とタクトスイッチ2個 (SW2, SW3) を搭載。

## プロジェクト構成
- `YE-tangnano9k-EVB.kicad_pro` : プロジェクト設定ファイル
- `YE-tangnano9k-EVB.kicad_sch` : 回路図
- `YE-tangnano9k-EVB.kicad_pcb` : 基板レイアウト
- `sym-lib-table` : シンボルライブラリ設定

## 使い方
KiCad 9.0以降で `.kicad_pro` ファイルを開き、回路図や基板データを編集してください。ファイル形式の詳細は [KiCad File Formats Documentation](https://dev-docs.kicad.org/en/file-formats/index.html) を参照してください。

