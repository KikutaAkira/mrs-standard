# MRS Compatibility Test v0.1
Status: DRAFT

## CT-001 Core Preservation

目的：
企業独自の拡張機能によるMRS Coreの改変を防ぐ。

試験：
拡張導入前後のCore仕様を比較する。

PASS：
Coreの必須仕様・インターフェースに
互換性を破壊する変更がない。

FAIL：
Coreが無断で改変・置換されている。

※試験方法の詳細はCore仕様確定後に策定する。
## CT-002 Extension Independence

目的：特定メーカーへの技術的依存を防ぐ。

試験：Vendor Extensionを無効化する。

PASS：MRS Coreの必須機能が正常動作する。

FAIL：拡張機能なしではCoreが動作しない。

NOT TESTED：Core仕様未確定または未試験。
