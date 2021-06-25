# FunCobal family

## Languages of FunCobal family

- プログラミング言語

  - [FunCobal](https://github.com/FunCobal-family/FunCobal) .fcb 　基幹言語

    - fDocker 　　システムモジュール：特殊外部機器制御処理モジュール
    - Texicon 　　システムモジュール：テキスト・文字列・マークアップ処理モジュール
    - fMExpr 　　システムモジュール：数式・定理・公理・定義・命題記述モジュール
    - fStmavector 　　システムモジュール：ベクトルマッピングデータ記述モジュール
    - fMacro 　　システムモジュール：プログラミング言語のマクロ機能モジュール

  - [Hjerbata](https://github.com/FunCobal-family/Hjerbata) .hjr 　　ビギナーに易しい姉妹言語
  - Preutonal(Pattern and Regular Expression Unified Text Operating Nucleus and Applies Language,) .ptxo 　　 AWK や Ruby のようなパターンや正規表現によるテキスト処理を行うシステムモジュール分立言語
  - Fiamscol(Functional Integrated Academic Mathematical and Scientific Computing Language
    ) .fims 　　数理科学計算のためのシステムモジュール分立言語
  - μFC .mfc 　　　中規模軽量組込み向け
  - T++ .tpp 　　　小規模軽量組込み向け
  - IDCS(Integrated Defined Commons System) .bd 　　　知識記述
  - ILDEF(Integrated Language for Defence) .kug 　　　セキュリティ向け

- データ記述言語
  - ChestDD
    - Standard: 汎用用途
    - Biblio: 書誌情報などメタ情報の列記
    - Streams: SNS 等の投稿データ
    - Pages: 記事や書籍などの各ページのデータ
    - Modules: 学科目情報の記述
    - Confi: 各種システムの設定ファイルとして使用する
    - Grams: 形式文法の定義ファイルとして使用する
    - Meta: 個別の詳細メタ情報の記述
    - Graph: グラフ構造の記述
- 問い合わせ言語
  - YADL(Yet Another Database Language)　　内部 DSL：データベース言語・問い合わせ言語
- マクロ言語
- シェル言語
  - [FC-Shell](https://github.com/FunCobal-family/FC-Shell) 　　 FunCobal family 附属のシェル言語
- アセンブリ言語
  - 細葉子(Yezi-diki)　　 FunCobal family の LLCIL

## Systems of FunCobal family

- \<[H Processing System](https://github.com/FunCobal-family/H-Processing-System)>　 Language Processing System
- \<[H SDK Tool Chain](https://github.com/FunCobal-family/H-SDK-Tool-Chain)>　 SDK Extensions for H Processing System
  - \<H Compiler Collection>　 FunCobal family Language Compilers
  - \<H Bins Codes>　 Binary Codes Tool with FunCobal family
  - \<H AutoHardin>　 FunCobal family Language Auto Builder
  - \<H Test Manager>　 Tester & Debugger
  - \<H Driven CronBase>　 CI & CD Host
  - \<H OriGen>　 Parser Generator
  - \<H Expressions>　 Lint, Syntax Highlight
- \<[HardingTsaa](https://github.com/FunCobal-family/HardingTsaa)>　 Package Manager&Installer
  - [./Hardinfile]　　 Package Build Script
  - [./* .tsaaspec]　 Library package Specification
- \<[FCPEG: FunCobal|FunctionalChes PEG](https://github.com/FunCobal-family/fcpeg)\>
- \<[Onigase: FunCobal Regexp](https://github.com/FunCobal-family/Onigase)> Regular Expressions System & Library
- \<[FunCobal on Cups](https://github.com/FunCobal-family/FunCobal-on-Cups)> Web Application Framework
- \<[BohTsaa](https://github.com/FunCobal-family/BohTsaa)> Multi-platform Application Framework

  ※IDE/Editor ... VisualStudio, VSCode, CLion, , , etc.

  ※Version Manager ... Git, GitHub, , , etc.

## 系列言語形式名前空間

構築言語にのみ配する

- Bantra : FanCobal/FunctionalChes LL Langs : ex. Yezi-diki, Chestnut Bytecode
- Hardin: FC HL Langs : ex. FunCobal, Hjerbata, FC-Shell
- Tolte : Ches HL Langs : ex. Chestnut

.

.

.　　　　　　　 ↙ Hardin: .\_

execute ← Bantra: .\_

.　　　　　　　 ↖ Tolte: .\*

## バイトコード/ワードコード

- LLCIL))Chestnut Bytecode (:BC,Tolte::Bantra:)
- LLCIL))"細葉子" a.k.a. "Yezi-diki" (:WC,Hardin::Bantra:)

## FIDOLS

Description :Package Identifying System File for HardingTsaa  
Acronym of : FunCobal Installing Dandified Original Leaves Specifier  
Configuration :  
[./* .fidols]  
　[./Hardinfile]  
　[./* .hjrspec] or [./* .tsaaspec]  
Management Method : like Package Managers of Gentoo Linux, and add specifications and implementations focused on to solve Satisfiability Problem.

## Specification of H Compiler Collection

Name : H Compiler Collection  
Description : Compilers for languages of FunCobal family, and Chestnut  
Outline : put Intermediate Language between Source and executive
Source to CIL : Source → CIL→ execute with Interpreter (with embedding Assembly in C++ code)  
Source to NASM: Source → NASM→ Object file  
CIL to Word Code : CIL → Word Code  
CIL : \*\*\*\* , Intermediate Language for Chestnut as a low-level programming language  
Implementation : Each of C++/Java/Dart/Julia/FunCobal  
Lead Developers : Garnet (for C++), Halka (for Java/Dart/Julia/FunCobal imp.)

## ICCF (Inter-Compiler-Compiler Framework)

"ICCF (Inter-Compiler-Compiler Framework)" are, for to glue programs crosswise languages, a concept that "bone", data of syntax trees interpreted under semantics, are exchanged across processing systems of each languages; and a system providing process of the bones.
